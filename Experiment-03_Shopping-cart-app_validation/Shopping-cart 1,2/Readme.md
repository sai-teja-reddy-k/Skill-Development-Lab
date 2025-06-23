# Client-Side Validation with JavaScript

**Developed by Saiteja**

## Table of Contents

1. [Aim](#aim)
2. [Requirements](#requirements)
3. [Theory](#theory)
4. [Features](#features)

   * [Registration Form Validation](#registration-form-validation)
   * [Shopping Cart Validation](#shopping-cart-validation)
5. [Usage](#usage)
6. [Implementation](#implementation)
7. [File Structure](#file-structure)
8. [License](#license)

## Aim

To implement robust client-side validation using JavaScript for both the user registration form and the shopping cart page, ensuring data integrity and an improved user experience.

## Requirements

* **Software:** Google Chrome, VS Code (or any text editor)
* **Technologies:** HTML5, CSS3, JavaScript

## Theory

Client-side validation uses JavaScript to check user inputs before sending data to the server. By validating fields dynamically, invalid submissions are prevented, reducing server load and giving immediate feedback to users.

## Features

### Registration Form Validation

* Ensures all fields (name, email, password) are completed.
* Validates email format using a regular expression.
* Enforces a minimum password length of 6 characters.
* Displays alerts for any invalid input.

### Shopping Cart Validation

* Retrieves cart items stored in `localStorage`.
* Verifies that quantity values are positive numbers.
* Alerts users when invalid quantities are entered.
* Dynamically recalculates and updates the total price on valid changes.

## Usage

1. **Registration:**

   * Open the registration form.
   * Fill in the required details and click **Submit**.
   * JavaScript validation will run and block submission if errors are detected.
2. **Shopping Cart:**

   * Open the shopping cart page.
   * Review and adjust item quantities.
   * Invalid inputs will trigger alerts, and the total will update in real time.

## Implementation

All validation logic is written in plain JavaScript:

* **Registration script** handles form submission events and applies regex/email checks and length validations.
* **Cart script** reads from `localStorage`, loops through items, validates quantity inputs, and updates the displayed total.

## File Structure

```plaintext
ShoppingCartApp/
└── public/
    ├── html/
    │   ├── register.html     # Registration form page
    │   └── cart.html         # Shopping cart page
    ├── js/
    │   └── validation.js     # JavaScript validation logic
    └── css/
        └── validation.css   # Styles for validation messages
```

## License
Sai Teja
![image](https://github.com/user-attachments/assets/bc5cb9bb-cde9-4bd1-878d-66da0de00f3c)


This project is open-source and released under the [MIT License](LICENSE).
Sai Teja Reddy
