# AURA | The Ultimate Digital Creator Kit

[Aura Creator Kit]

> **Stop paying monthly fees. Own your platform.**
> A complete, self-hosted website template for creators, influencers, and digital artists.

---

## ⚡ Quick Start

**No installation required.** Aura is built with modern web technologies that run directly in your browser.

1.  **Unzip** the downloaded folder.
2.  **Double-click** `index.html` to open it in your browser.
3.  **Open** the folder in a code editor (like [VS Code](https://code.visualstudio.com/)) to start editing.

---

## 📦 What's Included?

Your download includes 9 premium, responsive pages:

* `index.html` - **Homepage:** High-impact "Bento Grid" portfolio.
* `about.html` - **About:** Your journey, timeline, and FAQ.
* `services.html` - **Services:** Sell coaching, consulting, or freelance work.
* `shop.html` - **Shop:** E-commerce grid with instant category filtering.
* `product-detail.html` - **Product:** High-conversion sales page with sticky details.
* `media-kit.html` - **Media Kit:** Live stats page that prints perfectly to PDF (`Ctrl+P`).
* `contact.html` - **Contact:** Professional inquiry form with validation.
* `links.html` - **Link Hub:** Mobile-first "Link-in-Bio" page (replace Linktree).
* `kit.html` - **Gear Kit:** Show off your equipment or setup.

---

## 🎨 Customization Guide

### 1. Changing Colors & Fonts
Open any HTML file and look for the `<script>` tag inside the `<head>` section:

```javascript
tailwind.config = {
    darkMode: 'class',
    theme: {
        extend: {
            colors: {
                brand: {
                    400: '#22D3EE', // Change this HEX code for primary Light color
                    500: '#4F46E5', // Change this HEX code for primary Brand color
                    600: '#4338CA', // Change this HEX code for Darker hover states
                },
                // ...
            }
        }
    }
}