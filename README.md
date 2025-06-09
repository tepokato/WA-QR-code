# Work Area QR Code Generator

This lightweight web app helps generate QR codes for FedEx-style work area identifiers. Designed for sort managers, supervisors, or team leads, it simplifies creating scannable codes for labeling and organizing vans, zones, or equipment.

🔧 Features

✅ Input-based QR code generation (2-character prefix + 3-digit work area number)

📱 Mobile-friendly and responsive design

🎨 Clean, modern UI with visual feedback and accessibility support

📎 Displays large, readable work area number beneath the QR

🚫 Validates incorrect inputs and prevents invalid QR code generation


🚀 Getting Started

To use the app:

1. Enter the first two characters of the work area code (e.g., W0).


2. Enter the last three digits (e.g., 346 for W0346).


3. Click "Generate QR Code".



The QR code and the corresponding work area number will be displayed for printing, scanning, or posting.

📦 Usage

No backend or installation needed. Just open the HTML file in any modern web browser.

git clone https://github.com/yourusername/qr-code-generator.git
cd qr-code-generator
open QrgenV3.html

🖼 Example

Entering W0 and 346 will generate a QR code with content W0346 and display 346 underneath.

🛡️ Validation

Prefix must be exactly 2 alphanumeric characters.

Work area number must be exactly 3 digits.

Alerts guide the user if inputs are incomplete or invalid.


🧱 Built With

HTML5, CSS3

JavaScript

QRCode.js


📄 License

MIT License
