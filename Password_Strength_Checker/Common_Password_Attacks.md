# Common Password Attacks

## 📌 Overview

Password attacks are techniques used by attackers to gain unauthorized access to accounts and systems by exploiting weak or compromised passwords.

Understanding these attacks helps security professionals design stronger authentication mechanisms and improve password security.

---

## 🎯 Why Understanding Password Attacks is Important

Knowledge of password attacks helps to:

* Strengthen password policies
* Improve account security
* Reduce the risk of compromise
* Build secure authentication systems

---

## 🔹 Brute Force Attack

A brute force attack systematically tries every possible combination until the correct password is found.

### Characteristics

* Time-consuming
* Effective against weak passwords
* Computationally expensive

### Example

```text id="j6jsk5"
123456
123457
123458
...
```

### Defense

* Strong passwords
* Account lockout mechanisms
* Multi-Factor Authentication (MFA)

---

## 🔹 Dictionary Attack

A dictionary attack uses a list of commonly used passwords and words.

Examples:

```text id="z45mzy"
password
admin
qwerty
letmein
password123
```

### Defense

* Avoid common passwords
* Use unique passwords
* Password managers

---

## 🔹 Credential Stuffing

Attackers use previously leaked usernames and passwords on multiple websites.

This attack succeeds because many users reuse passwords across different services.

### Defense

* Unique passwords
* MFA
* Monitoring for compromised credentials

---

## 🔹 Password Spraying

Attackers try a few common passwords against many accounts.

Examples:

```text id="9o6r5g"
Summer2025!
Welcome123
Password1
```

### Defense

* Strong password policies
* MFA
* Account monitoring

---

## 🔹 Rainbow Table Attack

Attackers use precomputed hash tables to crack password hashes.

### Defense

* Salting
* Strong hashing algorithms
* Multi-factor authentication

---

## 🌍 Real-World Impact

Password attacks can lead to:

* Account compromise
* Data breaches
* Identity theft
* Financial loss

---

## ⚠️ Security Best Practices

* Use long passwords
* Avoid password reuse
* Enable Multi-Factor Authentication
* Use password managers
* Monitor compromised credentials

---

## 🚀 Project Connection

### Project: Password Strength Checker

The Password Strength Checker attempted to identify weak and commonly used passwords.

This project provided practical exposure to:

* Password security
* Pattern detection
* Common password lists
* Secure coding principles

Understanding password attacks helped explain why:

* Length matters
* Complexity matters
* Common passwords should be avoided

---

## 📚 Key Takeaways

* Weak passwords are vulnerable to multiple attack techniques.
* Password reuse significantly increases risk.
* Strong passwords and MFA provide better protection.
* Understanding attacker techniques improves defensive security.

---

## 📖 References

* CompTIA Security+
* OWASP Authentication Cheat Sheet
* NIST Digital Identity Guidelines
* CIS Controls
