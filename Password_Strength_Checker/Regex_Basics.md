# Regular Expressions (Regex)

## 📌 Overview

Regular Expressions (Regex) are patterns used to search, match, and manipulate text.

They provide a powerful way to validate user input and detect specific patterns within strings.

Regex is widely used in programming, cybersecurity, and data processing.

---

## 🎯 Why Regex is Important

Regex helps to:

* Validate user input
* Search for patterns
* Extract information from text
* Detect specific characters and sequences
* Improve data integrity

---

## 🔹 Common Character Classes

| Pattern | Meaning                         |
| ------- | ------------------------------- |
| `[A-Z]` | Uppercase letters               |
| `[a-z]` | Lowercase letters               |
| `[0-9]` | Digits                          |
| `\d`    | Any digit                       |
| `\w`    | Letters, digits, and underscore |
| `\s`    | Whitespace                      |
| `.`     | Any character                   |

---

## 🔹 Quantifiers

| Symbol  | Meaning               |
| ------- | --------------------- |
| `*`     | Zero or more          |
| `+`     | One or more           |
| `?`     | Optional              |
| `{n}`   | Exactly n times       |
| `{n,m}` | Between n and m times |

---

## 🔹 Pattern Matching Examples

### Detect Uppercase Letters

```python
re.search(r'[A-Z]', password)
```

---

### Detect Lowercase Letters

```python
re.search(r'[a-z]', password)
```

---

### Detect Numbers

```python
re.search(r'[0-9]', password)
```

---

### Detect Special Characters

```python
re.search(r'[!@#$%^&*(),.?":{}|<>]', password)
```

---

## 🌍 Real-World Applications

Regex is used in:

* Password validation
* Email validation
* Log analysis
* Data extraction
* Search engines
* Malware detection

---

## ⚠️ Security Considerations

Improper input validation can lead to:

* Invalid data
* Application errors
* Security vulnerabilities

Regex helps improve input validation and security.

---

## 🚀 Project Connection

### Project: Password Strength Checker

Regex was used to:

* Detect uppercase letters
* Detect lowercase letters
* Detect numbers
* Detect special characters

This project provided practical exposure to:

* Pattern matching
* Input validation
* Python's `re` module
* Secure coding practices

---

## 📚 Key Takeaways

* Regex is used for pattern matching.
* It simplifies input validation.
* Character classes define matching rules.
* Regex is widely used in cybersecurity and programming.

---

## 📖 References

* Python Documentation (`re` module)
* CompTIA Security+
* OWASP Input Validation Guidelines
