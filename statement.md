## Problem Statement

The increasing reliance on digital services necessitates the use of *strong, unique passwords* to protect user accounts and sensitive data. Manually creating passwords that are long, complex, and truly random can be challenging for users. Many users resort to weak, predictable passwords or reuse the same password across multiple services, which significantly increases the risk of security breaches.

The problem is to provide an accessible and easy-to-use tool that automatically generates *highly randomized, complex passwords* based on user-defined length and character type criteria (letters, numbers, and symbols), thereby promoting better online security hygiene.

---

## Scope of the Project

The scope of the PyPassword Generator project is limited to a *command-line interface (CLI) application* developed in Python.

* *In Scope:*
    * Accepting user input for the desired number of letters, numbers, and symbols.
    * Generating a password by randomly selecting characters from predefined sets.
    * Ensuring the final password characters are *randomly shuffled* for maximum security.
    * Displaying the generated password to the user in the console.

* *Out of Scope (Future Enhancements):*
    * Graphical User Interface (GUI).
    * Password strength assessment or validation.
    * Saving or storing generated passwords (e.g., in a secure vault).
    * Integration with external password managers.

---

## Target Users

The primary target users are individuals who need a quick and easy way to create secure passwords.

* *General Users:* Anyone creating new online accounts who needs a strong, complex, and unique password.
* *Developers/Students:* Individuals working on projects who need strong, temporary passwords for testing or environment setup.
* *Security-Conscious Users:* Individuals looking to replace their current weak passwords with algorithmically generated, randomized ones.

---

## High-Level Features

* *Customizable Character Count:* Allows the user to specify the exact length contribution from letters, symbols, and numbers.
* *Comprehensive Character Set:* Utilizes uppercase letters, lowercase letters, numbers (0-9), and a common set of special symbols for robust password creation.
* *Guaranteed Randomization (Hard Level):* Implements a shuffling mechanism (random.shuffle()) to ensure the order of characters is completely unpredictable, preventing predictable patterns like "Letters-Numbers-Symbols."

---
