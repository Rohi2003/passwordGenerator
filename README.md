# Secure Password Generator

A simple and secure password generator implemented in JavaScript for use in web applications.


#Site is live at https://rohi2003.github.io/passwordGenerator/

📸 Screenshots
<img width="960" alt="image" src="https://github.com/Rohi2003/passwordGenerator/assets/87049122/7a41b6fa-5960-4680-9763-49ab3339408e">

## Features

- Generate secure passwords with various options.
- Adjustable password length using a slider.
- Copy generated passwords to the clipboard.
- Password strength indicator.

## Usage

1. Open `index.html` in your web browser.
2. Adjust the password length using the slider.
3. Check/uncheck options for including uppercase, lowercase, numbers, and symbols.
4. Click the "Generate" button to generate a secure password.
5. Click the "Copy" button to copy the generated password to the clipboard.

## Options

- **Uppercase:** Include uppercase letters in the password.
- **Lowercase:** Include lowercase letters in the password.
- **Numbers:** Include numbers in the password.
- **Symbols:** Include symbols in the password.

## Password Strength Indicator

The password strength indicator provides feedback based on selected options and password length:

- Green: Strong password (Uppercase, lowercase, numbers/symbols, and length >= 8).
- Yellow: Moderate password (Uppercase/lowercase, numbers/symbols, and length >= 6).
- Red: Weak password (Either uppercase or lowercase, and either numbers or symbols, or length < 6).

## Copying to Clipboard

Clicking the "Copy" button copies the generated password to the clipboard. A message will indicate if the operation was successful.


## Acknowledgments

- Password generation inspired by [Fisher Yates Method](https://en.wikipedia.org/wiki/Fisher%E2%80%93Yates_shuffle).

## Author

Rohit kumar



