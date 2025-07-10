# 🔐 Common Password Checker

This is a simple Python project that checks whether a given password is part of a common password list. It helps users avoid weak and easily guessable passwords.

## 🚀 Features

- Checks if a password exists in a list of common passwords
- Alerts the user if the password is risky
- Reads password list from a file (`common_passwords.txt`)
- Clean, easy-to-understand code and user-friendly output

## 📁 Files Included

- `password_checker.py` — the main Python script
- `common_passwords.txt` — text file containing a list of weak/common passwords (you must create this)

## 🛠 How It Works

1. Loads common passwords from `common_passwords.txt`
2. Accepts user input for a password
3. Compares input against the list
4. Displays:
   - ⚠️ Warning if password is common
   - ✅ Message if password is safe from that list
