Password Generator
Overview
This project is a simple and efficient password generator designed to create strong, random passwords. It ensures that each password contains a mix of uppercase letters, lowercase letters, numbers, and symbols, making it highly secure and suitable for various applications.

Features
Random Password Generation: Generates a 12-character password with a mix of uppercase letters, lowercase letters, numbers, and symbols.
User-Friendly Interface: The password is displayed in an input box, making it easy to copy and use.
Copy to Clipboard: A convenient function to copy the generated password to the clipboard with a single click.
How It Works
Character Sets: The script defines four sets of characters: uppercase letters, lowercase letters, numbers, and symbols.
Password Creation: The createPassword function randomly selects one character from each set to ensure the password includes all character types. It then fills the remaining length with random characters from a combined set of all characters.
Copy Functionality: The copyPassword function allows users to easily copy the generated password to their clipboard for quick use.
Usage
Click the button to generate a new password.
The generated password will appear in the input box.
Click the copy button to copy the password to your clipboard.
