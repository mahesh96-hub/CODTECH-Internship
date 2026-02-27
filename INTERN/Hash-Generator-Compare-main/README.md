 # 🔒 Hash Generator & File Comparator (Dark Mode + GUI + CLI)

## 🧭 Overview
The **Hash Generator & File Comparator** is a Python application and standalone tool that allows users to:
- Generate **cryptographic hashes** (MD5, SHA1, SHA256, etc.) for **text** or **files**
- **Compare two files** to verify integrity or detect duplicates  
- Operate via **Graphical Interface (Dark Mode)** or **Console**
- Export as a **standalone `.exe`** — no Python required!

This project is designed for **students, developers, and cybersecurity enthusiasts** who want to understand and use hashing for data verification and integrity checking.

---

## ⚙️ Features

✅ **Modes of Operation**
1. **Text Hashing:** Enter a string and get its hash instantly.  
2. **File Hashing:** Select a file and compute its hash.  
3. **File Comparison:** Compare two files to check for equality (based on hashes).  

✅ **Supported Algorithms**
- MD5  
- SHA1  
- SHA224  
- SHA256  
- SHA384  
- SHA512  

✅ **Highlights**
- 🧠 GUI built with **ttkbootstrap** (Dark Mode)
- 💾 Standalone `.exe` version (no Python needed)
- 📋 Copy hash directly to clipboard
- 📜 Logging of all operations in `hash_generator.log`
- ✅ Color-coded comparison results (Green = Identical, Red = Different)
- 🧱 Cross-platform compatible (Windows, Linux, macOS)
- 🧩 Optional lightweight console versions included

---

## 🏗️ Project Structure
```
Hash-Generator-Compare/
│
├── advanced_hash_generator_dark.py # Main Dark Mode GUI app
├── advanced_hash_generator_dark.exe # Compiled standalone executable
├── advanced_hash_generator.py # Light version (Tkinter GUI)
├── hash_generator.py # Console text/file hashing
├── file_compare.py # Console file comparison
├── requirements.txt # Project dependencies
├── README.md # Project documentation
├── hash.ico # Optional app icon
└── hash_generator.log # Log file (auto-generated)

```
---

## 🧩 Installation (Python Version)

### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/<your-username>/Hash-Generator-Compare.git
cd Hash-Generator-Compare
```

## Create a Virtual Environment (Recommended)
```bash
python -m venv venv
venv\Scripts\activate     # On Windows
source venv/bin/activate  # On macOS/Linux
```
## Install Dependencies
```
pip install -r requirements.txt
```
## Usage
### 🖥️ Run GUI (Dark Mode)
```
python advanced_hash_generator_dark.py
```
### 💻 Run Console Version

### Hash a String or File:
```
python hash_generator.py
```

### Compare Two Files:
```
python file_compare.py
```


💡 How It Works
🔹 Hashing Logic

Uses Python’s built-in hashlib to generate a unique hex digest for text or files.

Reads files in chunks (4 KB) to support large files efficiently.

🔹 File Comparison

Computes both file hashes and compares them.

Displays a ✅ "Files Identical" message if hashes match, or ❌ otherwise.

🧰 Technologies Used
Component	Description
Python 3.x	Core programming language
hashlib	Built-in hash generation
ttkbootstrap	Modern themed UI framework
pyperclip	Clipboard operations
tkinter	GUI base (standard library)
PyInstaller	Converts Python script to executable
Pillow (PIL)	Theme asset dependency for ttkbootstrap
🧪 Example Screenshots
Dark Mode GUI	File Comparison

	

(Replace placeholders with your actual screenshots once captured)

🧩 Future Enhancements

🚀 Planned Features:

Add drag-and-drop file support

Export hash reports as .txt or .csv

Add checksum validation for downloaded files

Implement multi-file comparison

Add progress bar for large file hashing

🧑‍💻 Author

Developed by: K Mahesh Reddy

🌐 GitHub Profile

### License

This project is licensed under the MIT License.
You’re free to use, modify, and distribute this software with proper attribution.

**⭐ If you like this project, please star ⭐ the repository!**


Your feedback helps make open-source projects better 💙
