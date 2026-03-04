# Bakzy Restaurant Web App 🍰

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-2.3-lightgrey?logo=flask&logoColor=black)
![MongoDB](https://img.shields.io/badge/MongoDB-6.0-green?logo=mongodb&logoColor=white)
![Cloudinary](https://img.shields.io/badge/Cloudinary-1DA1F2?logo=cloudinary&logoColor=white)

A **modern, interactive web application for a bakery/restaurant** where users can browse menu items, filter by categories, select product sizes, manage quantities, and place orders via WhatsApp. Admins can manage products, categories, galleries, and view contact messages.  

---


## Features ✅

### Public Features
- **Menu Browsing**: View all items with images, category badges, and descriptions.
- **Category Tabs**: Filter products dynamically by category.
- **Size Options**: Choose product sizes, with dynamic price display.
- **Product Cards**: Hover effects, badges, zoom-in icons, and smooth UI animations.
- **Lightbox Preview**: Click an item to view a larger image with name and category.
- **Floating Cart Button**: Shows cart count and opens a cart drawer.
- **Cart Drawer**:
  - Increment/decrement item quantity.
  - Remove items individually or clear the entire cart.
  - Price calculation with subtotal and indication for “Price on request” items.
- **WhatsApp Ordering**: Orders (including enquire items) can be sent directly via WhatsApp with formatted messages.

### Admin Features
- **Admin Login/Logout**: Secured admin access.
- **Manage Products**:
  - Add, edit, delete products.
  - Upload multiple sizes per product with prices.
  - Add product images using Cloudinary.
- **Manage Categories**:
  - Add, edit, delete categories.
  - Assign products to categories.
- **Gallery Management**:
  - Add/edit/delete gallery images.
- **Contact Form Messages**: View messages sent by users.

---

## Technologies Used 🛠️
- **Backend:** Python, Flask  
- **Database:** MongoDB (for products, categories, and messages)  
- **Image Hosting:** Cloudinary (for product and gallery images)  
- **Frontend:** HTML, CSS, Jinja2, JavaScript (interactive UI, cart, lightbox)  
- **Fonts:** Playfair Display, Cormorant Garamond, DM Sans  

---

## Admin Login Credentials 🛡️
- Username: `admin`  
- Password: `admin`  

> Can be customized in `main.py`.

---

## Folder Structure 📁
```
├── main.py # Flask backend
├── templates/ # Jinja2 HTML templates (base.html, menu.html, etc.)
├── static/ # CSS, JS, fonts, and other assets
├── .env # Environment variables (MongoDB URI, Cloudinary keys)
└── requirements.txt # Python dependencies
```

---

## UX Highlights 🎨
- Smooth hover animations for product cards and images.
- Size and price selection dynamically updates the UI.
- Cart drawer with live total updates.
- Enquire button style for items without a set price.
- WhatsApp integration automatically formats orders.
- Responsive design for mobile and desktop screens.

---

## Notes 📝
- Only image types allowed: `png, jpg, jpeg, webp, gif`.
- Cart supports multiple items, quantities, and combinations of sizes.
- “Price on request” items handled gracefully in cart and WhatsApp order.
- Uses `flash` messages for success/error notifications (admin operations).
- For production, set `debug=False` in `main.py`.

