# qr-code-generator
QR Code Generator

 Project Description

This project is a simple Python-based QR Code Generator. It takes information such as a UPI ID from the user and generates a QR code that can be saved and displayed as an image.

 Objective

The main objective is to learn how to use Python libraries, take user input, generate QR codes, and save them as image files.

 Technologies Used

- Python
- QRCode Library
- Pillow (PIL)

Installation

Install the required library using:

pip install qrcode[pil]

 How It Works

1. The program asks the user to enter a UPI ID.
2. It creates a UPI payment URL using the entered ID.
3. The "qrcode" library converts the URL into a QR code.
4. The QR code is saved as a PNG image and displayed.

Usage Example

Run the program and enter:

Enter your UPI ID = example@upi

The program will generate the QR code image.

 Features

- Simple and easy to use
- Generates QR codes automatically
- Saves QR codes as PNG images
- Uses user-provided information

 Future Improvements

- Add a graphical user interface (GUI)
- Allow users to enter payment amount and message
- Add QR code customization options
- Add input validation

 Conclusion

This project demonstrates the practical use of Python for generating QR codes and helps in understanding user input, libraries, string formatting, and file handling.
