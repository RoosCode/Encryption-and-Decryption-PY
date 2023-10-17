# Encryption-and-Decryption-PY V1.0.0.0
This Python program provides a graphical user interface (GUI) for performing AES encryption and decryption using the cryptography library in combination with tkinter. Here's a breakdown of the code and how to use it:

1. Prerequisites
Before running this code, you need to make sure you have the required libraries installed. You can install them using pip:

pip install tkinter
pip install cryptography

2. Code Structure
The program consists of several functions that serve specific purposes:

generate_key: This function generates a random key for encryption and decryption and saves it in a file called "key.key".

encrypt_message: This function reads the encryption key from "key.key," uses it to create a Fernet cipher, encrypts the input message using AES encryption, and displays the encrypted message in the GUI.

decrypt_message: This function reads the encryption key from "key.key," uses it to create a Fernet cipher, decrypts the input encrypted message, and displays the decrypted message in the GUI.

main_screen: This function creates the main GUI window using tkinter. It includes text entry fields for the original message, the encrypted message, and the decrypted message, along with buttons for encryption and decryption. The "Generate Key" function is called to create the encryption key at the start.

3. How to Use
Follow these steps to use the program:

Run the Program: Run the Python script, and a GUI window will appear.

Enter a Message: In the "Enter a message" field, type the message you want to encrypt.

Encryption: Click the "Encrypt" button to encrypt the message. The encrypted message will appear in the "Encrypted message" field.

Decryption: To decrypt the message, click the "Decrypt" button. The decrypted message will appear in the "Decrypted message" field.

Key Generation: The program generates an encryption key ("key.key") automatically at the start. This key is used for both encryption and decryption. You don't need to manage the key; it's handled by the program.

Copy to Clipboard (Optional): You can copy the decrypted message to your clipboard by selecting and copying it from the "Decrypted message" field.

Handling Errors: If there are any errors during encryption or decryption, an error message will be displayed in a pop-up window.

4. Customization
This code provides a basic example of AES encryption and decryption using tkinter. You can customize and enhance it further according to your specific requirements, such as implementing more secure key management practices or adding additional features to the GUI.

Please note that this code is for educational purposes/ my portfolio, and for real-world applications, you should consider additional security measures and key management practices. I will add more securitymeasures in later versions. This Code is a living document. Also note this will be the first real code I am publishion within GetHub.Hello, World! and thank you for reading.  
