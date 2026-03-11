# 🏨 Hotel Royal Stay - Luxury Hotel Management Website

![Hotel Royal Stay](https://img.shields.io/badge/Version-1.0.0-gold?style=for-the-badge)
![Status-Active](https://img.shields.io/badge/Status-Active-green?style=for-the-badge)
![Rating-⭐⭐⭐](https://img.shields.io/badge/Rating-3%20Star-yellow?style=for-the-badge)

> **"Feel the Class & Feel the Comfort"**

Welcome to **Hotel Royal Stay** - A comprehensive luxury hotel management website featuring room bookings, restaurant services, premium bar, and event hall/lawn bookings with modern UI/UX and full-featured functionality.

---

## 📋 Table of Contents

- [Project Overview](#project-overview)
- [Key Features](#key-features)
- [Technology Stack](#technology-stack)
- [Project Structure](#project-structure)
- [Pages Overview](#pages-overview)
- [Getting Started](#getting-started)
- [User Guide](#user-guide)
- [Payment Integration](#payment-integration)
- [Admin Panel](#admin-panel)
- [Screenshots](#screenshots)
- [Future Enhancements](#future-enhancements)
- [Credits](#credits)
- [License](#license)

---

## 🎯 Project Overview

**Hotel Royal Stay** is a full-featured 3-star luxury hotel website located in Kolhapur, Maharashtra, India. The website provides a complete digital solution for hotel management including:

- 🏠 Luxury Room Booking with 360° Virtual Tours
- 🍽️ Online Restaurant Ordering with PDF Receipts
- 🍸 Premium Bar Services with Live DJ Nights
- 🎉 Event Hall & Lawn Bookings (Weddings, Parties, Conferences)
- 💬 24/7 Live Chat Support
- 👤 User Authentication System
- 📱 Mobile-Responsive Design

---

## ✨ Key Features

### 1. Room Booking System
- Three room categories: Deluxe AC, Executive Suite, Royal Premium Suite
- Real-time price calculation with night count
- **360° Virtual Room View** using Three.js
- Check-in/Check-out date selection
- Advance payment options
- Automatic bill generation with GST

### 2. Restaurant Services
- Complete food menu with 25+ dishes
- Indian, Chinese, Italian, and Continental cuisine
- Real-time cart management
- Multiple quantity selection
- **Digital Bill Generation** with jsPDF
- Payment via UPI, Card, or Net Banking

### 3. Premium Bar
- Live DJ Night events
- Premium drinks collection (Wine, Whiskey, Vodka, Beer, Cocktails)
- Soft Music Lounge
- 24/7 Service
- Happy Hours offers (Buy 2 Get 1 Free)
- QR Code Payment via PhonePe

### 4. Hall & Lawn Booking
- Grand Wedding Hall, Conference Hall, Birthday Party Hall
- Royal Wedding Lawn, Reception Garden, Corporate Event Lawn
- Guest count management
- 30% Advance payment system
- Razorpay Integration
- Multi-page PDF receipts

### 5. User Authentication
- Registration with email validation
- Login/Logout functionality
- Profile management
- Order history tracking
- Local Storage persistence

### 6. Live Chat Support
- 24/7 automated customer support
- Multi-language support (English, Hindi, Marathi)
- Quick reply buttons
- Chat history storage

### 7. Additional Features
- Floating Call & Map buttons
- Offer notifications
- Special promotions (40% cashback on early booking)
- Social media integration
- Responsive design for all devices

---

## 🛠 Technology Stack

| Category | Technology |
|----------|------------|
| **Frontend** | HTML5, CSS3, JavaScript |
| **Frameworks** | Three.js (360° View), jspdf |
| **Payments** | Razorpay, PhonePe, UPI |
| **Fonts** | Google Fonts (Poppins, Cinzel) |
| **Icons** | Font Awesome 6.4.0 |
| **Storage** | LocalStorage (Browser) |
| **Design** | Custom CSS with Gradients & Animations |

---

## 📁 Project Structure

```
RS_hotel_project/
│
├── 📄 HTML Files
│   ├── index.html              # Main landing page (old version)
│   ├── homepage.html           # Main homepage (new version)
│   ├── home.html               # Alternative home page
│   ├── restaurant.html         # Restaurant & Food ordering
│   ├── h_lodge.html            # Room booking & Lodging
│   ├── h_bar.html              # Bar services
│   ├── h_hall.html             # Hall & Lawn (alternative)
│   ├── hall&lawn.html          # Hall & Lawn booking (main)
│   └── booking.html            # Booking page
│
├── 🖼️ Image Files
│   ├── Food Images
│   │   ├── Butter Chicken.jpg
│   │   ├── Paneer Butter Masala.jpg
│   │   ├── Veg Biryani.jpg
│   │   ├── Chicken Biryani.jpg
│   │   ├── Margherita Pizza.jpg
│   │   └── ... (25+ food images)
│   │
│   ├── Bar Images
│   │   ├── barhd.jpg, barhd2.jpg, barhd5.jpg, barhd6.jpg
│   │   ├── s1_bar.jpg - s5_bar.jpg
│   │   ├── Beer.jpg, Vodka.jpg, Whiskey.jpg
│   │   └── Champagne.jpg, Cocktail Special.jpg
│   │
│   ├── Room/Hall Images
│   │   ├── h_hall.jpg, h_hall2.jpg, h_hall3.jpg
│   │   ├── h_lawn1.jpg, h_lawn2.jpg
│   │   └── hall2.jpg, hall6.jpg
│   │
│   ├── Beverage Images
│   │   ├── cocacola.jpg, sprite.jpg
│   │   ├── thumbsup.jpg, maja.jpg
│   │   └── redwine.jpg
│   │
│   └── Event Images
│       ├── wed.jpg, wed2.jpg
│       ├── lawn7.jpg, lawn8.jpg
│       └── Aloo Gobi.jpg, Cheese Nachos.jpg
│
└── 📝 Documentation
    └── README.md               # This file
```

---

## 📱 Pages Overview

### 1. Homepage (`homepage.html`)
The main landing page featuring:
- Premium animated navbar with gold accents
- Hero section with background image
- "Book Now" section with 40% cashback offer
- Image sliders showcasing hotel facilities
- Live chat widget
- Floating call and map buttons
- Footer with contact info and social links

### 2. Restaurant (`restaurant.html`)
Online food ordering system:
- Grid-based menu display with images
- Add to cart functionality
- Real-time total calculation
- Payment mode selection
- PDF bill download
- Order confirmation

### 3. Lodging (`h_lodge.html`)
Room booking with virtual tours:
- Three room categories with pricing
- **360° Room View** (Three.js)
- Date and night selection
- PhonePe/UPI payment integration
- PDF receipt generation

### 4. Bar (`h_bar.html`)
Premium bar services:
- Live DJ Night, Soft Music Lounge
- Drink menu with prices
- Slider for bar ambiance
- Order management
- Happy Hours offers

### 5. Hall & Lawn (`hall&lawn.html`)
Event venue booking:
- Multiple hall and lawn options
- Price range: ₹15,000 - ₹90,000
- Guest count input
- Advance payment (30%) system
- Razorpay integration

### 6. Booking (`booking.html`)
Central booking portal:
- Room selection buttons
- Customer details form
- Date selection
- Payment processing
- Invoice generation

---

## 🚀 Getting Started

### Prerequisites
- Any modern web browser (Chrome, Firefox, Edge, Safari)
- Internet connection (for CDN resources)
- No server required - runs directly in browser

### Running the Project

1. **Clone/Download** the project files
2. **Navigate** to the project folder
3. **Open** `homepage.html` in your browser
4. **Explore** all features!

### For Local Development
```bash
# Using VS Code Live Server
# Or simply open the file directly in browser
index.html
# or
homepage.html
```

---

## 💳 Payment Integration

The website supports multiple payment methods:

| Payment Method | Status | Integration |
|----------------|--------|-------------|
| UPI | ✅ Active | PhonePe Modal |
| Credit/Debit Card | ✅ Active | Direct Processing |
| Net Banking | ✅ Active | Direct Processing |
| Razorpay | ✅ Active | Hall/Lawn Booking |
| PhonePe | ✅ Active | Room & Bar Booking |

> **Note**: Payment integrations are in test mode. Replace with actual API keys for production use.

---

## 👨‍💼 Admin Panel

Access admin features at:
- **Admin Page**: `h_admin.html`
- Features: Manage bookings, view all orders, customer database

---

## 📸 Screenshots

The website features:
- 🎨 Gold and dark gradient theme
- 📱 Fully responsive mobile design
- ✨ Smooth animations and transitions
- 🖼️ High-quality image galleries
- 💬 Interactive chat widget

---

## 🔮 Future Enhancements

Planned features for next version:
- [ ] Backend integration with database
- [ ] Real payment gateway integration
- [ ] Email notifications
- [ ] SMS alerts
- [ ] Room availability calendar
- [ ] Online check-in/check-out
- [ ] Loyalty points system
- [ ] Multi-language support
- [ ] PWA (Progressive Web App)
- [ ] Admin dashboard with analytics

---

## 🙏 Credits

### Development
- **Lead Developer**: Om Kandalkar
- **Contact**: +91 8275761213
- **Email**: hotelroyalstay@gmail.com

### Technologies Used
- [Three.js](https://threejs.org/) - 360° Virtual Tours
- [jsPDF](https://jspdf.github.io/) - PDF Generation
- [Font Awesome](https://fontawesome.com/) - Icons
- [Google Fonts](https://fonts.google.com/) - Typography
- [Unsplash](https://unsplash.com/) - Stock Images

### Hotel Information
- **Address**: MG Road, Kolhapur, Maharashtra
- **Contact**: +91 9876543210
- **Landline**: 020-24567890
- **Email**: hotelroyalstay@gmail.com

### Social Media
- 📸 [Instagram](https://www.instagram.com/om____1199)
- 📺 [YouTube](https://youtube.com/@omkandalkar326)
- 📘 [Facebook](https://www.facebook.com/)

---

## 📄 License

This project is for educational and demonstration purposes.

```
© 2026 Hotel Royal Stay | Luxury 3-Star Experience
All Rights Reserved.
```

---

## 🎉 Thank You!

Thank you for exploring **Hotel Royal Stay**! We hope this project showcases the complete hotel management solution with modern web technologies.

> *"Book Smart • Stay Royal"*

---

**Made with ❤️ for Hotel Industry Excellence**

