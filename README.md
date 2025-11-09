# 🌸 Event Calendar (Java, JSP, Servlets & MySQL)

A modern, interactive **Event Calendar Web Application** built using **Java, JSP, Servlets, and MySQL**, featuring a glowing pink–purple UI theme with smooth animations and elegant design.

---

## 💡 Project Overview

The **Event Calendar** helps users plan and manage upcoming events through a beautiful, easy-to-use interface.

**Users can:**
- Add a new event (Title, Description, Date)
- View all events in a clean, interactive table
- Access a vibrant, glowing web design that feels modern and smooth

---

## 🧩 Technologies Used

| Component | Technology |
|------------|-------------|
| Frontend | HTML, CSS, JSP (Glassmorphism UI) |
| Backend | Java Servlets, JDBC |
| Database | MySQL |
| Server | Apache Tomcat |
| IDE | Eclipse |
| JAR | `mysql-connector-j-8.x.jar` |

---

## ⚙️ Setup Instructions

### 1️⃣ Create Database

Run this SQL script in MySQL:

```sql
CREATE DATABASE event_calendar_db;
USE event_calendar_db;

CREATE TABLE events (
    id INT AUTO_INCREMENT PRIMARY KEY,
    title VARCHAR(100) NOT NULL,
    description TEXT NOT NULL,
    event_date DATE NOT NULL
);
EventCalendar/
│
├── src/
│   ├── main/java/com/calendar/controller/
│   ├── main/java/com/calendar/dao/
│   ├── main/java/com/calendar/model/
│
├── webapp/ or WebContent/
│   ├── index.jsp
│   ├── view_calendar.jsp
│   ├── add_event.jsp
│   └── WEB-INF/
│       └── web.xml
│
├── Screenshots/
│   ├── Screenshot 2025-11-08 131329.png
│   ├── Screenshot 2025-11-08 131340.png
│   └── Screenshot 2025-11-08 131754.png
│
├── README.md
└── pom.xml / .classpath / .project


## 🖼️ Screenshots

### 🏠 Home Page
<img src="Screenshot 2025-11-08 131329.png" alt="Home Page" width="800"/>

---

### ➕ Add Event Page
<img src="Screenshot 2025-11-08 131340.png" alt="Add Event" width="800"/>

---

### 📅 View Calendar Page
<img src="Screenshot 2025-11-08 131754.png" alt="View Calendar" width="800"/>



