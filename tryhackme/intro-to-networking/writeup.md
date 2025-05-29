# 🔓 TryHackMe: Offensive Security (Beginner Notes)

## 🧠 What I Learned

This room introduced me to the basics of **offensive hacking** — the practice of simulating attacks to test and improve cybersecurity.

### Key Takeaways:
- Offensive hacking is about **thinking like an attacker**.
- It includes stages like **reconnaissance**, **exploitation**, and **post-exploitation**.
- These skills are used in **penetration testing** and **red teaming**.

---

## 🧪 Hands-On Practice

The room provided a **fake banking website** to simulate a real-world hacking environment.

### ✅ Step 1: Reconnaissance & Analysis
- Explored login pages and input fields.
- Checked the **HTML source code** for hidden hints or comments.

### ✅ Step 2: Used Gobuster
- Ran Gobuster to enumerate hidden directories:
  ```bash
  gobuster dir -u http://<target-ip> -w /usr/share/wordlists/dirb/common.txt
![Screenshot of fake bank](![Screenshot (18)](https://github.com/user-attachments/assets/033a21ff-b797-4c07-a9b0-c896a445be61)
)
