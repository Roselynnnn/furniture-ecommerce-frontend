# Furniture E-commerce Frontend

A responsive, multi-page furniture shopping website prototype built with **HTML, CSS, and vanilla JavaScript**. Created as a university web development project, it explores storefront navigation, product detail interactions, and a simulated checkout journey.

**[Live Demo](https://roselynnnn.github.io/furniture-ecommerce-frontend/)** · **[Source Code](https://github.com/Roselynnnn/furniture-ecommerce-frontend)**

## Features

- Furniture storefront with category navigation and promotional sections
- Product browsing and search-related pages
- Product detail pages with image tabs and expandable information sections
- Shopping-cart interface with quantity adjustment and automatic subtotal calculation
- Cart item removal and a multi-page checkout prototype (order summary, payment, confirmation)
- Responsive layouts for desktop and smaller screens

## Tech Stack

- **HTML5** — page structure
- **CSS3** — layouts, styling, and responsive media queries
- **JavaScript (vanilla)** — DOM interactions, quantity controls, price calculations, and page navigation
- **GitHub Pages** — static website hosting

## Project Structure

```text
├── index.html             # Home page
├── search.html            # Search interface
├── searchresults.html     # Search results interface
├── product.html           # Product details
├── shoppingcart.html      # Shopping cart
├── ordersummary.html      # Order summary
├── payment.html           # Payment interface prototype
├── confirmation.html      # Order confirmation
├── script.js              # Shared interactions
├── style.css              # Shared styles and responsive layout
├── images/                # Visual assets
└── font/                  # Font assets
```

## Run Locally

This project requires no build step or package installation.

1. Clone or download the repository.
2. Open `index.html` in a browser.
3. Navigate through the linked pages to explore the shopping flow.

Alternatively, serve the folder locally using `python -m http.server 8000` and open `http://localhost:8000`.

## Scope and Limitations

This is a **frontend prototype**, not a production e-commerce platform. The cart and checkout illustrate browser-side interactions; there is **no backend, account system, real transaction processing, or payment integration**. Product information and interface content are for demonstration purposes.

## Credits

Design credit on the original website: **Xiaoyue Liu and Li Yee Goh**. The demonstration storefront uses Pacific Furniture & Bedding branding/content as part of the original coursework concept; it is **not an official commercial store or affiliated sales channel**.
