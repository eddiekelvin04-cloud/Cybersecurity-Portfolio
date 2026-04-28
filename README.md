# Cryptographic Password Security & Entropy Lab
**Author:** Kelvin Okoronkwo Edward
**Technical Focus:** Cybersecurity Fundamentals | Data Integrity | Python Automation

## 1. Project Overview
This project is a technical demonstration of secure authentication principles. It focuses on two critical areas of cybersecurity:
* **Entropy Analysis:** Evaluating the strength of a password based on complexity requirements (length, casing, digits, and symbols).
* **Cryptographic Hashing:** Implementing the **SHA-256** algorithm to demonstrate how sensitive data is securely transformed into a one-way hash, ensuring that plain-text passwords are never stored in a database.

## 2. Problem Statement
Storing plain-text passwords is a primary vulnerability in modern systems. This lab demonstrates a defensive solution by using a "one-way" cryptographic function, ensuring that even if a database is breached, the original user passwords remain protected.

## 3. Technologies Used
* **Language:** Python 3.x
* **Libraries:** * `hashlib`: For implementing the SHA-256 hashing algorithm.
    * `re`: For pattern matching and complexity auditing via Regular Expressions (Regex).
* **Version Control:** Git/GitHub

## 4. Key Features
* **Real-time Feedback:** Provides users with specific suggestions to improve password entropy.
* **Hex-Digest Output:** Generates a 64-character hexadecimal string representing the secure hash of the input.
* **Security Best Practices:** Demonstrates the logic behind modern user-authentication systems.

## 5. How to Run
1. Ensure you have Python installed.
2. Clone the repository: 
   `git clone https://github.com/eddiekelvin04-cloud/Password-Security-Lab.git`
3. Run the script:
   `python password_lab.py`

## 6. Conclusion & Learning Outcomes
Through this project, I strengthened my understanding of:
* The mathematical difference between encryption (two-way) and hashing (one-way).
* The practical application of Regular Expressions in security auditing.
* The importance of salt and entropy in defending against brute-force attacks.
