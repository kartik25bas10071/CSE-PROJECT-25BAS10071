# CSE-PROJECT-26BAS10071
PyPassword Generator 🔑


## Overview of the project

This is a *command-line password generator* designed to create strong, random passwords based on user-specified requirements. It prompts the user to input the desired number of letters, symbols, and numbers, and then generates a secure, mixed-case password by shuffling the selected characters.

---

## Features

* *Customizable Length:* Users can specify the exact number of letters, symbols, and numbers for the password.
* *Randomized Order:* The generated password is *fully randomized*, mixing the positions of letters, symbols, and numbers to increase security (Hard level implementation).
* *Clear Output:* Displays the final generated password to the user.

---

## Technologies/tools used

* *Language:* Python
* *Libraries:* random module (built-in)

---

## Steps to install & run the project

1.  *Prerequisites:* Ensure you have *Python 3* installed on your system.
2.  *Save the Code:* Save the provided code into a file named password_generator.py.
3.  *Run from Terminal:* Open your terminal or command prompt, navigate to the directory where you saved the file, and execute the following command:

    bash
    python password_generator.py
    

4.  *Follow Prompts:* The program will prompt you to enter the number of letters, symbols, and numbers you want in your password. Enter an integer value for each.

---

## Instructions for testing

To test the application, run the script and observe the following:

1.  *Input:* When prompted, enter different combinations of non-negative integers (e.g., 8 letters, 2 symbols, 4 numbers).
2.  *Output Length:* Verify that the length of the generated password is the sum of the letters, symbols, and numbers you requested. (e.g., 8 + 2 + 4 = 14 characters).
3.  *Character Mix:* Ensure the final password contains a mix of uppercase/lowercase letters, numbers, and symbols (!, #, $, %, &, (, ), *, +). The characters should appear in a random, non-sequential order.
