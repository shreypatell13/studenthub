# Web Development Frameworks (ITUE203) - Comprehensive Practical Index (1 to 14)
**Student Name:** Shrey Patel  
**Roll No:** 25CE090  
**Department:** Computer Engineering  
**Academic Year:** 2026-27 (Odd Semester 3)  
**Repository:** [https://github.com/shreypatell13/studenthub](https://github.com/shreypatell13/studenthub)

---

## 📌 Practical Mapping Table (Practicals 1 to 14)

| Practical No. | Topic & Objective | Core Technologies | Primary Files in `wdf_studenthub` |
| :---: | :--- | :--- | :--- |
| **Practical 1** | **HTML5 Fundamentals & Semantic Structure**<br>Document structure, text formatting, headings, lists, tables, media, and form elements. | HTML5 | `p1_html/index.html` |
| **Practical 2** | **CSS3 Styling, Selectors & Box Model**<br>Typography, colors, box model (margin, border, padding), flexbox layout, and pseudo-classes. | CSS3 | `p2_css/index.html`, `p2_css/styles.css` |
| **Practical 3** | **Responsive UI Design for StudentHub Portal**<br>Responsive multi-page layout using Flexbox, CSS Grid, media queries, and shared theme tokens. | HTML5, CSS3 | `theme.css`, `dashboard.html`, `dashboard.css`, `student.html`, `event.html`, `fee.html` |
| **Practical 4** | **DOM Manipulation & Event Handling**<br>Dynamic UI interactivity, event listeners, form submissions, and `localStorage` state management. | JavaScript (ES6), DOM API | `dashboard.js`, `student.js`, `login.js`, `theme.css` |
| **Practical 5** | **Form Validation & User Registration**<br>HTML5 constraint validation, custom regex matching, password confirmation, and alert handling. | HTML5 Forms, JS Validation | `register.html`, `register.css`, `register.js`, `login.html`, `login.js` |
| **Practical 6** | **Asynchronous Data Loading via Fetch API & JSON**<br>Decoupling presentation from data by dynamically loading and rendering JSON datasets. | JavaScript, Fetch API, JSON | `attendance.js` + `attendance.json`, `timetable.js` + `timetable.json`, `result.js` + `result.json`, `fee.js` + `fee.json` |
| **Practical 7** | **PHP Server-Side Form Handling & File Persistence**<br>Server-side POST processing, sanitization, CSV/JSON data appending, and record rendering. | PHP, Server-side I/O | `studenthub_php/php/p7/form.php`, `studenthub_php/php/p7/records.php` |
| **Practical 8** | **Database Connectivity via PHP Data Objects (PDO)**<br>Secure MySQL connection handling, error modes, and graceful connection testing. | PHP, MySQL, PDO | `studenthub_php/php/p8/test_connection.php`, `studenthub_php/php/includes/db.php` |
| **Practical 9** | **User Registration & Secure Password Hashing**<br>Prepared statements to prevent SQL injection and `password_hash()` (bcrypt) encryption. | PHP, PDO, MySQL | `studenthub_php/php/p9/register.php` |
| **Practical 10** | **Session-Based Authentication & Role-Based Access Control**<br>Session management (`session_start()`), credentials validation, and role-based portal routing. | PHP Sessions, RBAC | `studenthub_php/php/p10/login.php`, `studenthub_php/php/p10/logout.php`, `studenthub_php/php/p10/student_dashboard.php` |
| **Practical 11** | **Student Record CRUD Operations**<br>Full database CRUD pipeline: Create, Read with search filtering, Update details, and Delete records. | PHP, SQL CRUD, PDO | `studenthub_php/php/p11/students.php`, `studenthub_php/php/p11/student_form.php`, `studenthub_php/php/p11/student_delete.php` |
| **Practical 12** | **Event Management & Secure File Uploads**<br>File upload handling with MIME validation, size caps, safe unique renaming, and `.htaccess` protection. | PHP File Uploads, Security | `studenthub_php/php/p12/events.php`, `studenthub_php/php/p12/event_form.php`, `studenthub_php/php/p12/event_delete.php` |
| **Practical 13** | **Asynchronous AJAX Integration & RESTful JSON API**<br>Real-time frontend-to-backend communication via Fetch API and a modular PHP JSON endpoint. | AJAX, REST API, JSON, PHP | `studenthub_php/php/p13/api.php`, `studenthub_php/php/p13/events_ajax.php` |
| **Practical 14** | **Admin Analytics Dashboard & Security Audit Logging**<br>System metric aggregation (user counts, event numbers) and transactional event audit logs. | PHP, SQL Aggregates, Security | `studenthub_php/php/p14/dashboard.php`, `studenthub_php/php/p14/users.php`, `studenthub_php/php/p14/audit.php` |

---

## 🚀 How to Run the Project
1. **Frontend (Practicals 1 to 6)**:
   - Open any HTML file (e.g. `p1_html/index.html`, `p2_css/index.html`, or `dashboard.html`) directly in any web browser or via VS Code Live Server.
2. **Backend (Practicals 7 to 14)**:
   - Start Apache and MySQL using XAMPP or local PHP runtime.
   - Import the database schema from `studenthub_php/sql/studenthub.sql` into MySQL.
   - Run setup seeds: `php studenthub_php/php/setup/seed_users.php`.
   - Launch in browser: `http://localhost/wdf_studenthub/studenthub_php/php/index.php`.
