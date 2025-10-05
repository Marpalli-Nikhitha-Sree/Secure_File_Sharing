# Secure File Sharing using Steeganography and Encryption

## Overview
This project demonstrates a **dual-layer security system** for file sharing:
1. **AES Encryption**: encrypts a secret message or file.
2. **Steganography (LSB)**: hides the encrypted message inside an image.

The receiver can **extract and decrypt** the hidden message using the correct key.

---

## Features
- Encrypt and hide any text message inside an image.
- Extract and decrypt message securely.
- Visual and mathematical proof of image quality (PSNR).
- Lightweight and easy to run on any system or Google Colab.

---

## How to Run
1. Open `Secure_File_Sharing.ipynb` in Google Colab.
2. Upload your **cover image** (e.g., `cover.jpeg`).
3. Run all cells:
   - Sender-side: encryption + hiding
   - Receiver-side: extraction + decryption
4. Optional: Download `stego.png` or view PSNR and ciphertext outputs.

---

## Output / Screenshots
- Original vs. Stego Image (looks identical)
- Encrypted ciphertext output
- Decrypted message output
- PSNR image quality verification

*(Screenshots available in `/screenshots` folder)*

---

## Libraries Required

