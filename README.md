# Email Spoofing & Phishing Education using GoPhish

## 🚀 Overview
This repository is designed for **educational purposes only** to demonstrate how **email spoofing and phishing** work using [GoPhish](https://getgophish.com/), an open-source phishing simulation framework. 

⚠️ **Disclaimer:** This project is for **ethical and educational use only**. Any misuse of this knowledge for malicious purposes is strictly prohibited.

---

## 🎯 Objectives
- Educate users on **how email spoofing works**.
- Demonstrate **how attackers use phishing techniques**.
- Teach how to set up **GoPhish for testing**.
- Provide **defensive measures** to prevent phishing attacks.

---

## 🛠 Tools Used
| Tool | Description |
|------|------------|
| [GoPhish](https://getgophish.com/) | Open-source phishing simulation tool |
| Email Header Analysis | Used to detect spoofed emails |
| SPF/DKIM/DMARC | Security protocols to prevent spoofing |

---

## 📌 Installation Guide
### 1️⃣ Install GoPhish
```bash
# Download and extract GoPhish
wget https://getgophish.com/download/latest/gophish-vX.X.X-linux-64bit.zip
unzip gophish-vX.X.X-linux-64bit.zip
cd gophish
```

### 2️⃣ Run GoPhish
```bash
./gophish
```

🔹 Access GoPhish dashboard at `https://localhost:3333`

🔹 Default credentials: `admin` / `gophish`

---

## 🛡 How to Prevent Email Spoofing & Phishing
### ✅ Use SPF, DKIM, and DMARC
- SPF (Sender Policy Framework) ✅
- DKIM (DomainKeys Identified Mail) ✅
- DMARC (Domain-based Message Authentication) ✅

### 🔎 Check Email Headers
- Look for suspicious `Received:` fields.
- Verify DKIM signature.

### 📢 Security Awareness
- Never click suspicious links.
- Always verify sender email addresses.
- Report phishing emails to IT/security teams.

---

## 🎓 Educational Purpose Only
This project is created **to educate users on email security and phishing awareness**. Please use this knowledge **responsibly**.

📌 **Contributions & Feedback** are welcome!

---

### 📧 Contact & Support
For any issues or questions, feel free to open an **issue** in the repo

