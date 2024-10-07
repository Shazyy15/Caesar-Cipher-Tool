# 🔐 Caesar Cipher Tool

Welcome to the **Caesar Cipher Tool**! This program allows users to **encrypt** and **decrypt** messages using the **Caesar Cipher** technique, a classic encryption method that shifts characters in the alphabet. 

---

![C++](https://img.shields.io/badge/Language-C++-blue.svg)
![Cybersecurity](https://img.shields.io/badge/Topic-Cybersecurity-green.svg)
![Encryption](https://img.shields.io/badge/Encryption-Caesar%20Cipher-lightgrey.svg)


## 📜 Project Overview

The **Caesar Cipher Tool** enables users to:
- **Encrypt** messages by shifting each letter forward in the alphabet.
- **Decrypt** messages by shifting each letter backward, restoring the original message.
- Choose how many positions to shift (0-25) to customize encryption.

Developed by **Shazil Shahid**, this tool is designed for anyone interested in exploring basic encryption techniques in a user-friendly, interactive way.

## 🚀 Features

- **Interactive User Interface**: The tool uses an engaging command-line interface, with options to encrypt or decrypt multiple messages in one session.
- **Color-coded Output**: Feedback is displayed with colors (if supported by the terminal) to enhance the user experience.
- **Multiple Attempts**: After each operation, users can choose to continue with another message or exit the tool.
  
## 🛠️ How to Use

### Prerequisites

1. Clone the repository:
   ```bash
   git clone https://github.com/Shazyy15/Caesar-Cipher-Tool.git
    ```
Navigate to the project directory:

 ```
cd Caesar-Cipher-Tool
 ```
Compile the program:

 ```
g++ CaesarCipherTool.cpp -o CaesarCipherTool
 ```
Run the program:
 ```

./CaesarCipherTool
 ```
Usage
- Select whether you want to Encrypt or Decrypt a message.
- Enter the message you'd like to encrypt or decrypt.
- Input a shift amount between 0 and 25.
- View the encrypted or decrypted message, and choose whether to process another message.
## 💻 Demo
 ```
==========================================
||    Caesar Cipher Tool - by Shazil Shahid   ||
==========================================
 This tool encrypts and decrypts messages using
 the Caesar Cipher encryption method.

Select an option:
1. Encrypt a message
2. Decrypt a message
Enter your choice (1 or 2): 1

Enter your message: HelloWorld
Enter the shift amount (0-25): 4

==========================================
Encrypted Message: LippsAsvph
==========================================

Would you like to try again? (y/n): y
 ```
## 🌟 Future Enhancements
- Add an option to automatically detect shift amount for decryption.
- Create a GUI version for easier accessibility.
- Expand the encryption methods to include other classical ciphers like Vigenère Cipher.
## 👨‍💻 About Developer
This project was created by Shazil Shahid, a cybersecurity enthusiast. Feel free to connect with me.

## 🤝 Contributions
Contributions, suggestions, and improvements are always welcome! If you'd like to contribute, please feel free to fork the repository, submit a pull request, or open an issue.

###### Thank you for using the Caesar Cipher Tool! Enjoy encrypting and decrypting messages!


