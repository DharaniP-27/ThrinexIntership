# 🔐 Password Strength Analyzer

## Project Overview

Password Strength Analyzer is a Python-based cybersecurity project that evaluates the strength of user-entered passwords and provides suggestions to improve password security.

The application checks various password security parameters such as:

- Password length
- Uppercase letters
- Lowercase letters
- Numbers
- Special characters
- Password reuse

Based on the analysis, the system classifies passwords as:

- Weak Password
- Medium Password
- Strong Password

The project also includes a secure password generator that creates strong random passwords.

---

# 🎯 Objectives

The main objectives of this project are:

- To analyze password security levels.
- To identify weak and insecure passwords.
- To educate users about strong password practices.
- To provide suggestions for improving password strength.
- To generate secure password alternatives.
- To reduce password reuse.

---

# 🚀 Features

## 1. Password Length Checking

The system checks whether the password contains a minimum of 8 characters.

Example:

```
Input:
abc123

Output:
Weak Password

Suggestion:
Use at least 8 characters
```

---

## 2. Uppercase Letter Detection

Checks whether the password contains uppercase letters.

Example:

```
Input:
password123

Suggestion:
Add uppercase letters
```

---

## 3. Lowercase Letter Detection

Checks whether lowercase characters are present.

Example:

```
Input:
PASSWORD123

Suggestion:
Add lowercase letters
```

---

## 4. Number Detection

Checks whether numbers are included in the password.

Example:

```
Input:
SecurePassword

Suggestion:
Add numbers
```

---

## 5. Special Character Detection

Checks for special characters:

```
@ # $ % ^ & *
```

Example:

```
Secure@123
```

---

## 6. Password Strength Classification

The application calculates a security score.

| Score | Password Strength |
|-------|------------------|
| 5 | Strong Password |
| 3-4 | Medium Password |
| Below 3 | Weak Password |

---

## 7. Password Reuse Detection

The system detects previously entered passwords and warns users if the same password is reused.

Example:

```
Warning:
Password already used. Create a new password.
```

---

## 8. Strong Password Generator

The application generates random secure passwords using:

- Uppercase letters
- Lowercase letters
- Numbers
- Special characters

Example:

```
Generated Password:

A7@kp92Lm#Qx
```

---

# 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Application development |
| Regular Expression (Regex) | Password pattern validation |
| Random Library | Secure password generation |
| String Library | Character selection |

---

# 📂 Project Structure

```
Password-Strength-Analyzer

│
├── password_analyzer.py
│
├── README.md
│
└── requirements.txt
```

---

# ⚙️ Installation and Execution

## Step 1: Clone Repository

```
git clone <repository-url>
```

## Step 2: Navigate to Project Directory

```
cd Password-Strength-Analyzer
```

## Step 3: Run the Application

```
python3 password_analyzer.py
```

---

# 💻 Sample Output

## Example 1: Weak Password

Input:

```
abc123
```

Output:

```
Strength: Weak Password

Suggestions:
- Use at least 8 characters
- Add uppercase letters
- Add special characters
```

---

## Example 2: Strong Password

Input:

```
Cyber@2026Secure
```

Output:

```
Strength: Strong Password
```

---

## Example 3: Password Generator

Output:

```
Generated Password:

H7@kp92Lm$Qx
```

---

# 🔄 Working Methodology

1. User enters a password.
2. Password is passed to the analysis module.
3. The application checks password security conditions.
4. A security score is calculated.
5. Password strength is displayed.
6. Suggestions are provided for improvement.

---

# 📌 Future Enhancements

Future improvements include:

- Database integration for storing password history.
- GUI application using Tkinter.
- Password breach detection using security APIs.
- Machine learning-based password strength prediction.
- Integration with authentication systems.

---

# ✅ Conclusion

Password Strength Analyzer is a cybersecurity-focused Python application that helps users create secure passwords by analyzing password complexity.

The project demonstrates concepts of:
- Cybersecurity
- Password security
- Python programming
- Regular expression-based validation
