Caesar Cipher Program

Description:

This program implements the Caesar cipher, a simple substitution cipher that shifts each letter in the plaintext by a fixed amount. The program allows the user to encode or decode a message by specifying the shift amount and cipher direction.

Features:

    Encodes or decodes messages using the Caesar cipher
    Allows the user to specify the shift amount
    Provides both encoding and decoding functionality

Technologies:

    Python

Installation:

    Clone the repository and navigate to the cesar_main.py file.
    Execute the following command in your terminal:

python cesar_main.py

Usage:

The program will prompt you to enter the desired cipher operation (encode or decode), the message to be processed, and the shift amount. Once you have entered the necessary information, the program will display the encoded or decoded message.

Example:

To encode the message "hello" using a shift of 3, you would enter the following commands:

python cesar_main.py
encode
hello
3

The program will then display the encoded message: "kdssh".

To decode the message "kdssh" using a shift of 3, you would enter the following commands:

python cesar_main.py
decode
kdssh
3

The program will then display the decoded message: "hello".
