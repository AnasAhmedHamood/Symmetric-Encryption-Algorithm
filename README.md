# 🔐 Unique Encryption Algorithm Based on Feistel Cipher

This project is a custom-designed symmetric encryption algorithm built upon the Feistel cipher structure. It combines a strong key generation process using SHA-256 and PBKDF2 with multiple layers of substitution and permutation to ensure high security and avalanche effect. A Flask web interface is provided for practical interaction with the encryption system.

---

## 📌 Project Overview

This implementation:
- Uses a 128-bit block size split into two 64-bit halves.
- Performs 16 Feistel rounds to enhance security.
- Applies confusion and diffusion via:
  - XOR with subkey
  - Bit rotation
  - Byte reversal (stack-based)
  - Bit inversion
  - Modular hexadecimal transformation

Key generation is dynamic and supports both user-provided and randomly generated keys. It incorporates salting, hashing (SHA-256), and round-number-based derivation to ensure cryptographic strength and randomness.

---

## 🚀 Features

- **Feistel cipher-based encryption/decryption**
- **Dynamic round-key generation** with SHA-256
- **Avalanche effect** visual demonstration
- **Web interface** using Flask for user interaction
- **Modular and readable Python code**

---

## 🛠 Prerequisites

Ensure you have:
- Python 3.7 or higher
- pip installed

---

## 📦 Installation

1. Clone this repository or download the ZIP.
2. Open your terminal and navigate to the project directory.
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
