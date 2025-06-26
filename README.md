====================================
COMPANY: CODETECH IT SOLUTIONS  
NAME: KAUSHIK SAMBE  
INTERN ID: CT04DG899  
DOMAIN: Cyber Security & Ethical Hacking  
DURATION: 4 WEEKS  
MENTOR: NEELA SANTOSH  
====================================

# Advanced Encryption Tool

## Overview
The Advanced Encryption Tool is a robust Python application designed to securely encrypt and decrypt files using the AES-256 encryption algorithm. It features a user-friendly interface, allowing users to protect sensitive data with strong cryptographic standards.

## Features
- **AES-256 Encryption:** Utilizes industry-standard AES-256 for file encryption and decryption.
- **Password-Based Key Derivation:** Securely derives encryption keys from user-provided passwords.
- **Simple Interface:** Command-line prompts guide users through encryption and decryption processes.
- **Cross-Platform:** Works on Windows, macOS, and Linux.

## Files
- **main.py:** Entry point for the application; provides the user interface.
- **encryption.py:** Contains core functions for encrypting and decrypting files.
- **requirements.txt:** Lists required Python packages.
- **README.md:** Documentation and usage instructions.
- **encrpted.txt:** Example output file generated after encryption.
- **decrypted.txt:** Example output file generated after decryption.

## Installation
To install the required dependencies, run:
```
pip install -r requirements.txt
```

## Usage
1. Run the application:
   ```
   python main.py
   ```
2. Follow the on-screen instructions to:
   - Encrypt a file: Provide the file path, output name, and password.
   - Decrypt a file: Provide the encrypted file path, output name, and password.

## Output
- After encryption, the output file (e.g., `encrpted.txt`) will contain the encrypted data.
- After decryption, the output file (e.g., `decrypted.txt`) will contain the original plaintext data.

## Contributing
Contributions are welcome. Please submit issues or pull requests to improve the tool.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.