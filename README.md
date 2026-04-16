# ARM-Assembly-Arithmetic-Operations
ARM Assembly implementation of arithmetic and logical operations including addition, subtraction with carry/borrow, multiplication, and bitwise operations. Developed for Microprocessors course and tested using Keil uVision.
# ARM Assembly Homework 2

This repository contains solutions for **Homework 2** of the Microprocessors / ARM Assembly course.

All programs are written and tested using **Keil uVision (ARM Cortex-M)**.

---

## 📌 Problem Description

The following operations are implemented using ARM Assembly:

---

### 🔹 1. Compute X

```
X = 0xF1064822 + STUDENT_NUMBER + 0xF0024563
```

✔ Result stored at:

```
0x20000030
```

---

### 🔹 2. Compute Y

```
Y = 0xF1064822 - STUDENT_NUMBER - 0xFFFFFFFF
```

✔ Uses:

* SUBS (with flags)
* SBC (borrow handling)

✔ Result stored at:

```
0x20000040
```

---

### 🔹 3. Compute Z

```
Z = 0xFEA05051 × STUDENT_NUMBER
```

✔ Uses:

* MUL / UMULL (depending on implementation)

✔ Result stored at:

```
0x20000050
```

---

### 🔹 4. Compute A (Bitwise Operations)

```
A = [0xAA AND (0xAB EOR 0xFF)] OR 0x01
```

✔ Uses:

* EOR
* AND
* ORR

✔ Result stored at:

```
0x20000060
```

---

## 🧠 Key Concepts Used

* Arithmetic operations (ADD, SUB, MUL)
* Carry and borrow handling (ADCS, SBC)
* Bitwise operations
* Memory addressing (LDR / STR)
* Register management

---

## 📂 Memory Map

| Variable | Address    |
| -------- | ---------- |
| X        | 0x20000030 |
| Y        | 0x20000040 |
| Z        | 0x20000050 |
| A        | 0x20000060 |

---

## ▶️ How to Run

1. Open Keil uVision
2. Create a new project
3. Add the `.s` / `.asm` file
4. Build the project
5. Run in Debug mode
6. Check Memory window

---

## 📸 Screenshots

* Debug execution
* Register values
* Memory contents

---

## 📂 Repository Structure

```
.
├── main.s
├── screenshots/
├── README.md
```

---

## 👤 Author

* Student ID: **1316180150**

---

## 🚀 Notes

* Code supports carry/borrow operations
* Designed for educational purposes
* Verified using Keil simulator

---
