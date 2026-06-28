# Expense Tracker

A command-line Expense Tracker application built with Python as part of DecodeLabs Industrial Training Program — Batch 2026.

## Description

This program allows users to enter multiple expense amounts, select a category for each entry, and view a complete financial report at the end of the session. The report includes total amount spent, category-wise breakdown with percentages, and average expense calculation.

## Key Concepts Used

- Accumulator Pattern — total += amount
- Float conversion for numeric input validation
- try/except ValueError for defensive coding
- Dictionaries to store structured transaction data
- while True loop with sentinel value kill switch
- datetime module for transaction timestamps
- Modular functions following IPO architecture

## How to Run

```bash
python expense_tracker.py
```

## Features

- Add unlimited expenses with category tags
- Categories: Food & Dining, Transport, Shopping, Education, Utilities, Other
- Live running total after every entry
- Full financial report on exit
- Category-wise breakdown with percentage
- Average expense calculation
- Invalid input and negative value handling

## Tech Stack

- Language: Python 3
- Module: datetime
- Editor: VS Code
- Version Control: GitHub

## About DecodeLabs

- Website: www.decodelabs.tech
- Email: decodelabs.tech@gmail.com
