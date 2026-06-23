# E-Commerce Website - WordPress & WooCommerce

##  Student Information

| **Field** | **Details** |
|-----------|-------------|
| **Student Name** | Thomas Yorwatei |
| **Student ID** | 22067/2023 |
| **Course** | Ecommerce |
| **Semester** | Year 3 |
| **Instructor** | Eric Maniraguha |

---

##  Project Title

**E-Commerce Website Development using WordPress & WooCommerce**

---

##  Platform Used

| **Component** | **Technology** |
|---------------|----------------|
| **Local Server** | XAMPP (Apache + MySQL) |
| **CMS** | WordPress 6.x |
| **E-Commerce Plugin** | WooCommerce |
| **Theme** | [Your Theme Name] |
| **Language** | PHP, HTML, CSS, JavaScript |
| **Database** | MySQL |
| **Version Control** | Git & GitHub |

---

##  Features Implemented

###  Homepage
- Store name displayed prominently
- Welcome message and brand introduction
- Featured products section
- Navigation menu with all pages
- Hero/banner section

###  Product Page
- **5+ Products** with detailed information:
  - Premium Wireless Headphones - $89.99
  - Smart Fitness Watch - $149.99
  - Organic Cotton T-Shirt - $29.99
  - Ceramic Coffee Mug Set - $24.99
  - Wireless Bluetooth Speaker - $59.99
- Product images for each item
- Price display
- Product descriptions
- Add to cart buttons
- Product categories

###  About Page
- Store description
- Mission statement
- Store history
- Why choose us section
- Core values

###  Contact Page
- Contact form (using Contact Form 7)
- Email address
- Phone number
- Physical address
- Business hours

###  Cart Interaction
- Add to cart functionality
- View cart page
- Update quantities
- Remove items
- Cart total calculation
- Proceed to checkout

###  Additional Features
- Responsive design (mobile-friendly)
- User-friendly navigation
- Professional appearance with [Theme Name]
- WordPress backend management
- WooCommerce integration

---

##  Screenshots

### Homepage
![Homepage](images/homepage.png)
*E-commerce homepage with welcome message and featured products*

### Product Page
![Product Page](images/product-page.png)
*Product listing page showing 5+ products with images, prices, and descriptions*

### Product Details
![Product Details](images/product-details.png)
*Individual product page with detailed information and add-to-cart*

### About Page
![About Page](images/about-page.png)
*About page with store description and mission*

### Contact Page
![Contact Page](images/contact-page.png)
*Contact page with form, email, phone, and address*

### Cart Page
![Cart Page](images/cart-page.png)
*Shopping cart with add-to-cart interaction and total calculation*

---

##  Repository Structure
ecommerce-website-wordpress/
│
├── README.md # Project documentation
├── images/ # Screenshots folder
│ ├── homepage.png
│ ├── product-page.png
│ ├── product-details.png
│ ├── about-page.png
│ ├── contact-page.png
│ └── cart-page.png
│
├── wp-content/
│ ├── themes/ # Custom theme files
│ ├── plugins/ # Installed plugins
│ └── uploads/ # Media uploads
│
└── wp-config.php # WordPress configuration

text

---

##  Live Website Link

**[View Live Website]((http://localhost/wordpress/))** *[Local Development Server]*

> **Note:** This project is currently running on a local XAMPP server. For production deployment, a live server link will be provided.

---

##  GitHub Repository

**[View Repository](https://github.com/thomasyorwatei/ecommerce-website-wordpress)**

---

##  Installation Instructions

### Prerequisites
- XAMPP (Apache, MySQL, PHP)
- Git (optional)
- Web browser

### Local Setup Steps

1. **Download and install XAMPP**
   ```bash
   # Download from: https://www.apachefriends.org/
  Start XAMPP services

bash
- Start Apache
- Start MySQL
Download WordPress

bash
# From: https://wordpress.org/download/
Extract to XAMPP htdocs

bash
# Extract to: C:\xampp\htdocs\wordpress\
Create database

sql
-- In phpMyAdmin
CREATE DATABASE wordpress_db;
Configure wp-config.php

php
define( 'DB_NAME', 'wordpress_db' );
define( 'DB_USER', 'root' );
define( 'DB_PASSWORD', '' );
define( 'DB_HOST', 'localhost' );
Install WordPress

bash
# Visit: http://localhost/wordpress
# Follow installation wizard
Install required plugins

bash
- WooCommerce
- Contact Form 7
- [Your theme's recommended plugins]
Activate the theme

bash
# Appearance → Themes → Activate [Your Theme Name]
