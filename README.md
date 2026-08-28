# NETWORKWALKS-B082-WK3-PM2-CYBERSECURITY-LAB-SETUP

## Week 3 Cybersecurity &amp; Ethical Hacking Internship

# 🔐 Week 3 Cybersecurity Lab – Password Cracking With John The Ripper and NetworkWalks Tools

## 🛡️ Cybersecurity & Ethical Hacking Internship

### 📌 Overview

This repository documents my practical activities for **Week 3 of my Cybersecurity & Ethical Hacking Internship**.

The focus of this week's practical exercises was **password cracking and password security assessment**. The laboratory activities provided practical experience in understanding how password-protected files can be assessed by extracting their password-related hash information and using controlled password-recovery techniques.

The exercises were performed strictly within the provided cybersecurity training laboratory environment for educational and ethical purposes.

---

## 🎯 Week 3 Objectives

The major objectives of this week's practical activities were to:

* 🔐 Understand the basic concept of password cracking.
* 🧩 Understand the difference between encryption and hashing.
* 📄 Work with password-protected PDF files in a controlled laboratory environment.
* 🔎 Extract the hash associated with a protected PDF.
* 🛠️ Use **John the Ripper (JTR)** to perform a password-recovery exercise.
* 🖥️ Understand the purpose of **Johnny**, the graphical interface for John the Ripper.
* 🌐 Use web-based password-security tools provided by Networkwalks.
* ⏱️ Observe how password complexity affects password-recovery time.
* 🛡️ Understand why strong passwords are important for protecting information.

The Week 3 manual describes John the Ripper as a password-cracking tool used by security professionals to test password strength and notes that it supports multiple operating systems and password/hash formats.

---

# 🧪 Project Module 1 – Password Cracking with John the Ripper

## 📖 Introduction

The first practical exercise focused on **John the Ripper (JTR)** and its graphical interface, **Johnny**.

John the Ripper is commonly used in security testing to assess password strength. Johnny provides a graphical interface that makes some of the functionality easier to use for beginners.

The laboratory exercise involved working with a password-protected PDF file and recovering its password within the authorized training environment.

## 🛠️ Tools Used

* 🐧 Kali Linux / Windows laboratory environment
* 🔐 John the Ripper
* 🖥️ Johnny GUI
* 📝 Text editor
* 📄 Password-protected PDF
* 🔎 PDF hash extraction tool

## 🔄 Practical Workflow

### 1️⃣ John the Ripper Installation

John the Ripper was installed/configured for the laboratory environment.

For Windows users, the lab manual provides the official Openwall download location and explains that the `john.exe` executable is located within the `run` directory.

### 2️⃣ 🔎 Obtaining the PDF Hash

