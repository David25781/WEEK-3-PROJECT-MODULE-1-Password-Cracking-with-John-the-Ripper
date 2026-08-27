
# WEEK 3 | PROJECT MODULE 1 — Password Cracking with John the Ripper

## 📌 Project Overview

As part of my **Cybersecurity Internship at Networkwalks**, Week 3 focused on understanding password security and password recovery techniques using **John the Ripper (JTR)** and **Johnny**, its graphical user interface.

The objective of this practical lab was to recover the password of a protected PDF file by extracting its password hash and performing a controlled password-cracking attack in a **legal and authorized laboratory environment**.

This project provided hands-on experience with password hashes, password-cracking methodologies, wordlist-based attacks, and the importance of strong password policies.

---

## 🎯 Objectives

* Understand how password-protected files store password hashes.
* Extract a password hash from an encrypted PDF file.
* Use **John the Ripper** to perform password recovery.
* Use **Johnny GUI** to interact with John the Ripper more easily.
* Understand the relationship between password complexity and cracking time.
* Demonstrate why strong passwords are essential for security.

---

## 🛠️ Tools & Technologies

| Tool                      | Purpose                                             |
| ------------------------- | --------------------------------------------------- |
| **John the Ripper (JTR)** | Password hash cracking and password recovery        |
| **Johnny**                | Graphical interface for John the Ripper             |
| **Kali Linux / Windows**  | Testing environment                                 |
| **PDF Hash Extractor**    | Extracting the password hash from the protected PDF |
| **Notepad**               | Saving and preparing the extracted hash             |

---

## 🔬 Methodology

### 1. Installing John the Ripper

John the Ripper was installed and configured for the Windows environment.

For Kali Linux users, John the Ripper is available directly as part of the default security-testing toolkit.

### 2. Installing and Configuring Johnny

Johnny was installed as the graphical interface for John the Ripper.

The application was configured to use the `john.exe` executable located inside the John the Ripper installation directory.

### 3. Extracting the PDF Hash

A password-protected PDF was used as the target file in the authorized lab environment.

The PDF was processed using a PDF hash extraction utility to obtain the password hash required by John the Ripper.

The extracted hash was saved into a text file:

```text
hash1.txt
```

The hash was verified to ensure that unnecessary characters were removed and that it was stored in the correct format for John the Ripper.

### 4. Loading the Hash into Johnny

The `hash1.txt` file containing the extracted hash was imported into Johnny using the **Open Password File** option.

After loading the hash, a new password-cracking attack was started.

### 5. Password Recovery

John the Ripper processed the hash and attempted to recover the original password.

The time required for password recovery depends on several factors, including:

* Password complexity
* Password length
* Available wordlists
* Attack methodology
* CPU performance
* Number of possible password combinations

Once the password was successfully recovered, it was used to unlock the protected PDF.

---

## 🧠 Key Cybersecurity Concepts Learned

### Password Hashing

A password hash is a one-way representation of a password. Instead of storing the original password directly, systems can store its hash.

However, weak passwords can potentially be recovered through password-cracking techniques.

### Password Cracking

Password cracking involves attempting to discover the original password from a password hash.

Tools such as John the Ripper can automate this process using different attack techniques.

### Password Complexity

The lab demonstrated the importance of password complexity. Short and predictable passwords are significantly easier to recover than long, random passwords.

### Security Awareness

The exercise highlighted why organizations should implement:

* Strong password policies
* Long and complex passwords
* Multi-factor authentication (MFA)
* Secure password hashing algorithms
* Account lockout and rate-limiting mechanisms
* Regular security assessments

---

## 💻 Example Workflow

```text
Protected PDF
     │
     ▼
Extract PDF Hash
     │
     ▼
Save Hash → hash1.txt
     │
     ▼
Load Hash into Johnny
     │
     ▼
Start Password Attack
     │
     ▼
Password Recovered
     │
     ▼
Unlock Protected PDF
```

---

## 📚 Skills Developed

Through this project, I developed practical knowledge in:

* Password security
* Hash analysis
* Password recovery
* John the Ripper
* Johnny GUI
* PDF password protection
* Cybersecurity laboratory methodologies
* Security assessment techniques
* Understanding password vulnerabilities

---

## ⚠️ Ethical & Legal Considerations

This activity was performed strictly for **educational and cybersecurity training purposes** within an authorized laboratory environment.

Password-cracking tools should only be used against systems, files, or hashes for which explicit authorization has been obtained.

Unauthorized password cracking or access to protected information may violate organizational policies and applicable laws.

---

## ✅ Project Outcome

Successfully completed a practical password-security exercise using **John the Ripper and Johnny**, gaining hands-on experience in extracting password hashes, performing controlled password-recovery attacks, and understanding the security implications of weak passwords.

This project strengthened my practical understanding of **offensive security techniques and defensive password-security practices** as part of my Cybersecurity Internship at **Networkwalks**.

---

### 🏷️ Topics

`Cybersecurity` `Ethical Hacking` `Password Cracking` `John the Ripper` `JTR` `Johnny` `Password Security` `Hashing` `Penetration Testing` `Security Testing` `Networkwalks` `Cybersecurity Internship`


<img width="467" height="458" alt="Screenshot 2026-08-26 213613" src="https://github.com/user-attachments/assets/ea002437-6ecb-4acf-8ef5-3526791033b1" />

<img width="457" height="451" alt="Screenshot 2026-08-26 213710" src="https://github.com/user-attachments/assets/3359e930-cc38-40a1-939c-2852fa0d1acb" />

<img width="419" height="454" alt="Screenshot 2026-08-26 213753" src="https://github.com/user-attachments/assets/39a60c44-ec61-49e6-9b38-ca67b3ebebfe" />

<img width="466" height="516" alt="Screenshot 2026-08-26 213850" src="https://github.com/user-attachments/assets/872f0cab-6886-4fcf-852e-3f3bcbb7819e" />

<img width="432" height="350" alt="Screenshot 2026-08-26 214010" src="https://github.com/user-attachments/assets/513da1e3-7053-41d0-a219-79003d408a49" />

<img width="368" height="426" alt="Screenshot 2026-08-26 213540" src="https://github.com/user-attachments/assets/550baaa0-a09e-420f-b55b-4e8ec11126e6" />








