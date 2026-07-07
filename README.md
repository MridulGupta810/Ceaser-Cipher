#  Caesar Cipher - Python

A simple yet elegant implementation of the **Caesar Cipher** in Python. This project allows users to **encrypt** and **decrypt** text directly from the terminal while preserving spaces, numbers, and special characters.

Perfect for beginners learning Python, loops, functions, string manipulation, and basic cryptography.

---

##  About the Project

The Caesar Cipher is one of the oldest and most famous encryption techniques in history. It works by shifting every letter in a message by a fixed number of positions in the alphabet.

For example, using a shift of **3**:

```text
Original : hello
Encrypted: khoor
```

To decrypt the message, the same shift is simply applied in the opposite direction.

---

##  Features

* 🔒 Encrypt messages
* 🔓 Decrypt messages
* 🔄 Supports any shift value
* 🔢 Automatically wraps around the alphabet using modulo (`%`)
* 📝 Preserves spaces, punctuation, and numbers
* 🔁 Run multiple encryptions/decryptions without restarting the program
* 🧹 Clean and beginner-friendly Python code

---

##  Technologies Used

* Python 3

No external libraries are required.

---

##  Project Structure

```text
Caesar-Cipher/
│
├── main.py
├── art.py
└── README.md
```

---

##  Getting Started

### Clone the repository

```bash
git clone https://github.com/MridulGupta810/caesar-cipher.git
```

### Navigate to the project

```bash
cd caesar-cipher
```

### Run the program

```bash
python main.py
```

---

## 💻 Example

```text
Type 'encode' to encrypt, type 'decode' to decrypt:
encode

Type your message:
hello world!

Type the shift number:
5

Here is the encoded result:
mjqqt btwqi!
```

Decrypting:

```text
Type 'encode' to encrypt, type 'decode' to decrypt:
decode

Type your message:
mjqqt btwqi!

Type the shift number:
5

Here is the decoded result:
hello world!
```

---

##  How It Works

1. The user selects **encode** or **decode**.
2. A message and shift value are entered.
3. Each alphabetic character is shifted by the specified amount.
4. Characters outside the alphabet (spaces, punctuation, numbers, etc.) remain unchanged.
5. Modulo arithmetic (`% 26`) ensures letters wrap around the alphabet correctly.
6. The program continues running until the user chooses to exit.

---

## What I Learned

Building this project helped strengthen my understanding of:

* Python functions
* `for` loops
* Conditional statements
* Lists and indexing
* String manipulation
* Modulo arithmetic
* User input handling
* Writing reusable and readable code

---

##  Future Improvements

* Add support for uppercase letters.
* Validate user input.
* Add file encryption and decryption.
* Build a graphical interface using Tkinter.
* Store encryption history.
* Support custom alphabets and languages.

---

##  Disclaimer

The Caesar Cipher is a historical educational encryption method and **should not be used for securing sensitive information**. Modern encryption algorithms such as AES or RSA are significantly more secure.

---

##  Contributing

Contributions, ideas, and improvements are always welcome.

If you'd like to improve this project:

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Submit a Pull Request.



---

##  Author

**Mridul Gupta**



> *"Every great engineer starts by building small things exceptionally well."*
