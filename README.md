# 🔐 Password Strength Analyzer

A lightweight Python tool that checks the strength of a password based on its complexity.  
Useful for understanding password security and encouraging stronger password habits.

---

## 🌟 Features
- Checks password for:
  - Minimum length (8+)
  - Uppercase & lowercase letters
  - Digits
  - Special symbols
- Rates passwords as **Weak**, **Moderate**, or **Strong**
- 100% Python — no external libraries

---

## ⚙️ Installation & Run (Step-by-Step)

### 🪜 Step 1: Clone the repository
```bash
git clone https://github.com/sai7763/Password-Strength-Analyzer.git
cd Password-Strength-Analyzer
```

---

### 🪜 Step 2: (Optional) Create a virtual environment
**Windows:**
```bash
python -m venv venv
venv\Scripts\activate
```
**macOS/Linux:**
```bash
python3 -m venv venv
source venv/bin/activate
```

---

### 🪜 Step 3: Install dependencies
There are no external dependencies.  
If a `requirements.txt` file exists:
```bash
pip install -r requirements.txt
```

---

### 🪜 Step 4: Run the script
```bash
python password_strength.py
```

Then enter a password when prompted:
```
Enter password: MyP@ssw0rd123
Password strength: Strong 💪
```

---

## 🧾 Example Output
```
Enter password: hello123
Password strength: Weak ❌

Enter password: MyP@ssword
Password strength: Moderate ⚠️

Enter password: MyP@ssw0rd123
Password strength: Strong 💪
```

---

## 💡 Notes
- This is an **educational project**, not a real password manager.
- Do not enter sensitive or personal passwords.
- Combine this script with breached-password checks (like `HaveIBeenPwned` API) for advanced validation.

---

## 🧰 Requirements
- Python 3.8 or higher

---

## 👨‍💻 Author
**Muvvala Sai (sai7763)**  
GitHub: [https://github.com/sai7763](https://github.com/sai7763)

---

## ⚖️ License
This project is licensed under the **MIT License**.  
You may use, modify, or share it freely with proper credit.