The protected PDFs ("My Locked "PDF1, PDF2 & PDF3") were processed using a PDF hash extraction tool.

The resulting hash began with the `$pdf$` identifier. The complete hash was copied for use in the password-recovery exercise.

### 3️⃣ 📝 Creating the Hash File

The extracted hashes in each case was saved in a text file named:

```text
hash1.txt
hash2.txt
hash3.txt
```

This file was subsequently supplied to John/Johnny for the laboratory exercise.

### 4️⃣ 🔓 Password-Recovery Attempt

Johnny was configured to use the hash file and a new attack was started.

The tool attempted to recover the password based on the available password candidates and the complexity of the target password.

### 5️⃣ ✅ Verification

After the password was recovered, it was used to open the protected PDF and verify that the password-recovery process had been successful.

## 📸 Evidence

Screenshots from my practical exercise are included in the `screenshots` directory.

> 💡 **Note:** Screenshots should demonstrate my own laboratory work and results rather than reproducing screenshots from the training manual.

---

# 🌐 Project Module 2 – Password Cracking with Networkwalks Tools

## 📖 Introduction

The second practical exercise explored password recovery using two browser-based tools provided by Networkwalks:

1. 🧮 **Hash Calculator**
2. 🔓 **Password Cracker**

Unlike the first module, this exercise did not require installation of a local password-cracking application because the tools operate through a web browser.

## 🛠️ Tools Used

* 🐧 Kali Linux / Windows laptop
* 🌐 Web browser
* 🧮 Networkwalks Hash Calculator
* 🔓 Networkwalks Password Cracker
* 📄 Password-protected PDF files

## 🔄 Practical Workflow

### 1️⃣ 📥 Obtaining the Protected PDF

The encrypted PDF supplied for the laboratory exercise was downloaded from the Networkwalks project-task page.

### 2️⃣ 🔎 Extracting the Hash

The protected PDF was uploaded to the Networkwalks Hash Calculator.

The tool generated a hash value beginning with:

```text
$pdf$...
```

The complete hash was then copied for the next stage of the exercise.

### 3️⃣ 🔓 Password-Recovery Exercise

The extracted hash was entered into the Networkwalks Password Cracker.

The tool attempted different password candidates until a matching password was identified.

### 4️⃣ ✅ Password Verification

The recovered password was entered into the protected PDF to verify whether the file could be successfully opened.

---

# ⚖️ Comparison of the Two Approaches

| 🔍 Feature           | 🔐 John the Ripper                   | 🌐 Networkwalks Tools                        |
| -------------------- | ------------------------------------ | -------------------------------------------- |
| 💻 Approach          | Local password-auditing tool         | Browser-based tools                          |
| 🛠️ Main Tool        | John the Ripper / Johnny             | Hash Calculator + Password Cracker           |
| 📦 Installation      | Required for local use               | Not required                                 |
| 🔎 Hash Extraction   | External PDF hash extraction process | Networkwalks Hash Calculator                 |
| 🔓 Password Recovery | John/Johnny                          | Networkwalks Password Cracker                |
| 🖥️ Interface        | Command-line and graphical           | Web browser                                  |
| 🎓 Learning Focus    | Practical JTR usage                  | Understanding the password-recovery workflow |

The two exercises demonstrated the same general security concept through different approaches: obtaining password-related hash information and using a controlled recovery process to assess the password protecting a file.

---

# 🧠 Key Cybersecurity Concepts Learned

## 1️⃣ 🔐 Hashing

A hash is a transformed representation of data. In the laboratory exercise, the password-protected PDF produced a hash representation that could be supplied to a password-recovery tool.

The lab manual emphasizes that hashing is treated as a one-way process, unlike encryption, which uses a key to transform data and can be reversed with the appropriate key.

## 2️⃣ 🔓 Password Cracking

Password cracking, in the context of this laboratory, involved attempting to recover the password associated with protected data.

The exercise demonstrated why short or predictable passwords are more vulnerable to password-recovery attempts.

## 3️⃣ ⏱️ Password Complexity

The practical exercise showed that the time required for password recovery depends partly on password complexity and the resources available to the cracking process.

## 4️⃣ ⚖️ Ethical Use

Password-cracking techniques can be used legitimately for:

* 🛡️ Authorized security assessments
* 🔐 Password-strength testing
* 🔎 Digital-forensics training
* 🎓 Cybersecurity education
* 📂 Recovery of authorized protected files

These techniques should only be applied to systems, accounts, hashes, and files for which proper authorization has been obtained.

---

# 📚 Lessons Learned

Through this week's practical activities, I gained a better understanding of how password security can be assessed in a controlled cybersecurity environment.

Some of the key lessons I learned include:

1. 🔐 **Password security is an important part of information security.**
2. 📄 **Password-protected files can be subjected to password-recovery attempts when their associated password data can be analyzed.**
3. 🛠️ **John the Ripper provides a practical environment for learning password-security assessment.**
4. 🖥️ **Johnny provides a graphical interface that can make JTR easier for beginners to operate.**
5. 🔎 **Hash extraction is an important stage in some password-auditing workflows.**
6. 🧩 **Password complexity has a significant effect on the difficulty of password recovery.**
7. 🔄 **Different tools can achieve similar security-testing objectives using different interfaces and workflows.**
8. ⚖️ **Password-cracking techniques must always be applied within an authorized ethical-hacking environment.**

---

# ⚠️ Challenges Encountered

During the laboratory exercises, I encountered practical challenges involving **tool installation, configuration, and interaction with the password-recovery environment**.

Working through these challenges helped me improve my troubleshooting skills and understand that cybersecurity tools often require correct configuration before they can function properly.

### 🛠️ Technical Troubleshooting Experience

One notable challenge involved configuring **Johnny to locate the John the Ripper executable (`john.exe`)**.

This provided additional practical experience in:

* 📁 Understanding software directory structures
* 🔎 Locating executable files
* ⚙️ Checking application configuration
* 🧪 Testing whether an installation was complete
* 🛠️ Troubleshooting software execution problems

This troubleshooting experience was an important part of my Week 3 practical learning.

---

# 🏁 Conclusion

Week 3 provided practical exposure to **password-security assessment** through two different approaches.

The first module introduced **John the Ripper and Johnny**, providing experience with a locally installed password-auditing tool. The second module demonstrated a browser-based approach using the **Networkwalks Hash Calculator and Password Cracker**.

Together, the exercises improved my understanding of:

🔐 Password cracking
🧩 Hashing
📄 Password-protected files
🛠️ Security tools
⚙️ Tool configuration
🧪 Practical troubleshooting
⚖️ Ethical security testing

Most importantly, the laboratory demonstrated the importance of using **strong and appropriately managed passwords** to reduce the risk of unauthorized access.

---

# 🛡️ Ethical & Educational Disclaimer

All activities documented in this repository were performed as part of an **authorized cybersecurity and ethical-hacking training laboratory**.

The techniques demonstrated are intended for:

* 🎓 Educational purposes
* 🛡️ Authorized security testing
* 🔐 Password-security assessment
* 🧪 Controlled cybersecurity laboratory exercises

Unauthorized access to systems, accounts, files, or password data is not intended or encouraged.

---

## 📖 Training Reference

**Networkwalks – Cybersecurity & Ethical Hacking Project Tasks**

### Week 3

* 🔐 **Project Module 1 – Password Cracking with JTR**
* 🌐 **Project Module 2 – Password Cracking with Networkwalks Tools**
-------------------------------------------------------------------

* 👤 Author
      Ashikem Joshua Bengioushuye
  
        Cybersecurity Intern/Enthusiast B082
  
        LinkedIn: www.linkedin.com/in/ashiwelljosh
  _________________________________________________________________________
📌 Project Information

Program Name: Cybersecurity program at Networkwalks 
|Week: 03 | Repository: GitHub

