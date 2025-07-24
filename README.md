cat > README.md << EOF
# 🏥 Hospital Management System

A full-fledged **Hospital Management System** developed using modern **Frontend + Backend** technologies. This system helps manage hospital operations such as patient registration, doctor assignment, appointment scheduling, billing, and more.

---

## 📌 Features

- 🔐 User Authentication (Login/Register)
- 🧑‍⚕️ Doctor and Patient Profiles
- 📅 Appointment Booking & Management
- 📝 Patient Records and History Tracking
- 💳 Billing & Invoice Generation
- 📊 Admin Dashboard with Analytics
- 📁 Database Integration

---

## 🧰 Tech Stack

| Layer        | Technologies Used                       |
|--------------|------------------------------------------|
| 💻 Frontend  | HTML, CSS, JavaScript, Bootstrap         |
| ⚙️ Backend   | PHP                                      |
| 🗃️ Database | MySQL (via phpMyAdmin)                    |
| 🌐 Server    | Apache (XAMPP)                           |

---

## 🚀 How to Run Locally
1.Download and install XAMPP in your machine
2.Clone or download the repository
3.Extract all the files and move it to the 'htdocs' folder of your XAMPP directory.
4.Start the Apache and Mysql in your XAMPP control panel.
5.Open your web browser and type 'localhost/phpmyadmin'
6.In phpmyadmin page, create a new database from the left panel and name it as 'myhmsdb'
7.Import the file 'myhmsdb.sql' inside your newly created database and click ok.
8.Open a new tab and type 'localhost/foldername' in the url of your browser

## 📂 Folder Structure

\`\`\`
Hospital-Management-System/
│
├── css/
├── js/
├── images/
├── includes/
├── admin/
├── doctor/
├── patient/
├── db_config.php
├── index.php
└── ...
\`\`\`

---

## 🛡️ Security Notes

- Passwords are hashed before storing (optional improvement: use bcrypt).
- Validation is performed on inputs (client + server-side).
- Only authorized users can access specific roles.

---

## ✍️ Author

**Hemang Dubey**   
🔗 https://github.com/HemangDubey

