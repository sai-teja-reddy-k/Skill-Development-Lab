# Responsive Shopping Cart Web Application

**Developed by Saiteja**

## Table of Contents

1. [Aim](#aim)
2. [Description](#description)
3. [Project Structure](#project-structure)
4. [Installation & Setup](#installation--setup)
5. [Usage](#usage)
6. [License](#license)

## Aim

To build a fully responsive shopping cart web application leveraging modern CSS3 techniques—Flexbox and Grid—to ensure a seamless user experience across devices of all sizes.

## Description

This project implements a user-friendly interface that allows visitors to:

* Register for a new account and log in securely.
* Browse a dynamic product catalog.
* Add items to a shopping cart with real-time updates.
* View and manage cart contents before checkout.

By using Flexbox and Grid, the layout adjusts effortlessly to mobile phones, tablets, and desktops, providing a consistent look and feel on every screen.

## Project Structure

```plaintext
ShoppingCartApp/
├── public/
│   ├── css/
│   │   ├── utils.css      # Utility styles (e.g., navigation bar)
│   │   ├── index.css      # Catalog item styles
│   │   ├── cart.css       # Shopping cart page styles
│   │   ├── login.css      # Login page styles
│   │   └── register.css   # Registration page styles
│   ├── images/            # Product and UI images
│   ├── js/
│   │   └── script.js      # Main JavaScript logic
│   └── html/
│       ├── index.html     # Product catalog
│       ├── cart.html      # Shopping cart overview
│       ├── login.html     # User login form
│       └── register.html  # User registration form
├── server.js              # Express.js server entry point
├── package.json           # Dependencies and scripts
└── README.md              # Project documentation
```

## Installation & Setup

### Prerequisites

* [Node.js](https://nodejs.org/) (v14 or higher)
* npm (v6 or higher)

### Steps to Run

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-repo/shopping-cart.git
   cd shopping-cart
   ```
2. **Install dependencies**

   ```bash
   npm install
   ```
3. **Start the server**

   ```bash
   node server.js
   ```
4. **Open in browser**
   Navigate to `http://localhost:3000` to view the application.

## Usage

1. **Register** a new user or **log in** with existing credentials.
2. **Browse** the catalog and click **Add to Cart** on desired products.
3. **View Cart** to adjust quantities or remove items.
4. Proceed to **Checkout** (functionality to be implemented).

## License

This project is released under the [MIT License](LICENSE).

Sai teja Reddy K
