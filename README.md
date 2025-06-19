# 📸 Imaginary - Photography Contest Website

Welcome to **Imaginary** – a stylish, responsive web platform for hosting photography contests. Users can register, log in, and submit entries under various creative categories. This project is built with **HTML**, **CSS**, **JavaScript**, **PHP**, and **MySQL**.

## 🚀 Features

- 🖼️ Dynamic image slideshow on homepage
- 👥 User Authentication (Sign Up / Login)
- 📁 Photography contest entry form with image upload
- 🗃️ MySQL database integration (via PHP)
- 🎨 Modern UI with a purple-themed aesthetic
- 🔄 Responsive Design & Auto Slide Show
- ✨ Smooth UI animations & transitions

---

## 📁 Project Structure

imaginary/
│
├── index.html            # Main homepage
├── login.php             # Login form handling
├── signup.php            # Signup form handling
├── contest.php           # Photo submission form processing
├── db.php                # Database connection file
├── style.css             # Stylesheet
├── script.js             # JavaScript for UI interactivity
├── imaginary.sql         # Database dump (MySQL)
└── images/               # Image assets (add your slide/gallery images)

---

## 🧠 Database Structure (`imaginary.sql`)

- `users` table:
  - `id`, `fullname`, `email`, `password`, `created_at`
- `contest_entries` table:
  - `id`, `fullname`, `email`, `age`, `category`, `photo_path`, `description`, `submitted_at`

> **Note:** Make sure to import `imaginary.sql` into your MySQL server.

---

## 🛠️ Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/imaginary.git
   cd imaginary

2. **Set up the database**

   * Use tools like **phpMyAdmin** or MySQL CLI.
   * Import `imaginary.sql` to create the required tables.

3. **Configure the database**

   * Update your MySQL credentials in `db.php`.

4. **Run the project**

   * Place the project folder inside your XAMPP/LAMP/other PHP server `htdocs` directory.
   * Start Apache & MySQL.
   * Visit: `http://localhost/imaginary/index.html`
---

## 📸 Contest Categories

* Nature
* People & Portraits
* Abstract & Art
* Others

---

## 📞 Contact

* 📧 Email: imaginary@google.com

---

## ✅ License

This project is open-source and free to use for educational and personal projects. Attribution appreciated 💜
