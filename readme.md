# QR Code Library

Library QR Code untuk Sistem Pengelolaan Aset Sekolah.

## Instalasi via jsDelivr



## Penggunaan

```javascript
QRCode.toCanvas(canvas, 'AST-2024-001', { 
  width: 256,
  color: { dark: '#000000', light: '#FFFFFF' }
}, (error) => {
  if (error) console.error(error);
});
License
MIT