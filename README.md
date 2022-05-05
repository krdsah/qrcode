# HTML5 QRCodes
Repository ini diperuntukan memudahkan dalam hal login hotspot mikrotik.
Selain fitur yang dimiliki lengkap, juga sangat mudah digunakan.
## Cara Pemakaian :
1. Tambahkan button di login.html
```
<button onclick="window.location='https://krdsah.eu.org/qrcode/';">QR Code</button>
```
2. Tambahkan script berikut di MikroTik via Terminal.
```
/ip hotspot walled-garden ip

add action=accept comment="Mikhmon QR Code Scanner" disabled=no dst-host=krdsah.eu.org
```

# Powered by HTML5 QRCode
