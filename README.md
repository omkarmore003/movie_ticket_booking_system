# 🎟️ Movie Ticket Booking System

A full-featured PHP-based web application for booking and managing movie tickets. Users can view movie listings, book tickets, cancel reservations, and simulate payments. Ideal for learning how to build a dynamic website with backend integration using PHP and MySQL.

---

## 📌 Features

- 🔐 User authentication (login/logout)
- 🎬 Browse movies and events
- 📝 Book and cancel tickets
- 💳 Simulated payment process
- 📄 Dynamic movie sidebar and movie listings
- 📩 Contact form for feedback
- ⚙️ Admin and user modules (if applicable)
- 🧩 Modular code with separate files for header/footer/config

---

## 🛠️ Tech Stack

| Layer       | Technology               |
|-------------|---------------------------|
| Frontend    | HTML, CSS, Bootstrap      |
| Backend     | PHP                       |
| Database    | MySQL (via phpMyAdmin)    |
| Web Server  | Apache (via XAMPP/WAMP)   |

---

## 🗂️ Project Structure

```
movie_ticket_booking_system/
├── index.php               # Homepage
├── login.php               # User login
├── booking.php             # Ticket booking logic
├── cancel.php              # Ticket cancellation
├── complete_payment.php    # Simulated payment
├── config.php              # DB config
├── contact.php             # Contact form
├── header.php/footer.php   # Page layout
├── movies_events.php       # Movie listing page
├── movie_sidebar.php       # Sidebar filters
├── form.php, msgbox.php    # Supporting pages
├── php_errors.log          # Log file
├── php.ini                 # PHP config (if needed)
└── ... other components
```

---

## ⚙️ Installation Instructions

### 📦 Prerequisites
- [XAMPP](https://www.apachefriends.org/index.html) or WAMP
- PHP 7.x or later
- MySQL

### 🧑‍💻 Setup Steps

1. **Clone the Repository**
   ```bash
   git clone https://github.com/omkarmore003/movie_ticket_booking_system.git
   ```

2. **Move Project Folder**
   Move the folder to your server directory:
   ```
   C:\xampp\htdocs\movie_ticket_booking_system
   ```

3. **Start Apache & MySQL**
   Launch XAMPP Control Panel → Start **Apache** and **MySQL**

4. **Import Database**
   - Open [phpMyAdmin](http://localhost/phpmyadmin)
   - Create a database: `movie_db`
   - Import the SQL file (if provided) under the `Import` tab

5. **Configure Database in `config.php`**
   ```php
   $host = "localhost";
   $username = "root";
   $password = "";
   $database = "movie_db";
   ```

6. **Access the Web App**
   Open your browser and go to:
   ```
   http://localhost/movie_ticket_booking_system
   ```

---

## 🧠 Learning Outcomes

- Practical understanding of **session handling** in PHP
- Integrating **MySQL database** with PHP
- Creating **modular PHP components** (headers, footers)
- Handling **form submissions and validations**
- Simulating **payment and ticketing workflows**

---

## 📃 License

This project is open-source and free to use for learning or portfolio purposes.

---

## 🙋‍♂️ Author

**Omkar More**  
📌 [GitHub](https://github.com/omkarmore003)  
📧 moreomkar003@gmail.com  
📍 India

---


