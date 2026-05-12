# Qr
import qrcode
message = input("Entrer the message:")
file_path = "python_system_qr code.png"
qr = qrcode.QRCode()
qr.add_data(message)
img =qr.make_image()
img.save(file_path)
