# 🔐 Hybrid Text Encryption (Caesar + Vigenère Cipher)

This is a simple C++ project that implements **hybrid encryption** using a combination of two classical ciphers:
- **Caesar Cipher**
- **Vigenère Cipher**

It demonstrates basic encryption techniques useful for understanding foundational cryptography and string manipulation in C++.

---

## 📁 File
- `hybrid_little_complex.cpp`: The main C++ file containing encryption logic.

---

## 💡 How It Works

1. **User Input**:
   - A plain text string to encrypt
   - A shift value (for Caesar cipher)
   - A keyword (for Vigenère cipher)

2. **Caesar Cipher**:
   - Each letter is shifted by the user-defined value.
   - Non-alphabetic characters are preserved.

3. **Vigenère Cipher**:
   - The result from Caesar encryption is further encrypted using a keyword.
   - The keyword cycles through the text to determine each letter's shift.

4. **Final Output**:
   - Caesar encrypted text
   - Final encrypted text after applying Vigenère

---

## 🖥️ Sample Output

```
Enter the text to encrypt: hello
Enter the shift value for Caesar Cipher: 3
Enter the keyword for Vigenere Cipher: key

Caesar Encrypted Text: khoor
Final Encrypted Text: urovv
```

---

## 🧠 Concepts Covered

- Structures (`struct`)
- String manipulation
- Functions
- Classic encryption techniques
- ASCII operations and modulo logic

---

## ✅ How to Run

1. Open the file in a C++ environment (e.g., VS Code or CodeBlocks).
2. Compile using:
   ```bash
   g++ hybrid_little_complex.cpp -o hybrid
   ```
3. Run:
   ```bash
   ./hybrid
   ```

---

## 📌 Note

- Input is taken without spaces.
- Works only on alphabetic characters for encryption.
