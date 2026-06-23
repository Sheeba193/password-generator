# Password Generator

A simple and responsive **Password Generator** built using **HTML**, **CSS**, and **JavaScript (ES6)**. This application allows users to generate secure passwords based on selected criteria such as password length, uppercase letters, lowercase letters, numbers, and symbols.

## Features

* Generate strong and secure passwords instantly
* Customize password length using a slider
* Include or exclude:

  * Uppercase letters (A-Z)
  * Lowercase letters (a-z)
  * Numbers (0-9)
  * Special symbols (!@#$%^&*)
* Copy generated password to clipboard with one click
* Password strength indicator (Weak, Medium, Strong)
* Clean and responsive user interface

## Technologies Used

* HTML5
* CSS3
* JavaScript (ES6)

## Project Structure

```text
password-generator/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

## How to Use

1. Open the application in your browser.
2. Select the desired password length using the slider.
3. Choose the character types to include:

   * Uppercase Letters
   * Lowercase Letters
   * Numbers
   * Symbols
4. Click the **Generate Password** button.
5. Copy the generated password using the copy icon.
6. Check the password strength indicator for security feedback.

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/password-generator.git
```

Navigate to the project folder:

```bash
cd password-generator
```

Open `index.html` in your browser.

## ES6 Features Used

* Arrow Functions
* Template Literals
* `const` and `let`
* Event Listeners
* Array Methods
* DOM Manipulation
* String Methods

## Password Strength Criteria

| Strength | Criteria                                                            |
| -------- | ------------------------------------------------------------------- |
| Weak     | Short length and limited character types                            |
| Medium   | Moderate length with multiple character types                       |
| Strong   | Long password containing uppercase, lowercase, numbers, and symbols |

## Learning Objectives

This project was built to practice:

* JavaScript fundamentals
* ES6 syntax and features
* DOM manipulation
* Event handling
* Random password generation
* Clipboard API usage
* Responsive UI design

## Future Improvements

* Password history
* Dark mode support
* Exclude similar characters (O, 0, l, 1)
* Exclude ambiguous symbols
* Password entropy calculation
* Custom character sets

## Author

**Bathseba Kerubo Kengere**

Frontend Developer | Software Developer | UI/UX Enthusiast

---

⚠️ **Note:** This project is intended for learning and portfolio purposes. For highly sensitive applications, consider using professionally audited password management tools and generators. 🔐
