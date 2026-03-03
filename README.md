# Bakzy Restaurant Web App 🍽️

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-2.3-lightgrey?logo=flask&logoColor=black)
![MongoDB](https://img.shields.io/badge/MongoDB-6.0-green?logo=mongodb&logoColor=white)
![Cloudinary](https://img.shields.io/badge/Cloudinary-1DA1F2?logo=cloudinary&logoColor=white)

A simple web application for a restaurant where users can view menu items, categories, and gallery images. Admins can manage menu items, categories, gallery images, and view contact messages. Built with **Flask**, **MongoDB**, and **Cloudinary** for image storage.

---

## Features ✅

### Public Features
- View **menu items** with images, sizes, and prices.
- View **categories** and gallery images.
- Contact form to send messages to the restaurant.

### Admin Features
- **Admin login/logout** system.
- Add, edit, and delete **menu items** with images and sizes.
- Add, edit, and delete **categories** with images.
- Add, edit, and delete **gallery images**.
- View **contact messages** sent by users.
- Images are stored securely on **Cloudinary**.

---

## Technologies Used 🛠️
- **Backend:** Python, Flask  
- **Database:** MongoDB  
- **Image Hosting:** Cloudinary  
- **Frontend:** HTML, CSS, Jinja2 templates  

---

## Admin Login 🛡️
- Username: `admin`  
- Password: `admin`  

You can change these in `main.py` if needed.

---

## Folder Structure 📁
```
├── main.py # Main Flask app
├── templates/ # HTML templates
├── static/ # CSS, JS, and images
├── .env # Environment variables
└── requirements.txt # Python dependencies
```

---

## Notes 📝
- Only images with extensions `png, jpg, jpeg, webp, gif` are allowed.
- Make sure your MongoDB URI and Cloudinary credentials are correct.
- For production, set `debug=False` in `main.py`.
- Uses `flash` messages for success/error notifications.

---
