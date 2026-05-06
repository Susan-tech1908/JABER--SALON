# 💇‍♀️ Jaber Salon Website

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://html5.org/)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://css3.com/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://javascript.com/)
[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222222?style=for-the-badge&logo=githubpages&logoColor=white)](https://pages.github.com/)

> **Live Website:** [Visit Jaber Salon](https://YOUR_USERNAME.github.io/jaber-salon)  
> **Status:** ✅ Live & Responsive

---

## 📌 Project Overview

A modern, fully responsive one-page business website for **Jaber Salon** - a professional hairstyling salon based in Nairobi, Kenya. The salon specializes in braids, cornrows, threading, twists, and all creative hairstyles.

This website serves as a digital storefront, allowing customers to:
- Browse available hairstyling services
- Learn about the salon's expertise
- Book appointments instantly via WhatsApp
- Connect through social media platforms

---

## ✨ Features

### 📱 **Responsive Design**
- Mobile-first approach with breakpoints at 850px and 550px
- Smooth navigation across all devices (desktop, tablet, mobile)
- Touch-friendly buttons and interactive elements

### 💬 **WhatsApp Booking Integration**
- Multiple strategically placed CTA buttons throughout the site
- Pre-filled message templates for different user intents
- One-click booking directly to WhatsApp Business

### 🎨 **Modern UI/UX**
- Gradient hero banner matching brand identity
- Smooth scrolling navigation
- Hover animations on all interactive elements
- Fixed WhatsApp float button for quick access

### 📋 **Dynamic Service Catalog**
- Service cards rendered via JavaScript
- Easy to update without modifying HTML structure
- Visual icons for each hairstyle category

### 🔗 **Social Media Integration**
- Instagram, Facebook, TikTok, and WhatsApp links
- Social icons open in new tabs
- Consistent brand presence across platforms

### 🔍 **SEO Optimized**
- Meta descriptions and keywords
- Semantic HTML structure
- Open Graph tags for social sharing
- Clean URL structure

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| **HTML5** | Semantic document structure |
| **CSS3** | Styling, animations, responsive layouts |
| **Vanilla JavaScript** | Interactive elements, WhatsApp integration, dynamic content |
| **Font Awesome 6** | Icon library for social media and UI elements |
| **Google Fonts (Inter)** | Modern, clean typography |

**No frameworks, no dependencies, no build process!** 🎉

---

## 📂 Project Structure
Jaber Salon
├── index.html # Main website file (all-in-one)
├── README.md # Project documentation
└── assets/ (optional) # Images, logos, favicons

text

> **Note:** This is a single-file website - everything (HTML, CSS, JS) is contained in `index.html` for simplicity.

---

## 🚀 Live Demo

**View the live website:** [https://YOUR_USERNAME.github.io/jaber-salon](https://YOUR_USERNAME.github.io/jaber-salon)

---

## 💻 Local Development

### To run this project locally:

**Option 1: Direct Open**
```bash
# Simply double-click the index.html file in your browser
Option 2: Using Live Server (Recommended)

bash
# Using VS Code Live Server extension
Right-click index.html → Open with Live Server

# Or using Python
python -m http.server 8000

# Or using Node.js
npx live-server
🔧 Customization Guide
Update WhatsApp Number
Find this line in index.html (around line 550):

javascript
const WA_PHONE = "254725773725";  // Change to your number
Format rules: Country code without '+' or spaces
✅ 254700000000
❌ +254700000000 

Update Social Media Links
Find the social links section in HTML:

html
<div class="social-links">
  <a href="https://www.instagram.com/YOUR_USERNAME" target="_blank">
    <i class="fab fa-instagram"></i>
  </a>
  <a href="https://www.tiktok.com/@YOUR_USERNAME" target="_blank">
    <i class="fab fa-tiktok"></i>
  </a>
  <a href="https://www.facebook.com/YOUR_PAGE" target="_blank">
    <i class="fab fa-facebook-f"></i>
  </a>
</div>
Update Services
Modify the servicesData array in JavaScript:

javascript
const servicesData = [
  { name: "Box Braids", desc: "Description here", icon: "fas fa-grip-lines" },
  // Add or remove services as needed
];
Update Contact Information
Find the contact section in HTML:

html
<div class="contact-item">
  <i class="fas fa-phone-alt"></i> <span>+254 725 773 725</span>
</div>
<div class="contact-item">
  <i class="fas fa-map-marker-alt"></i> <span>Your location here</span>
</div>
Update Colors
Modify CSS variables (find these in the style section):

css
:root {
  --primary: #b45f2b;
  --secondary: #e08e3a;
  --whatsapp: #25D366;
}

