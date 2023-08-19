import pyqrcode
from pyqrcode import QRCode
s="https://github.com/MDsabir786"
url=pyqrcode.create(s)
url.svg("myfirstQRCode.svg",scale=10)
