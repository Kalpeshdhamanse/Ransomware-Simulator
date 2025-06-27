# 🔐 Ransomware-Simulator

A simple Python-based script that demonstrates **how ransomware works** by encrypting and decrypting files using **Fernet encryption**. This educational tool helps cybersecurity learners understand ransomware behavior in a safe, local environment.

---

## 📌 Problem Statement

Ransomware is a growing cybersecurity threat that encrypts user files and demands a ransom for recovery. It can lead to massive data loss, financial damage, and downtime. Understanding how ransomware functions helps in building strong defense mechanisms.

---

## 🎯 Objective

Build a Python application to:
- Simulate ransomware behavior using file encryption
- Encrypt all files in a folder with a secret key
- Decrypt them only with the correct key
- Demonstrate the importance of data security and controlled access

---

## 🧰 Technologies Used

- **Python 3**
- **Cryptography (Fernet)** for symmetric encryption
- Linux Terminal (Kali or any Debian-based distro)

---

## ⚙️ Features

- Encrypts all files in a selected folder (`files_to_encrypt`)
- Decrypts encrypted files with the saved key
- Simulates ransomware attack behavior
- Safe for educational use only
- CLI-based simple interface

---

## 🛠️ Requirements

- Python 3.x
- Cryptography module (`pip install cryptography`)
- Sample `.txt` files in a test folder
- Kali Linux (or any local Linux system)

---

## 🚀 How to Run

### 📦 1. Download or Clone the Repository
```bash
git clone https://github.com/your-username/ransomware-simulator.git
cd ransomware-simulator
```
🗃️ 2. Set Up Sample Files
```bash
mkdir files_to_encrypt
echo "Confidential Data" > files_to_encrypt/secret1.txt
echo "Test File" > files_to_encrypt/secret2.txt

```
 🔐 3. Install Required Module
 ```
pip3 install cryptography
```
▶️ 4. Run the Script
```bash
python3 ransomware_sim.py

```
💻 5. Choose Operation
When prompted, enter:

E → to encrypt files

D → to decrypt files

### 💻 GUI in Action
 | ![](Screenshort/Screenshot_2025-06-26_10_27_14.png) | ![](Screenshort/Screenshot_2025-06-26_10_27_33.png) |  ![](Screenshort/Screenshot_2025-06-26_11_47_29.png) |
 | ![](Screenshort/Screenshot_2025-06-26_11_11_08.png) | ![](Screenshort/Screenshot_2025-06-26_11_43_09.png) |



 ✅ Built by **Kalpesh Dhamanse** —  [GitHub](https://github.com/Kalpeshdhamanse/SQL-Injection.git)
