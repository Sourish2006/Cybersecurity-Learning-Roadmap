# XOR Encryption

## 📌 Overview

XOR (Exclusive OR) Encryption is a simple symmetric encryption technique that uses the XOR operation to encrypt and decrypt data.

The same key is used for both encryption and decryption.

---

## 🔹 XOR Operation

The XOR operator compares two bits and returns:

* `1` if the bits are different
* `0` if the bits are the same

### XOR Truth Table

| A | B | A XOR B |
| - | - | ------- |
| 0 | 0 | 0       |
| 0 | 1 | 1       |
| 1 | 0 | 1       |
| 1 | 1 | 0       |

---

## 🔹 Why XOR Works

XOR encryption is reversible.

```text id="6h0tt8"
Plaintext XOR Key = Ciphertext

Ciphertext XOR Key = Plaintext
```

Applying the same key twice restores the original data.

---

## 🔹 Encryption Process

```text id="7n2b91"
Plaintext
     ↓
XOR with Key
     ↓
Ciphertext
     ↓
XOR with Same Key
     ↓
Plaintext
```

---

## 🔹 Example

Suppose:

```text id="5ib4gw"
Plaintext : A
ASCII     : 65

Key       : K
ASCII     : 75
```

Encryption:

```text id="0j1w6v"
65 XOR 75 = 10
```

Ciphertext value:

```text id="vcx40m"
10
```

Decryption:

```text id="yefy1u"
10 XOR 75 = 65
```

Recovered plaintext:

```text id="eijm3j"
A
```

---

## 🔹 Advantages

* Simple to implement
* Fast and efficient
* Requires very little computational power
* Useful for learning cryptography concepts

---

## 🔹 Limitations

* Not secure against modern attacks
* Weak if the key is short or reused
* Not suitable for protecting highly sensitive information

---

## 🌍 Real-World Usage

The XOR operation is commonly used in:

* Stream ciphers
* Malware obfuscation
* Data encoding
* Cryptographic algorithms

---

## 🚀 Project Connection

### Project: File Encryption Tool

In the File Encryption Tool project, XOR encryption was used to encrypt and decrypt file contents.

This project provided practical exposure to:

* Symmetric encryption
* Bitwise operations
* Cryptography fundamentals
* Secure file handling

---

## 📚 Key Takeaways

* XOR is a symmetric encryption technique.
* The same key is used for encryption and decryption.
* Applying XOR twice with the same key restores the original data.
* XOR is simple and useful for understanding cryptography concepts.
* Although educational, XOR encryption is not considered secure for modern applications.

---

## 📖 References

* Cryptography and Network Security – William Stallings
* CompTIA Security+
* Introduction to Cryptography
