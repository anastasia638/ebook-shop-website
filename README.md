# Ebook Shop Website

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

> A frontend online bookstore allowing users to browse ebooks by category, view book details, and simulate a purchasing workflow.

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Technologies](#technologies)
- [Run Locally](#run-locally)
- [Pages](#pages)

---

## Overview

The **Ebook Shop Website** is a static frontend web application simulating an online bookstore. Users can browse a catalogue of ebooks, filter by category or price, view detailed book pages, and go through a simulated purchasing process (add to cart, checkout).

This project demonstrates proficiency in **HTML5 semantic markup**, **CSS3 styling and layouts** (Flexbox, Grid), and **vanilla JavaScript** for dynamic interactions (DOM manipulation, event handling).

---

## Features

- Homepage with featured ebooks and promotions
- Book catalogue with category filters
- Individual book detail pages
- Search functionality (by title or author)
- Shopping cart with add/remove/update functionality
- Simulated checkout flow
- Responsive design (mobile-friendly)
- Clean and accessible UI

---

## Project Structure

```
ebook-shop-website/
├── index.html              # Homepage
├── catalogue.html          # All books catalogue page
├── book-detail.html        # Individual book page
├── cart.html               # Shopping cart
├── checkout.html           # Checkout page
├── css/
│   ├── style.css             # Global styles
│   ├── catalogue.css         # Catalogue-specific styles
│   ├── cart.css              # Cart page styles
│   └── responsive.css        # Responsive/media queries
├── js/
│   ├── main.js               # Global scripts (navigation, header)
│   ├── catalogue.js          # Catalogue filtering and search
│   ├── cart.js               # Cart management (add, remove, total)
│   └── data.js               # Book data (JSON-like structure)
├── assets/
│   ├── images/               # Book cover images
│   └── icons/                # UI icons
└── README.md
```

---

## Technologies

| Technology | Role |
|------------|------|
| HTML5 | Semantic page structure |
| CSS3 | Styling, Flexbox, Grid, animations |
| JavaScript (ES6) | DOM manipulation, event handling, cart logic |
| Responsive Design | Mobile-first media queries |

---

## Run Locally

No build tools or server required — open directly in a browser.

```bash
# Clone the repository
git clone https://github.com/anastasia638/ebook-shop-website.git
cd ebook-shop-website

# Open in browser
open index.html
# Or on Linux:
xdg-open index.html
```

Alternatively, use a local server for best results:

```bash
# With Python
python3 -m http.server 8000
# Then open http://localhost:8000
```

---

## Pages

| Page | Description |
|------|-------------|
| `index.html` | Homepage with featured books and hero banner |
| `catalogue.html` | Full book list with search and filter by category |
| `book-detail.html` | Book details: cover, description, price, add to cart |
| `cart.html` | Cart with item list, quantities and total |
| `checkout.html` | Order form with delivery and payment fields |

---

## Skills Demonstrated

- **HTML5:** Semantic elements, forms, accessibility attributes
- **CSS3:** Flexbox, Grid, transitions, responsive design
- **JavaScript:** DOM manipulation, event listeners, local storage (cart persistence)
- **Frontend architecture:** Multi-page application structure
- **UX/UI:** Clean interface design, intuitive navigation

---

## Author

**Meriem Silmi** — Computer Science Student, France

[![GitHub](https://img.shields.io/badge/GitHub-anastasia638-black?style=flat-square&logo=github)](https://github.com/anastasia638)
[![Live Demo](https://img.shields.io/badge/Demo-View%20Site-green?style=flat-square)](https://anastasia638.github.io/ebook-shop-website)
