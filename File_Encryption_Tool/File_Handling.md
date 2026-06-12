# File Handling

## 📌 Overview

File handling is the process of creating, opening, reading, writing, and closing files in a program.

It allows applications to store and retrieve data from files, making persistent data storage possible.

---

## 🎯 Why File Handling is Important

* Store data permanently
* Read existing data
* Modify file contents
* Process large amounts of information
* Create logs and reports

---

## 🔹 Common File Operations

* Create a file
* Open a file
* Read data from a file
* Write data to a file
* Append data to a file
* Close a file

---

## 🔹 File Modes

| Mode | Description         |
| ---- | ------------------- |
| `r`  | Read mode           |
| `w`  | Write mode          |
| `a`  | Append mode         |
| `r+` | Read and write mode |
| `rb` | Read binary mode    |
| `wb` | Write binary mode   |

---

## 🔹 Common Functions in C

### fopen()

Used to open a file.

Example:

```c
FILE *fp = fopen("file.txt", "r");
```

---

### fread()

Reads data from a file.

Example:

```c
fread(buffer, sizeof(char), size, fp);
```

---

### fwrite()

Writes data to a file.

Example:

```c
fwrite(buffer, sizeof(char), size, fp);
```

---

### fclose()

Closes a file and releases resources.

Example:

```c
fclose(fp);
```

---

## 🌍 Real-World Applications

* Text editors
* Databases
* Log files
* Configuration files
* Encryption tools
* Backup systems

---

## 🚀 Project Connection

### Project: File Encryption Tool

The File Encryption Tool used file handling to:

* Read file contents
* Encrypt data
* Write encrypted data back to a file
* Decrypt and restore the original content

This project provided practical experience with:

* File operations
* Binary data processing
* Secure data storage
* Cryptography fundamentals

---

## 📚 Key Takeaways

* File handling enables persistent data storage.
* Programs interact with files using different modes.
* `fopen()`, `fread()`, `fwrite()`, and `fclose()` are fundamental file operations.
* File handling is widely used in cybersecurity and software development.

---

## 📖 References

* The C Programming Language – Kernighan and Ritchie
* Programming in ANSI C – E. Balagurusamy
* CompTIA Security+
