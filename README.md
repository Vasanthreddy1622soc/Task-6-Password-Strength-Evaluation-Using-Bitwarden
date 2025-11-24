# 🔐 Password Strength Evaluation Using Bitwarden

## 📌 Project Overview
This project is part of my SOC Analyst learning journey, where I evaluate the security of passwords with different complexity levels. Using the Bitwarden Password Strength Testing Tool, I analyzed crack times, weak patterns, and strong password formation techniques.

---

## 🎯 Objective
To understand what makes a password strong and how complexity, randomness, and length affect resistance against cyber attacks such as brute force and dictionary attacks.

---

## 🛠️ Tools Used
- Bitwarden Password Strength Testing Tool
  - Used to evaluate password strength scoring and estimated time to crack

---

## 🧪 Methodology
1. Created 8 passwords with various complexity levels.
2. Tested each password using Bitwarden’s strength evaluation tool.
3. Compared results based on:
   - Strength rating
   - Estimated cracking time
   - Tool feedback

---

## 📊 Results

| ID | Password | Strength | Est. Time to Crack | Observation |
|---|---|---|---|---|
| P1 | jagan | Very Weak | 3 Seconds | Dictionary-based name, no complexity |
| P2 | mohan123 | Very Weak | 1 Minute | Common name + predictable pattern |
| P3 | Sravanam | Very Weak | 45 Minutes | Only alphabets, weak structure |
| P4 | Sravan723 | Weak | 10 Hours | Slight complexity but still predictable |
| P5 | Sandeep@192 | Weak | 11 Hours | Name-based with slight symbol usage |
| P6 | Prem!8kumar@234 | Good | 39 Years | Good mixture of character sets |
| P7 | Saketh_Reddy!Vasu6 | Strong | Centuries | Long, random, and highly complex |
| P8 | Kuldeep$Reddy_234! | Strong | Centuries | Very strong passphrase-style password |

📌 **Trend Observed:**  
More randomness + more complexity + longer length = exponential crack time increase ✔

---

## 🧠 Key Learnings
- Weak passwords can be cracked in **seconds to minutes**
- Complex passwords extend crack time to **years or centuries**
- Name-based passwords remain weak even with symbols/numbers
- Passphrases provide the best balance of security and usability

---

## 🚨 Common Password Attack Techniques

| Attack | Description |
|---|---|
| Brute Force Attack | Tries every combination until correct |
| Dictionary Attack | Attempts using common passwords/names |
| Credential Stuffing | Uses leaked passwords from breaches |
| Phishing | Tricks users into revealing passwords |

Cracking success depends heavily on **password strength and uniqueness**.

---

## 🛡️ Password Security Best Practices
✔ Use 12–16+ characters  
✔ Mix uppercase, lowercase, numbers & symbols  
✔ Avoid personal information (names, DOB, phone numbers)  
✔ Use strong passphrases & randomness  
✔ Enable MFA where possible  
✔ Store passwords in a **Password Manager**  
✔ Never reuse passwords across websites  

Following **NIST SP 800-63B** standards for secure password creation.

---

## 🏁 Conclusion
This project highlights the importance of strong password policies in cybersecurity. Proper password hygiene significantly reduces the likelihood of successful brute force and dictionary attacks.

---



> “A strong password is the first line of defense in a digital world.”

