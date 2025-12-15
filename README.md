
# E-Commerce Spring Boot

A backend **E-Commerce application** built with **Spring Boot** that provides REST APIs for typical online shopping features such as products, categories, cart, orders, and user interactions.  
This project demonstrates Spring Boot fundamentals, layered architecture, and CRUD operations for e-commerce entities.

---

## 🚀 Main Features

- Product listing and retrieval  
- Category management  
- Shopping cart operations  
- Order submission and tracking  
- RESTful APIs with JSON responses  
- Backend developed using Spring Boot

---

## 🛠️ Tech Stack

- **Java** (Spring Boot)  
- **Spring Web** (REST APIs)  
- **Spring Data JPA**  
- **Maven** (build tool)  
- **Embedded servlet container** (Tomcat)  
- **Database** (MySQL / H2 / any JDBC-compatible database)

---

## 🧱 Project Structure

```text
ecommerce_spring-boot/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/
│   │   │       └── example/
│   │   │           ├── controller/     # REST API controllers
│   │   │           ├── service/        # Business logic
│   │   │           ├── model/          # Entity & DTO classes
│   │   │           ├── repository/     # Data access interfaces
│   │   │           └── exception/      # Custom error handling
│   │   └── resources/
│   │       ├── application.properties  # Config file
│   │       └── static/                  # Static assets (if any)
├── .mvn/                                # Maven wrapper
├── mvnw
├── mvnw.cmd
├── pom.xml                              # Maven build config
└── README.md
````

---

## ⚙️ Setup & Run

### Prerequisites

* **Java JDK 8+**
* **Maven 3+**
* **Database** (optional; can use H2 for quick tests)

---

### Steps

1. **Clone the repo**

   ```bash
   git clone https://github.com/sindhu27b/ecommerce_spring-boot.git
   cd ecommerce_spring-boot
   ```

2. **Build the project**

   ```bash
   mvn clean install
   ```

3. **Run the application**

   ```bash
   mvn spring-boot:run
   ```

4. The app will start on **[http://localhost:8080](http://localhost:8080)** by default.




---

## 📌 Design Considerations

* Layered architecture (Controller → Service → Repository)
* Separation of concerns for clean maintainable code
* DTOs for request/response objects
* Custom error handling with meaningful exceptions

---

## 👨‍💻 Author

**Sindhuja Bollikonda**
GitHub: [https://github.com/sindhu27b](https://github.com/sindhu27b)

---



[1]: https://github.com/sindhu27b/ecommerce_spring-boot "GitHub - sindhu27b/ecommerce_spring-boot"
