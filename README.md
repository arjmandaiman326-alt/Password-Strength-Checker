# 🔐 Password Strength Checker

A beginner-friendly Python project that checks the strength of a password based on basic cybersecurity principles.

## Features

- Checks password length
- Detects uppercase letters
- Detects numbers
- Detects special characters
- Classifies passwords as:
  - Weak
  - Medium
  - Strong

## Technologies

- Python 3

## How it Works

The program asks the user to enter a password.

It then checks whether the password:

- is at least 8 characters long
- contains uppercase letters
- contains numbers
- contains special symbols

A score is calculated based on these conditions.

### Password Ratings

| Score | Strength |
|-------|----------|
| 0–1 | Weak |
| 2–3 | Medium |
| 4 | Strong |

## Example

```
Enter your password: Hello@123

Password Analysis
-----------------
Length: 9
Contains Uppercase: True
Contains Number: True
Contains Symbol: True

Password Strength: Strong
```

## Future Improvements

- Check for common leaked passwords
- Password entropy calculation
- Password generator
- GUI using Tkinter
- Dark mode interface

## Author

Aiman
