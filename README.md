# Online Movie Ticket Booking System

🎥 **Online Movie Ticket Booking System** 🍿

Welcome to the Online Movie Ticket Booking System repository. This project leverages modern web technologies to create a seamless and user-friendly experience for booking movie tickets online.

---

## ✨ Key Features:

- **Modern UI:**
  - Developed using HTML, Bootstrap, and CSS for a visually appealing and responsive design.

- **Advanced Search & Filters:**
  - Dynamic search and filter functionality powered by AJAX to enhance user experience.

- **Integrated Payment Gateway:**
  - Razorpay integration for secure and efficient payment processing.

- **Email Notifications:**
  - SMTP mailer configured in PHP for sending instant emails for ticket bookings and newsletter subscriptions.

- **Robust Backend:**
  - Backend infrastructure built using PHP and MySQL, hosted on an Apache server.

---

## 🛠️ Technologies Used:

- **Frontend:** HTML, CSS, Bootstrap
- **Backend:** PHP, Apache Server
- **Database:** MySQL
- **Other Tools:** AJAX, Razorpay, SMTP mailer

---

## 📂 Getting Started

### Prerequisites

- Install [XAMPP](https://www.apachefriends.org/index.html) or any similar server to host the backend.
- Clone this repository to your local machine.

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/AyushKumar-Codes/Movie-Booking-System.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Movie-Booking-System
   ```

3. Start your Apache Server and MySQL Database.

4. Import the database:
   - Open `phpMyAdmin`.
   - Create a new database (e.g., `movie_booking_system`).
   - Import the SQL file provided in the repository (`database.sql`).

5. Configure database credentials in `config.php`:
   ```php
   define('DB_SERVER', 'localhost');
   define('DB_USERNAME', 'root');
   define('DB_PASSWORD', '');
   define('DB_DATABASE', 'movie_booking_system');
   ```

6. Run the application:
   - Open your browser and navigate to:
     ```
     http://localhost/Movie-Booking-System
     ```

---

## 🤝 Contributing

Contributions are welcome! If you'd like to contribute to this project:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a Pull Request.

---

## 📧 Contact

For any questions or feedback, feel free to contact me via this repository. 

---

### 📜 License

This project is licensed under the MIT License - see the LICENSE file for details.

