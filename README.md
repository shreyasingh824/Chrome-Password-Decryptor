# Chrome Password Decryptor

## Overview

This Python script allows you to decrypt and retrieve saved passwords from the Google Chrome web browser. Google Chrome stores saved passwords in an encrypted format on your computer. This script helps you decrypt and display these passwords in a human-readable format.

## Prerequisites

Before using this script, ensure you have the following prerequisites:

- **Python**: You need to have Python installed on your computer. You can download Python from [python.org](https://www.python.org/downloads/).

- **pycryptodome**: This script uses the `pycryptodome` library to handle encryption and decryption. You can install it using `pip`:

## Usage

Follow these steps to use the script:

1. Clone or download this repository to your local machine.

2. Open a terminal or command prompt and navigate to the directory where the script is located.

3. Run the script using the following command:
   
4. The script will retrieve and display saved passwords from Google Chrome. It will show the website URL, login page URL, username, and decrypted password.

## How It Works

The script works as follows:

- It retrieves the encryption key used by Chrome from the "Local State" file.

- The Chrome login data file is copied to a temporary location to avoid conflicts with Chrome.

- The script connects to the copied database and retrieves the login data, including website URLs, login page URLs, and encrypted passwords.

- Using the encryption key, the script decrypts the passwords and displays the results.


## Acknowledgments

- This script was inspired by the work of various contributors and online resources who have explored Chrome's password storage mechanism.

- Special thanks to the authors and maintainers of the `pycryptodome` library for providing a convenient way to work with encryption in Python.



