SECURE DATA HIDING IN IMAGE USING STEGANOGRAPHY

PROJECT OVERVIEW

This project implements a steganography-based tool that allows users to securely hide and reveal secret messages within images using the Least Significant Bit (LSB) technique. Unlike traditional encryption methods, this tool conceals the very existence of the message, providing an additional layer of security.

FEATURES

•Hide secret messages within image files.

•Extract hidden messages from steganographed images.

•Maintains high image quality after embedding data.

•Easy-to-use terminal interface.

•Error handling for invalid inputs and missing files.

TECHNOLOGIES USED

Programming Language:

•PYTHON


Libraries:

•stegano: For hiding and revealing secret messages.

•Pillow (PIL): For image processing tasks.

•os: For handling file paths and file validation.


Tools and Platforms:

•Visual Studio Code (VS Code)

•Windows OS

INSTALLATION GUIDE

1. Clone the Repository

git clone <repository-link>
cd <project-directory>


2. Install Required Libraries
Run the following commands in the terminal:

pip install stegano
pip install pillow


3. Run the Script

python steganographed.py

USAGE INSTRUCTIONS

1. Hide a Message in an Image

Choose the "Hide Message" option.

Enter the path of the image file.

Type the secret message you want to hide.

The output image with the hidden message will be saved as hidden_image.png.



2. Reveal a Hidden Message

Choose the "Reveal Message" option.

Enter the path of the steganographed image.

The hidden message will be displayed in the terminal.



3. Exit the Program

Select the "Exit" option to close the program.
