# Responsive Shopping Cart Payment System with Bootstrap

**Developed by Saiteja**

## Table of Contents

1. [Overview](#overview)
2. [Features](#features)
3. [File Structure](#file-structure)
4. [Technologies Used](#technologies-used)
5. [Installation & Setup](#installation--setup)
6. [How to Use](#how-to-use)
7. [Bootstrap Integration](#bootstrap-integration)
8. [License](#license)

## Overview

This version of **ShoppingCartApp** introduces a credit card payment form and is fully responsive thanks to Bootstrap 5. Users can seamlessly complete transactions on any device, whether on desktop or mobile.

## Features

* Responsive layout powered by Bootstrap 5
* Credit card payment form with fields for:

  * Cardholder name
  * Card number
  * Expiration date
  * CVV
* Clean, modern UI for an intuitive checkout experience
* Mobile-first design for optimal performance on smartphones and tablets

## File Structure

```plaintext
ShoppingCartApp/
├── public/
│   ├── css/
│   │   └── paybycreditcard.css    # Custom styles for the payment form
│   └── html/
│       └── paybycreditcard.html   # Credit card payment page
```

## Technologies Used

* HTML5
* CSS3
* [Bootstrap 5](https://getbootstrap.com/)

## Installation & Setup

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-repo/ShoppingCartApp.git
   ```
2. **Navigate to the HTML folder**

   ```bash
   cd ShoppingCartApp/public/html
   ```
3. **Open the payment page**

   * Launch `paybycreditcard.html` in your preferred browser.

## How to Use

1. Enter the following details in the form:

   * **Cardholder’s Name**
   * **Card Number**
   * **Expiration Date**
   * **CVV**
2. Click **Pay Now** to simulate a payment transaction.

> **Note:** Backend payment processing is not implemented in this demo.

## Bootstrap Integration

Bootstrap 5 is included via CDN in the `<head>` of `paybycreditcard.html`:

```html
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
```

Custom styles are loaded through `paybycreditcard.css` to complement Bootstrap’s utilities.

## License

This project is licensed under the [MIT License](LICENSE).
Sai Teja Reddy K
![image](https://github.com/user-attachments/assets/a4cacfd1-eac3-4aec-8f90-c6484827dc14)

