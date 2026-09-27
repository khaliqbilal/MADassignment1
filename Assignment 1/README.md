# Salary Calculator - Flutter App

## Assignment 1 - Mobile Application Development (CSC303)

A complete Salary Calculator application built in Flutter that:
- Collects user salary details
- Calculates tax deductions
- Displays net monthly income

---

## Features

- 📋 **Form with 4 input fields:**
  - Basic Salary
  - House Rent Allowance (HRA)
  - Medical Allowance
  - Travel Allowance

- 🧮 **Calculations:**
  - Gross Salary = Basic + HRA + Medical + Travel
  - Tax: 10% if Gross ≤ 50,000 | 20% if Gross > 50,000
  - Net Monthly Income = Gross Salary − Tax Deduction

- ✅ **Result Display Order:**
  1. Tax Deduction (shown first)
  2. Net Monthly Income (shown second)

- 🔄 **Reset Button** to clear all fields

- ✨ **Form Validation** on all input fields

---

## Screenshots

| Input Screen | Result Screen |
|---|---|
| ![Input Screen](Screenshots/input_screen.jpg) | ![Result Screen](Screenshots/result_screen.jpg) |

---

## Project Structure

```
salary_calculator/
├── lib/
│   └── main.dart        # Main application code
├── pubspec.yaml         # Project dependencies
└── Screenshots/
    ├── input_screen.jpg
    └── result_screen.jpg
```

---

## Student Info

- **Name:** Khaliq Bilal
- **Course:** CSC303 - Mobile Application Development
- **Assignment:** Assignment No. 1 (CLO-2)
