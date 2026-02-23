# Password Cracking Toolkit (Simulation Only)

## Internship Project – Cybersecurity / Ethical Hacking

This toolkit is developed as part of an **internship project** to understand and analyze
password security using **ethical and controlled simulations**.  
It demonstrates how weak passwords can be identified and evaluated without attacking
any real systems or user accounts.

---

## 📌 Project Objective

The main objective of this toolkit is to:
- Understand common password attack techniques
- Analyze password strength and vulnerabilities
- Learn secure password handling and policy enforcement
- Gain hands-on experience in ethical security testing

---

## 🛠 Toolkit Modules

### 1️⃣ Dictionary Generator
- Generates password wordlists using common patterns
- Demonstrates how attackers guess weak passwords
- Output: Custom wordlist file

**File:**  
`dictionary/dictionary_generator.py`

---

### 2️⃣ Brute Force Simulator
- Simulates brute-force password cracking attempts
- Calculates total combinations and estimated cracking time
- Highlights the impact of password length and complexity

**File:**  
`brute_force/brute_force_simulator.py`

---

### 3️⃣ Password Strength Analyzer
- Analyzes passwords based on:
  - Length
  - Uppercase & lowercase characters
  - Numbers
  - Special characters
- Identifies weak passwords and provides feedback

**File:**  
`analyzer/password_strength_analyzer.py`

---

### 4️⃣ Hash Demonstration (Educational)
- Demonstrates how password hashes are stored
- Includes sample Linux shadow hash format
- No real password cracking performed

**File:**  
`hashes/sample_hashes.txt`

---

### 5️⃣ Audit Report
- Summarizes findings from the simulations
- Identifies weak passwords and risks
- Provides security recommendations

**File:**  
`reports/audit_report.txt`

---
