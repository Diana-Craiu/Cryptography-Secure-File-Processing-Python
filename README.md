## Cryptography & Secure File Processing (Python)

This project demonstrates the implementation of secure file encryption, digital signing, and integrity verification using modern cryptographic techniques.

---

## Overview

The project focuses on protecting file confidentiality and integrity through a combination of symmetric and asymmetric cryptography.

Key components include:

- RSA key generation and X.509 certificate creation  
- AES-based file encryption  
- Digital signature generation and verification  
- Password-based key derivation (PBKDF2)  

---

## Functionality

- Encrypts files using AES with randomly generated IVs  
- Signs encrypted files using RSA private keys  
- Verifies signatures using public keys from certificates  
- Ensures data integrity and authenticity  

---

## Additional Features

- File monitoring system that detects changes  
- Automatic re-signing of modified files  
- Secure key storage and serialization  

---

## Technologies

- Python  
- Cryptography library  
- GPG (for file signing)  

