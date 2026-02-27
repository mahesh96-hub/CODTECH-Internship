# CODTECH-Internship

# Cybersecurity Tools Suite (4-in-1 Security Toolkit)

A collection of practical cybersecurity tools developed as part of an internship project.
This repository combines four essential security utilities covering encryption, hashing, password security simulation, and web vulnerability scanning.

---

## Project Overview

This toolkit demonstrates core cybersecurity concepts:

* Data confidentiality (Encryption)
* Data integrity (Hashing)
* Password attack awareness (Simulation)
* Web application security (SQL Injection detection)

Each tool is implemented in Python with beginner-friendly interfaces and an educational focus.

---

## Included Tools

### 1. AES-256 File Encryption Tool

Secure files using AES-256 encryption with password protection.

Key features:

* AES-256-GCM encryption
* Password-based key derivation (PBKDF2)
* Multi-file encryption and decryption
* GUI interface (Tkinter)
* Cross-platform support

The tool derives a secure key from the user password and encrypts files using modern cryptographic standards. 

Run:

```bash
python AES-Encryption-Tool.py
```

---

### 2. Hash Generator and File Comparator

Generate cryptographic hashes and verify file integrity.

Capabilities:

* Hash text or files
* Compare two files via hash
* Algorithms: MD5, SHA1, SHA256, SHA384, SHA512
* GUI and CLI versions
* Dark-mode advanced interface

This tool computes hashes and compares them to detect file tampering or duplication. 

Run (GUI):

```bash
python advanced_hash_generator_dark.py
```

Run (CLI):

```bash
python hash_gen_file_comp.py
```

---

### 3. Password Security Simulation Tool

(Brute-Force Attack Demonstration – Educational)

A simulated password-guessing engine designed to demonstrate how brute-force attacks work and why strong passwords are essential.

Educational features:

* Password attempt simulation
* Dictionary and random attack strategies
* Attack timing simulation
* Security protocol workflow
* Terminal visualization

The engine repeatedly generates password attempts to illustrate brute-force attack behavior in controlled educational environments. 

Run:

```bash
python main.py
```

Ethical notice:
This tool is strictly for cybersecurity education and password-strength awareness. Do not use against real accounts or systems without authorization.

---

### 4. SQL Injection Vulnerability Scanner

A web security assessment tool to detect SQL injection vulnerabilities in web forms.

Core functions:

* Automatic form extraction
* SQL payload injection testing
* Server response analysis
* Error-based vulnerability detection
* Command-line interface

The scanner parses web pages, injects test inputs, and identifies SQL errors indicating vulnerabilities. 

Run:

```bash
python SQL_Injection_Scanner.py
```

Scan only authorized websites or local test environments.

---

## Repository Structure

```
Cybersecurity-Tools-Suite/
│
├── AES-Encryption-Tool/
│   ├── AES-Encryption-Tool.py
│   └── README.md
│
├── Hash-Generator-Comparator/
│   ├── advanced_hash_generator_dark.py
│   ├── hash_gen_file_comp.py
│   └── README.md
│
├── Password-Security-Simulation/
│   ├── main.py
│   ├── core.py
│   └── modules/
│
├── SQL-Injection-Scanner/
│   ├── SQL_Injection_Scanner.py
│   └── README.md
│
└── LICENSE
```

---

## Requirements

Python 3.8 or higher

Install dependencies:

```bash
pip install cryptography tkinter requests beautifulsoup4 colorama aiohttp pycryptodome
```

---

## Learning Outcomes

This project demonstrates:

* Encryption and key derivation
* Cryptographic hashing
* Password attack mechanics
* Web vulnerability detection
* Secure coding practices
* Python security tool development

---

## Author

K Mahesh Reddy
Cybersecurity and Ethical Hacking Intern

GitHub: https://github.com/mahesh96-hub
LinkedIn: https://www.linkedin.com/in/maheshreddy27/

---

## Ethical and Legal Disclaimer

These tools are created for:

* cybersecurity education
* ethical hacking labs
* authorized security testing

Do not use on systems or websites without explicit permission.
Unauthorized security testing may be illegal.

---

## License

MIT License — free to use, modify, and distribute with attribution.
