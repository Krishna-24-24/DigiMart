# 🛒 DigiMart — E-Commerce Web App

> A fully functional e-commerce web application built with HTML, CSS, and JavaScript that lets users browse products, manage a shopping cart, apply coupons, and place orders with form validation.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?style=flat&logo=javascript&logoColor=black)

---

## 🌐 Live Demo

**[https://Krishna-24-24.github.io/DigiMart/](https://Krishna-24-24.github.io/DigiMart/)**

---

## 📌 About the Project

**DigiMart** is a single-page e-commerce application that simulates the core features of a real-world online shopping platform. Built entirely with vanilla HTML, CSS, and JavaScript — no frameworks, no libraries — it covers product listing, live inventory tracking, cart management, coupon discounts, and a full checkout flow with input validation.

---

## ✨ Features

- ✅ Dynamic product listing with real-time stock tracking
- ✅ Add to Cart with live inventory decrement
- ✅ Low stock warning and auto Out-of-Stock detection
- ✅ Shopping cart popup with quantity controls (+ / −)
- ✅ Delete item from cart with inventory restore
- ✅ Coupon code system with 10% discount (`VIT`)
- ✅ Remove coupon option
- ✅ Checkout form with full input validation
- ✅ Payment options: Cash on Delivery, UPI, Card
- ✅ Dynamic payment fields (UPI ID / Card Number shown on selection)
- ✅ Order confirmation screen
- ✅ Stock updated after order is placed

---

## 🖼️ App Flow

```
Homepage (Browse Products)
       ↓
  Add to Cart → Cart Popup
       ↓
  Apply Coupon (optional) → Subtotal / Discount / Total
       ↓
  Proceed to Buy → Delivery Details Form
       ↓
  Select Payment Method (COD / UPI / Card)
       ↓
  Place Order → 🎉 Order Confirmation
       ↓
  Go to Home → Stock Updated
```

---

## 🔒 Validation Rules

| Field | Rule |
|-------|------|
| Name | Required, alphabets only |
| Place | Required, alphabets only |
| Pincode | Required, exactly 6 digits |
| Mobile | Required, exactly 10 digits |
| UPI ID | Required if UPI selected, must contain `@` |
| Card Number | Required if Card selected, exactly 16 digits |

---

## 🛍️ Product Catalog

The app includes 10 products: Mobile Phone, Laptop, Earbuds, Water Bottle, Classmate Notebook, Refrigerator, Headphones, Shoes, Study Table, and Smart Watch — each with a name, price, stock count, and image.

---

## 💰 Coupon Code

| Code | Discount |
|------|----------|
| `VIT` | 10% off subtotal |

---

## 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| **HTML5** | Page structure, forms, popups |
| **CSS3** | Layout, animations, modal overlays |
| **JavaScript** | Cart logic, validation, inventory tracking |

---

## ⚙️ Key JavaScript Concepts

- `Array.find()` — locates products by name
- `Object` as cart store — tracks item name, price, quantity
- DOM manipulation — dynamically renders product cards and cart items
- `regex` — validates mobile, pincode, UPI, card number
- CSS `display:flex/none` — shows/hides popups and payment fields
- Real-time stock sync between cart and product listing

---

## 📂 Project Structure

```
DigiMart/
├── index.html     # All HTML, CSS, and JavaScript in one file
└── README.md
```

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
