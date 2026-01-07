# Text Encryption Web Application

A simple web-based cybersecurity project that demonstrates classical encryption and decryption algorithms using HTML, CSS, and JavaScript.

This project allows users to enter text, select an encryption algorithm, provide a key, and either encrypt or decrypt the text accordingly.

---

## 🔐 Supported Algorithms

### 1. Caesar Cipher
- A substitution cipher that shifts characters by a fixed number.
- Encryption and decryption are performed using modular arithmetic.
- Key: Numeric shift value.

### 2. Vigenère Cipher
- A polyalphabetic substitution cipher that uses a keyword.
- Each character is shifted based on the corresponding character in the key.
- Key: Alphabetic keyword.

### 3. Rail Fence Cipher
- A transposition cipher that rearranges characters in a zig-zag pattern.
- Encryption writes characters diagonally across rails.
- Decryption reconstructs the zig-zag pattern to retrieve original text.
- Key: Number of rails (≥ 2).

---

## ⚙️ Features

- Encrypt and decrypt text using multiple algorithms
- Auto-switching key input type based on selected algorithm
- Case-sensitive encryption
- User-friendly web interface
- Input validation for keys

---

## 🛠️ Technologies Used

- HTML
- CSS
- JavaScript (Vanilla)

---

## ▶️ How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/devikamanoj1491/text_cipher.git
