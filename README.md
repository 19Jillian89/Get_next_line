# get_next_line

![Language](https://img.shields.io/badge/language-C-blue)
![Status](https://img.shields.io/badge/status-complete-success)
![42](https://img.shields.io/badge/42-common%20core-black)
![Bonus](https://img.shields.io/badge/bonus-in%20progress-yellow)

---

## 🔍 Project Overview

`get_next_line` is a function that reads a file **line by line** from a given file descriptor. Each call returns the next line, including the newline character (`\n`) if present. This project is part of the [42 Common Core curriculum](https://www.42network.org/), and is implemented using only the allowed functions: `read`, `malloc`, and `free`.

---

## ✅ Features

- 📄 Returns one line per call (including `\n`)
- 📁 Supports multiple file descriptors at once
- ⚙️ Customizable buffer size via `BUFFER_SIZE`
- 🚫 No use of standard I/O functions (`fgets`, `strtok`, etc.)

---
🔁 Bonus

The bonus part includes:

- Reading from multiple file descriptors simultaneously without data leaks or interference.

- Proper handling of edge cases (empty files, very long lines, etc.).

---
## 📄 License

This project is for educational purposes and is part of the 42 Common Core curriculum.

---

If you found this project helpful or interesting, feel free to star ⭐️ or fork it!
