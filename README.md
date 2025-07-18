
# 🏛️ Club Inventory Management System

A web-based inventory management system designed to manage and track club items efficiently. Built as a **Database Project** using **HTML, CSS, JavaScript, PHP, MySQL**, and **XAMPP**.

---

## 📌 Features

🔐 **Role-Based Access Control**:

* **General Secretary (GS)** & **Deputy General Secretary (DGS)**:

  * Create, update, and **delete inventory items**
  * Add or remove inventory records
  * Manage executive access
* **Executives**:

  * **Allot inventory** to members
  * View current availability
  * Return / Update inventory status

🗃️ **Inventory Tracking**:

* Real-time tracking of inventory status (Available / Issued)
* Logs of allotments and returns

📊 **Dashboard View**:

* Summarized inventory stats
* User role-based options
* Filtered item search

---

## 🛠️ Tech Stack

| Technology | Purpose              |
| ---------- | -------------------- |
| HTML       | Frontend Structure   |
| CSS        | Styling and Layout   |
| JavaScript | Dynamic Interactions |
| PHP        | Backend Logic        |
| MySQL      | Database Management  |
| XAMPP      | Local Server Hosting |

---

## 🧑‍💼 User Roles

| Role                  | Permissions                              |
| --------------------- | ---------------------------------------- |
| General Secretary     | Create, Update, Delete Inventory         |
| Deputy Gen. Secretary | Same as GS                               |
| Executive             | Allot items to members, Return Inventory |

---

## 🚀 Getting Started

1. **Clone the Repository**

   ```bash
   git clone https://github.com/Niks6/Club-Inventory-Management-System.git
   ```

2. **Set Up XAMPP**

   * Start **Apache** and **MySQL**
   * Open **phpMyAdmin** at `http://localhost/phpmyadmin`

3. **Create the Database**

   * create the `club_inventory.sql` file according to your need into phpMyAdmin and update sql code in php files

4. **Run the Project**

   * Place the project folder inside `htdocs`
   * Access the app at `http://localhost/club-inventory-management`

---


## 📝 .gitignore

If you're using Git and want to avoid committing sensitive files, create a `.gitignore`:

```gitignore
/db/config.php
/node_modules/
*.log
*.env
.DS_Store
```

---

## 📬 Contact

For queries or suggestions, feel free to reach out:

* 📧 Email: [yourname@example.com](mailto:codeisforcoders@gmail.com)
* 💼 LinkedIn: [YourProfile](https://linkedin.com/in/nik-sh)

---

## ⭐ Acknowledgments

In this project i forgot to add the ER-Diagram so make your own database and just change the php's SQL code to work.

---

