# QR Code Generator

A simple Python desktop application to generate QR codes from URLs using Tkinter and the `qrcode` library.

## Features

- Enter any URL and generate a QR code instantly
- QR code is displayed in the app and saved as `qrcode.png`
- User-friendly GUI built with Tkinter

## Requirements

- Python 3.x
- Libraries:
  - tkinter (standard library)
  - qrcode
  - pillow

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/qr-code-generator.git
   cd qr-code-generator
   ```

2. Install dependencies:

   ```bash
   pip install qrcode pillow
   ```

## Usage

1. Run the application:

   ```bash
   python main.py
   ```

2. Enter a URL in the input field and click "Generate QR Code".
3. The QR code will be displayed and saved as `qrcode.png` in the project directory.

## File Structure

- `main.py` — Main application code
- `qrcode.png` — Generated QR code image
- `.gitignore` — Git ignore rules
- `README.md` — Project documentation

## License

MIT License
