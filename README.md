# Password Generator

This is a simple password generator tool created using **Python** and **Tkinter** for the graphical user interface (GUI). The application allows users to generate secure, random passwords based on user-defined criteria. Users can also copy the generated password to the clipboard by selecting its serial number.

## Features

- **Generate Multiple Passwords**: Allows the user to specify how many passwords to generate.
- **Customizable Length**: Users can define the length of the generated passwords.
- **Password Complexity**: Each generated password includes:
  - Lowercase letters
  - Uppercase letters
  - Numbers
  - Special characters (symbols)
- **Copy to Clipboard**: Users can easily copy a selected password to the clipboard.
- **Serial Numbering**: Each generated password is assigned a serial number for easy identification.

## Requirements

- Python 3.x
- Tkinter (usually comes pre-installed with Python)
- **pyperclip** library for clipboard functionality

### Installing Dependencies

To install the required dependencies, you can use `pip`:

```bash
pip install pyperclip
