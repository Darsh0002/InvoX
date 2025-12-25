# InvoX | Full-Stack Invoice Management System

InvoX is a professional invoice generation and management platform designed to streamline billing workflows. It allows users to create, manage, and track invoices with automated tax calculations and professional PDF exports.

**[🔗 View Live Demo]([INSERT_LINK_HERE])** | **[🔗 Backend Repository]([INSERT_LINK_HERE])**

---

## 🚀 Key Features

* **Dynamic Invoice Builder:** Real-time subtotal, tax, and discount calculations.
* **PDF Generation:** One-click export of professional, print-ready invoices.
* **Dashboard Analytics:** Visual tracking of total revenue and pending payments.
* **Client Management:** Integrated directory to manage client contact details and history.
* **Secure Authentication:** User registration and login powered by JWT (JSON Web Tokens).
* **Responsive Design:** Fully optimized for mobile, tablet, and desktop views.

---

## 🛠️ Tech Stack

### Frontend
* **Framework:** React.js
* **Styling:** Tailwind CSS
* **Icons:** Lucide React
* **State Management:** React Context API / Hooks

### Backend
* **Framework:** Spring Boot (Java)
* **Security:** Spring Security & JWT
* **Database:** PostgreSQL / MySQL (JPA/Hibernate)
* **Documentation:** Swagger / OpenAPI

---

## 📸 Screenshots

| Dashboard | Invoice Editor |
| :--- | :--- |
| ![Dashboard](https://via.placeholder.com/600x300?text=Dashboard+View) | ![Editor](https://via.placeholder.com/600x300?text=Invoice+Editor) |

---

## ⚙️ Installation & Setup

### 1. Backend Setup (Spring Boot)
1. Navigate to the backend directory.
2. Update `src/main/resources/application.properties` with your database credentials.
3. Run the application:
   ```bash
   mvn clean install
   mvn spring-boot:run
