# \# Password Strength Checker

# 

# A Tkinter-based GUI tool that evaluates password strength in real time and helps generate secure passwords.

# 

# \## Features

# 

# \- \*\*Real-time strength evaluation\*\* as you type — no button click needed

# \- Checks five criteria:

# &#x20; - Minimum 8 characters (12+ recommended for bonus strength)

# &#x20; - At least one uppercase letter (A–Z)

# &#x20; - At least one lowercase letter (a–z)

# &#x20; - At least one digit (0–9)

# &#x20; - At least one special character (`@ # $ % ^ \& \* ( ) , . ? !`)

# \- Color-coded checklist that turns green as each criterion is met

# \- Progress bar and strength label (Very Weak / Moderate / Strong) that update live

# \- \*\*Show/Hide password\*\* toggle

# \- \*\*Generate Secure Password\*\* — creates a 12-character password guaranteed to meet all criteria, using Python's `secrets` module for cryptographically secure randomness

# \- \*\*Copy to clipboard\*\* button

# 

# \## Why `secrets` instead of `random`

# 

# Password generation uses Python's `secrets` module rather than `random`, since `random` is not cryptographically secure and shouldn't be used to generate anything security-sensitive, including passwords.

# 

# \## Usage

# 

# ```bash

# python main.py

# ```

# 

# Requires Python 3 with Tkinter (included in most standard Python installations).

# 

# \## Tech stack

# 

# Python 3, Tkinter, `re`, `secrets`

# 

# \## Author

# 

# Lalit Bharambe — \[GitHub](https://github.com/lalitb25)

