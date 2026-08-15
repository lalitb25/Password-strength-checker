# Password Strength Checker

A Tkinter GUI that evaluates password strength in real time and generates secure passwords.

## Features

- Real-time strength check as you type (no button needed)
- Checks length (8+, 12+ for bonus), uppercase, lowercase, digits, and special characters
- Color-coded checklist and live strength meter (Very Weak / Moderate / Strong)
- Show/Hide password toggle
- Generate Secure Password button (uses Python's `secrets` module, not `random`, for actual security)
- Copy to clipboard button

## Usage

```bash
python password_checker.py
```

Requires Python 3 with Tkinter (included by default in most Python installs).

## Tech stack

Python 3, Tkinter, `re`, `secrets`

## Author

Lalit Bharambe — [GitHub](https://github.com/lalitb25)
