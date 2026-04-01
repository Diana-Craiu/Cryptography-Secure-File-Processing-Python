## Implementation Summary

### Cryptographic Approach

The system combines:

- RSA → for digital signatures  
- AES → for file encryption  
- PBKDF2 → for secure key derivation  

---

### Encryption Flow

1. Generate random salt and IV  
2. Derive encryption key from password (PBKDF2)  
3. Encrypt file using AES  
4. Store encrypted output  

---

### Signing Process

1. Generate RSA key pair  
2. Sign encrypted file using private key  
3. Store signature separately  

---

### Verification

1. Load public key from certificate  
2. Verify signature  
3. Confirm file integrity  

---

### Security Considerations

- Use of random IV ensures unique encryption  
- PBKDF2 prevents brute-force attacks  
- Digital signatures ensure authenticity  