# 🔑 SCT_CS_3 — Password Strength Checker

> **SkillCraft Technology | Cyber Security Internship — Task 03**

---

## 📌 Task Description

Build a tool that **assesses the strength of a password** based on criteria such as length, presence of uppercase and lowercase letters, numbers, and special characters.

---

## 🧠 Scoring System

| Criterion | Points |
|---|---|
| Contains uppercase (A–Z) | +1 |
| Contains lowercase (a–z) | +1 |
| Contains numbers (0–9) | +1 |
| Contains special characters | +1 |
| Length ≥ 8 | +1 |
| Length ≥ 12 | +1 |
| Length ≥ 16 | +1 |
| Length ≥ 20 | +1 |
| **Maximum Score** | **8** |

### Strength Levels
| Score | Rating |
|---|---|
| 0–2 | Very Weak ❌ |
| 3–4 | Weak ⚠️ |
| 5 | Moderate 🟡 |
| 6 | Strong 🟢 |
| 7–8 | Very Strong 💪 |

---

## 📁 File Structure

```
SCT_CS_3/
├── password_strength_cli.py   # Command-Line Interface version
├── password_strength_gui.py   # Graphical User Interface version
└── README.md                  # Project documentation
```

---

## ⚙️ Requirements

- Python 3.x
- `tkinter` (built-in — GUI only)
- `re`, `math` (built-in)

---

## 🚀 How to Run

### CLI Version
```bash
python password_strength_cli.py
```

### GUI Version
```bash
python password_strength_gui.py
```

---

## 🖥️ Features

### CLI
| Feature | Description |
|---|---|
| Live Analysis | Analyses password on each entry |
| Criteria Breakdown | Shows each criterion pass/fail |
| Entropy Estimate | Calculates bit entropy |
| Visual Bar | ASCII strength progress bar |
| Suggestions | Tips to improve weak passwords |

---

## 📸 Sample Output (CLI)

```
  ─── Analysis ───────────────────────────────
  Length         : 18 chars
  Uppercase      : ✅
  Lowercase      : ✅
  Numbers        : ✅
  Special Chars  : ✅
  Entropy        : ~118.0 bits

  Strength  [████████████████████] 7/8

  Result  ➜  Very Strong 💪

  🎉 Your password meets all criteria!
```

---

## 🔒 Password Examples

| Password | Strength | Score |
|---|---|---|
| `abc` | Very Weak ❌ | 1/8 |
| `password` | Very Weak ❌ | 2/8 |
| `P@ssw0rd` | Moderate 🟡 | 5/8 |
| `MyStr0ng!Pass#2026` | Very Strong 💪 | 7/8 |

---

## output screen shots

<img width="1023" height="871" alt="Screenshot 2026-05-15 030303" src="https://github.com/user-attachments/assets/b50fc481-0b8b-4c78-9acb-7ca967ca5b8b" />

---

## 👩‍💻 Author

**Iqra Raheem**
Cyber Security Intern — SkillCraft Technology
Internship ID: SCT/MAY26/0435

---
