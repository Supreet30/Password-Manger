# 🔐 Password Manager (Python + Tkinter + JSON)

A simple and secure desktop password manager built with Python. This application allows you to save, generate, and store passwords for various websites using a clean GUI. All data is stored locally in a structured JSON file.

---

## 🚀 Features

- ✅ Add new credentials (website, email/username, password)
- 🔐 Generate strong random passwords
- 💾 Store data persistently in a local JSON file
- 📋 Copy generated password to clipboard
- 🔍 Search Password by Website
- ⚠️ Handles missing fields and errors gracefully

---

##🛠️ Tech Stack

- Python 3.10+
- Tkinter – for GUI
- JSON – for storing credentials
- random / string – for password generation
- pyperclip - copying password to clipboard

---

✅ Requirements

- Python 3.10 or later
- Tkinter (comes pre-installed with Python)
- pyperclip for clipboard support
  pip install pyperclip

---
## 📂 Example JSON Data Format

```json
{
  "example.com": {
    "email": "you@example.com",
    "password": "sT@9&gKL#1x"
  },
  "github.com": {
    "email": "dev@github.com",
    "password": "H#4lp!2SdF"
  }
}
