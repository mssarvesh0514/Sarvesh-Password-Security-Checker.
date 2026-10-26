# Password Security Checker

**Student:** Sarvesh  
**Project type:** Beginner cybersecurity / Python  
**Purpose:** Demonstrate basic password-strength awareness.

## Project description
The Password Security Checker estimates password strength using length, lowercase and uppercase letters, numbers, symbols, and a small list of commonly used passwords. It provides feedback to help users improve password habits.

## Technologies used
- Python 3
- Jupyter Notebook (`.ipynb`)
- Python standard library: `re`

## Dataset
No external dataset is required. The project includes a small built-in list of common example passwords in the source code. This list is only for demonstration and is not comprehensive.

## Setup
1. Install Python 3.
2. Optional: install Jupyter Notebook with `python -m pip install notebook`.
3. Download or clone this project folder.
4. Open a terminal in the project folder.
5. If using a virtual environment, activate it.
6. Install the listed dependencies (none are required): `python -m pip install -r requirements.txt`
7. Start Jupyter: `jupyter notebook`
8. Open `Sarvesh_PasswordSecurityChecker.ipynb` and run the cells from top to bottom.

You can also copy the code cells into a regular Python file and run it with Python 3.

## Example
- `123456` should be identified as weak/common.
- `hello123` should receive improvement suggestions.
- A longer example containing mixed character types should receive a stronger rating.

## Privacy and responsible use
- **Do not enter a real password you currently use.** Use made-up test values only.
- The project does not save or transmit entered passwords.
- Do not commit real passwords, API keys, or other secrets to GitHub.

## Limitations
This is an educational demonstration, not a guarantee of password security. It does not use a comprehensive breached-password database and does not estimate password-cracking time. Password length, uniqueness, password-manager use, and multi-factor authentication are important.

## Files
- `Sarvesh_PasswordSecurityChecker.ipynb` — project code
- `requirements.txt` — dependency list
- `Sarvesh_PasswordSecurityChecker_Report.docx` — project report
- `README.md` — project overview and instructions
