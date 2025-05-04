# OpenSSL Encryption Demos

This repository demonstrates basic **symmetric** and **asymmetric** encryption using OpenSSL on Linux.

## 🔐 Symmetric Encryption (AES-256-CBC)

- `demofile.txt`: Original plaintext file.
- `secret.key`: Randomly generated 256-bit key (ignored in Git).
- `encrypted.bin`: Encrypted version of `demofile.txt`.
- `decrypted.txt`: Output after decryption.

## 🔑 Asymmetric Encryption (RSA)

Located in the `asymmetric/` folder:
- `public.pem`: Public RSA key
- `private.pem`: Private RSA key (ignored in Git)
- `message.txt`: Message to encrypt
- `encrypted_message.bin`: Encrypted with public key
- Decryption done using the private key

## ⚠️ Notes

- This is for educational/demo purposes only.
- Keys are excluded via `.gitignore`.
