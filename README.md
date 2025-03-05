# PDF Generator with Python on Termux (LazyVim - Oppo A74 5G)

This project demonstrates **how to generate a PDF using Python** in **Termux** on an **Oppo A74 5G** smartphone. The script was developed and tested using **LazyVim** (Neovim configuration), and the PDF was successfully generated in the **Downloads folder** using the `fpdf` library.

---

## 📌 Project Overview
This repository contains a **Python script** that utilizes the **FPDF library** to create a simple **PDF file** in an Android environment using **Termux**. The purpose of this experiment was to **test whether PDFs can be created and stored using Python on a mobile device**.

### ✅ Key Takeaways
- Successfully **installed Python and FPDF** in Termux.
- Used **LazyVim (Neovim configuration)** for coding.
- The script **generated a PDF file in the `/storage/emulated/0/Download/` directory**.
- Tested on an **Oppo A74 5G** smartphone.

---

## 🔧 Setup & Installation

### **1️⃣ Install Termux**
If Termux is not installed on your phone, download it from **F-Droid** (recommended) or Google Play Store (older version).  
👉 **Download Termux:** [https://f-droid.org/packages/com.termux/](https://f-droid.org/packages/com.termux/)

### **2️⃣ Update & Install Required Packages**
Open **Termux** and run:
```bash
pkg update && pkg upgrade -y
pkg install python git -y
pip install fpdf
