# 🛒 E-Commerce Management System using Spring Boot

A full-stack **E-Commerce Web Application** built using **Spring Boot, JSP, Hibernate, Spring Security, and MySQL** following the MVC architecture pattern.

This project provides a complete online shopping platform with **Admin** and **Customer** modules including authentication, product management, category management, and customer operations.

---

# 🚀 Features

## 👤 Customer Module

* User Registration & Login
* Secure Authentication using Spring Security
* Browse Products
* View Product Details
* User Profile Management

## 🛠️ Admin Module

* Admin Dashboard
* Add / Update / Delete Products
* Manage Categories
* Manage Customers
* Role-Based Authorization

## 🔒 Security

* Spring Security Authentication
* Role-Based Access Control
* CSRF Protection Enabled

---

# 🧰 Tech Stack

| Technology      | Usage                          |
| --------------- | ------------------------------ |
| Java 11         | Backend Language               |
| Spring Boot     | Application Framework          |
| Spring MVC      | MVC Architecture               |
| Spring Security | Authentication & Authorization |
| Hibernate ORM   | Database Operations            |
| JSP + JSTL      | Frontend Views                 |
| MySQL           | Database                       |
| Maven           | Dependency Management          |

---

# 📁 Project Structure

```text
src/main/java/com/jtspringproject/JtSpringProject/
│
├── configuration/      # Security Configuration
├── controller/         # Controllers
├── dao/                # DAO Layer
├── models/             # Entity Classes
├── services/           # Business Logic
├── repository/         # Repository Layer
│
├── HibernateConfiguration.java
└── JtSpringProjectApplication.java

src/main/resources/
└── application.properties

src/main/webapp/views/
└── *.jsp
```

---

# ⚙️ Installation & Setup

## 1️⃣ Clone Repository

```bash
git clone https://github.com/Rakshitha-csbs/E-commerce-project_using-springboot.git
cd E-commerce-project_using-springboot
```

---

## 2️⃣ Configure Database

Update `application.properties`

```properties
db.driver=com.mysql.cj.jdbc.Driver
db.url=jdbc:mysql://localhost:3306/ecommjava?createDatabaseIfNotExist=true
db.username=root
db.password=your_password

hibernate.dialect=org.hibernate.dialect.MySQL5Dialect
hibernate.show_sql=true
hibernate.hbm2ddl.auto=update
```

---

## 3️⃣ Import Database

Run the SQL file:

```text
basedata.sql
```

inside MySQL Workbench or any MySQL client.

---

## 4️⃣ Run Application

```bash
mvn clean install
mvn spring-boot:run
```

Application will run on:

```text
http://localhost:8080/
```

---

# 🔑 Login Credentials

## Admin

```text
Username: admin
Password: admin
```

> Change default credentials before production deployment.

---

# 📌 Main Endpoints

## User Routes

```text
/
 /login
 /register
 /user/products
 /profileDisplay
```

## Admin Routes

```text
/admin/
/admin/Dashboard
/admin/products
/admin/categories
/admin/customers
```

---

# 🖼️ Screenshots

## Home Page

![Home](screenshots/home.png)

## Admin Dashboard

![Dashboard](screenshots/dashboard.png)

## Products Page

![Products](screenshots/products.png)

---

# 🧪 Build & Test

```bash
mvn clean verify
```

---

# 🚀 Future Enhancements

* Shopping Cart
* Online Payment Gateway
* Order Tracking
* Email Notifications
* REST API Integration
* Docker Deployment
* JWT Authentication

---

# 🤝 Contribution

Contributions are welcome.

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to GitHub
5. Open a Pull Request

---

# ⭐ Support

If you like this project, give it a ⭐ on GitHub.

---

# 📜 License

This project is developed for educational and learning purposes.

---

# 👩‍💻 Author

**Rakshitha Prabhu**

GitHub: https://github.com/Rakshitha-csbs
