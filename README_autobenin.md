# AUTObenin 🚗

**AUTObenin** is a web-based vehicle rental platform built with PHP and MySQL. It allows users to browse available vehicles, place rental orders, and manage their bookings through an intuitive interface.

> 🚧 **Status: In development** — core modules implemented, deployment in progress.

---

## ✨ Features

- 🚘 **Vehicle Catalog** — Browse available vehicles with details (type, price, availability)
- 📋 **Order System** — Place, view, and manage rental orders
- ✅ **Order Validation Module** — Backend validation ensuring order integrity and business rules
- 👤 **User Authentication** — Register, login, and manage your account
- 🛠 **Admin Dashboard** — Manage vehicles, users, and orders

---

## 🛠 Tech Stack

| Layer | Technology |
|-------|-----------|
| Language | PHP |
| Database | MySQL |
| Frontend | HTML5, CSS3, JavaScript |
| Architecture | MVC |
| Server | Apache (XAMPP / WAMP) |

---

## 📁 Project Structure

```
autobenin/
├── index.php
├── config/
│   └── database.php
├── controllers/
│   ├── OrderController.php
│   └── VehicleController.php
├── models/
│   ├── Order.php
│   └── Vehicle.php
├── views/
│   ├── catalog.php
│   ├── order_form.php
│   └── dashboard.php
└── assets/
    ├── css/
    └── js/
```

---

## ⚙️ Order Validation Module

The order validation module (my core contribution) ensures:

- ✔️ All required fields are present and correctly formatted
- ✔️ Selected vehicle is available for the requested dates
- ✔️ No date conflicts with existing reservations
- ✔️ User eligibility checks before confirming a booking
- ✔️ Sanitized and secured inputs to prevent SQL injection

---

## 🚀 Getting Started

### Prerequisites

- PHP `>=7.4`
- MySQL `>=5.7`
- Apache server (XAMPP or WAMP recommended)

### Installation

```bash
# Clone the repository
git clone https://github.com/yx6p762vfy-cloud/autobenin.git

# Move to your local server directory
# e.g. htdocs/ for XAMPP or www/ for WAMP

# Import the database
# Open phpMyAdmin and import: database/autobenin.sql

# Configure your DB credentials
# Edit: config/database.php

# Launch your Apache server and visit:
# http://localhost/autobenin
```

---

## 📸 Screenshots

> Coming soon.

---

## 🗺 Roadmap

- [x] Vehicle catalog
- [x] Order form & validation module
- [x] User authentication
- [ ] Admin dashboard (in progress)
- [ ] Online payment integration
- [ ] Production deployment

---

## 👥 Team Project

This project was developed collaboratively. My responsibilities included designing and implementing the **order validation module** (backend logic, input checks, conflict detection).

---

## 👨‍💻 Author

**Steven HOUNGBO**
- GitHub: [@yx6p762vfy-cloud](https://github.com/yx6p762vfy-cloud)
- Portfolio: _coming soon_

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
