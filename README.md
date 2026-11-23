# ☕ BREW & BITE — Modern Cafe & Restaurant Landing Page

> **"Sip. Savor. Repeat."**  
> A modern, responsive, single-page restaurant landing page for **BREW & BITE**, a fictional cafe and restaurant concept based in Dhaka, Bangladesh. Built as a self-contained frontend project ready for direct GitHub Pages deployment.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/Vanilla_JS-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-222222?style=for-the-badge&logo=githubpages&logoColor=white)

---

## 🌐 Live Demo

🔗 **Live Site:** [https://your-username.github.io/brew-and-bite/](https://your-username.github.io/brew-and-bite/) _(Replace with your actual GitHub Pages URL)_

---

## 📸 Preview

> _(Add screenshots of your Light Mode, Dark Mode, Menu, and Cart Drawer here)_

|                Light Mode (Desktop)                 |                Dark Mode (Desktop)                |
| :-------------------------------------------------: | :-----------------------------------------------: |
| ![Light Mode Preview](./screenshots/light-mode.png) | ![Dark Mode Preview](./screenshots/dark-mode.png) |

---

## 📖 Project Overview

**BREW & BITE** is designed to simulate the official digital storefront of a premium contemporary cafe and restaurant in Dhaka. It combines coffee culture, international favorites, local Bangladeshi dishes, bakery items, and healthy meals into one conversion-focused, interactive web experience.

The entire application is built in a **single, zero-build `index.html` file** using semantic HTML5, Tailwind CSS (via CDN), and modular Vanilla JavaScript—making it lightweight, maintainable, and effortless to host on GitHub Pages.

---

## ✨ Key Features

### 🍽️ Interactive Menu & Filtering

- **6 Filterable Categories:** Coffee & Beverages, Burger & Sandwich, Pizza & Pasta, Desserts & Bakery, Bangladeshi Food, and Healthy Food & Salad.
- **30 Demo Menu Items** with BDT (`৳`) pricing, descriptions, high-quality imagery, and bestseller badges.

### 🛒 Full Shopping Cart System

- Add items, adjust quantities, or remove products inside a sleek cart drawer/modal.
- Real-time cart badge counter and live calculations for **Subtotal, Discount, Delivery Fee, and Final Total**.
- Persistent cart state using `localStorage` and empty-cart handling.
- Toast notifications for cart and coupon actions.

### 🎟️ Working Coupon System

- Built-in coupon validation with instant success/error feedback, duplicate prevention, coupon removal, and negative-total protection.
- **Demo Coupon Codes:**
  - `WELCOME10` — 10% off subtotal
  - `BREW50` — ৳50 flat discount
  - `STUDENT15` — 15% student discount

### 💳 Checkout & Demo Payment UI

- Supports **Delivery** and **Pickup** order types with form validation.
- Payment method selector: **Cash on Delivery**, **bKash (Demo)**, **Nagad (Demo)**, and **Card (Demo)**.
- Order summary breakdown and confirmation screen with a generated demo Order ID.

### 🌗 Dark & Light Mode

- Coordinated Light Theme (Warm Cream & Soft Ivory) and Dark Theme (Deep Forest Green & Charcoal).
- Automatically respects system preferences on first visit and saves user choice via `localStorage`.

### 🌍 Bilingual Interface (`EN | বাং`)

- Real-time full-UI switching between **English** (default) and **Bangla** using a centralized JavaScript translation dictionary.
- Translates navigation, hero, menu items, cart, checkout, offers, FAQ, contact, and footer.
- Renders Bangla cleanly with dedicated Bengali web fonts (`Hind Siliguri` / `Noto Sans Bengali`) and persists language selection in `localStorage`.

### 📱 Responsive, Accessible & SEO-Ready

- Mobile-first responsive layout tested across `375px`, `768px`, `1024px`, and `1440px` breakpoints.
- Accessible FAQ accordion, semantic HTML, visible keyboard focus states, and `prefers-reduced-motion` support.
- SEO meta tags, Open Graph metadata, descriptive `alt` text, and lazy-loaded images.

---

## 🎨 Design System

### Color Palette

| Role             | Hex Code  | Preview                |
| :--------------- | :-------- | :--------------------- |
| **Forest Green** | `#183B32` | Primary Brand          |
| **Deep Green**   | `#102A25` | Dark Surface / Accents |
| **Warm Cream**   | `#F7F3EA` | Light Background       |
| **Soft Ivory**   | `#FFFDF8` | Light Card Surface     |
| **Terracotta**   | `#C76D4B` | Primary CTA / Accent   |
| **Muted Gold**   | `#D5AE72` | Secondary Highlight    |
| **Dark Text**    | `#202923` | Primary Typography     |
| **Muted Text**   | `#777F78` | Secondary Typography   |

### Typography

- **Headings:** Playfair Display (Google Fonts)
- **Body:** Inter (Google Fonts)
- **Bangla UI:** Hind Siliguri / Noto Sans Bengali (Google Fonts)

---

## 🛠️ Tech Stack

- **Markup:** HTML5 (Semantic)
- **Styling:** Tailwind CSS (CDN) + Custom CSS Variables
- **Logic:** Vanilla JavaScript (ES6+)
- **Icons:** Lucide Icons / Font Awesome
- **Fonts:** Google Fonts
- **Hosting:** GitHub Pages (No Node.js, bundlers, or backend required)

---

## 📂 Project Structure

```text
brew-and-bite/
├── index.html          # Complete self-contained application (HTML, CSS, JS)
├── README.md           # Project documentation
└── screenshots/        # (Optional) Preview images for documentation
```

---

## 🚀 Getting Started

### Run Locally

1. Clone the repository:
   ```bash
   git clone [https://github.com/your-username/brew-and-bite.git](https://github.com/your-username/brew-and-bite.git)
   ```
2. Navigate to the project folder:
   ```bash
   cd brew-and-bite
   ```
3. Open `index.html` directly in any modern web browser (Chrome, Edge, Firefox, Safari) — no installation or build step needed.

### Deploy on GitHub Pages

1. Push your project files (`index.html` and `README.md`) to a public GitHub repository.
2. Go to your repository **Settings** → **Pages**.
3. Under **Build and deployment**, set **Source** to `Deploy from a branch`.
4. Select the `main` branch and `/ (root)` folder, then click **Save**.
5. Wait 1–2 minutes and access your live site at `https://<your-username>.github.io/<repository-name>/`.

---

## ⚠️ Disclaimer & Payment Limitation

- **Fictional Brand:** _BREW & BITE_ is a fictional demo restaurant created for an educational course mission. All menu prices, offers, business hours, contact details, and customer testimonials are demonstration content and do not represent a real business.
- **Simulated Payments Only:** This is a static frontend-only project with no backend server or live payment gateway. **bKash, Nagad, and Card** options are UI simulations only—no real transactions are processed, and no sensitive payment credentials are collected or stored. Real payment processing requires secure server-side integration with official payment gateway APIs.

---

## 👤 Author

**Your Name**

- GitHub: [@your-username](https://github.com/your-username)
- Location: Dhaka, Bangladesh

---

⭐ _If you found this project helpful or inspiring, feel free to give it a star!_
