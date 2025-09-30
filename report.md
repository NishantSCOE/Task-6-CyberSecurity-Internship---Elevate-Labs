# Task 6: Password Strength Creation and Evaluation

### **Objective**
The objective of this task is to understand the principles of creating strong passwords and to evaluate password strength using online security tools.

### **Tools Used**
* **Online Password Strength Checker:** passwordmeter.com 

### **Password Evaluation Results**
In this section, I created and tested a series of passwords, progressively increasing their complexity to observe the direct impact on their strength scores.

---

**1. Password: `nishant`**
* **Screenshot of Result:**
    * [Insert your screenshot for 'nishant' here - Screenshot (203).png]
* **Score:** 8% (Very Weak)
* **Analysis:** The tool rated this password as "Very Weak." It is short, consists only of lowercase letters, and is based on personal information. It fails to meet minimum requirements for numbers, symbols, and uppercase letters, making it extremely vulnerable.

---

**2. Password: `nishant123`**
* **Screenshot of Result:**
    * [Insert your screenshot for 'nishant123' here - Screenshot (205).png]
* **Score:** 42% (Good)
* **Analysis:** By adding a common number sequence, the score improved significantly to "Good." The password now includes lowercase letters and numbers, but it still lacks uppercase letters and symbols. The pattern is also highly predictable.

---

**3. Password: `nishant@123`**
* **Screenshot of Result:**
    * [Insert your screenshot for 'nishant@123' here - Screenshot (206).png]
* **Score:** 64% (Strong)
* **Analysis:** The introduction of a single symbol (`@`) increased the password's complexity and pushed the score into the "Strong" category. It now contains three of the four recommended character types.

---

**4. Password: `Nishant@1234`**
* **Screenshot of Result:**
    * [Insert your screenshot for 'Nishant@1234' here - Screenshot (207).png]
* **Score:** 100% (Very Strong)
* **Analysis:** By adding an uppercase letter at the beginning and increasing the length, this password achieved a perfect score of 100%. [cite_start]It meets all the minimum requirements: length, uppercase, lowercase, numbers, and symbols[cite: 60].

---

**5. Password: `Nishant$-1234@4321!`**
* **Screenshot of Result:**
    * [Insert your screenshot for 'Nishant$-1234@4321!' here - Screenshot (208).png]
* **Score:** 100% (Very Strong)
* **Analysis:** While the previous password also scored 100%, this one is significantly more secure in practice. Its greater length (18 characters) and use of multiple, varied symbols make it far more resistant to brute-force attacks than the shorter version.

### **Common Password Attacks Researched**
* **Brute-Force Attack:** An automated method of attack that tries every possible combination of letters, numbers, and symbols until the correct password is found. A password's length and complexity are the primary defenses against this.
* **Dictionary Attack:** A method where an attacker uses a pre-compiled list of common words, phrases, and known leaked passwords to try and guess the correct one. This is why using personal names or common words is insecure.

### **Summary: How Complexity Affects Security**
This evaluation clearly demonstrates how each element of complexity contributes to password security.
1.  **Length:** Increasing the character count provides the biggest boost to the score and security.
2.  **Character Types:** Each new type of character added (numbers, symbols, uppercase letters) exponentially increases the number of possible combinations, making a brute-force attack much more difficult.
3.  **Unpredictability:** Moving away from a simple name and number pattern to include symbols and mixed cases makes the password less vulnerable to dictionary attacks and guessing.

### **Best Practices & Key Learnings**
From this evaluation, the key takeaways for creating strong passwords are:
* **Length is King:** A longer password is almost always better than a short, complex one. Aim for 16 characters or more.
* **Use All Character Types:** Combine uppercase, lowercase, numbers, and symbols.
* **Avoid Personal Information:** Never use your name, birthdate, or other easily guessable details.
* **Use a Unique Password for Every Account:** This prevents a breach on one site from compromising your other accounts.
* **Enable Multi-Factor Authentication (MFA):** As a crucial second layer of security, MFA protects your account even if your password is stolen.
* **Use a Password Manager:** These tools help generate and store extremely strong, unique passwords for all your accounts securely.