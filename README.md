

# ✅ Tested Spring Boot Product API

This project is a simple **Product CRUD REST API** built using **Spring Boot**. It includes **unit tests**, **integration tests**, and **test coverage analysis** using **JaCoCo**.
The core code for this project (without the testing code ) is in a seperate repository.
---

## 🔌 API Endpoints

| Method | Endpoint                          | Description         |
|--------|-----------------------------------|---------------------|
| GET    | `/get products`                   | Get all products    |
| GET    | `/get products/{prodid}`          | Get product by ID   |
| POST   | `/get products`                   | Add a product       |
| PUT    | `/update products`                | Update a product    |
| DELETE | `/get products/delete/{prodid}`   | Delete a product    |

---

## 🛠 Tech Stack

- **Java 21**
- **Spring Boot 3.5.0**
- **Spring Data JPA**
- **H2 (In-memory database)**
- **JUnit 5**
- **Mockito**
- **MockMvc**
- **Maven**
- **JaCoCo** (for code coverage)

---

## 🚀 How to Run the Application

### 🔧 Start the Server

```bash
mvn spring-boot:run
````

### 🧪 How to Run Tests

```bash
mvn clean test
```

### 📈 Generate Test Coverage Report

```bash
mvn clean verify
```

Then open the following file in your browser:

```
target/site/jacoco/index.html
```

---

## 📊 Test Coverage

✅ The project is covered with both unit and integration tests using **JUnit**, **Mockito**, and **MockMvc**.





```
![JaCoCo Report](screenshots/jacoco-report.png)
```
![image](https://github.com/user-attachments/assets/120e1edc-b666-4038-a825-8bbaf83582fe)

---

## 📦 Notes

* The API is self-contained and uses an H2 in-memory database, so **no external setup** is needed.
* You can test it using tools like **Postman** or **curl**.
* For H2 console and DB configurations, edit `application.properties`.

---

## 📁 Project Structure

```
├── controller/
├── model/
├── repository/
├── service/
├── test/
├── ProductApplication.java
├── pom.xml
└── README.md
```

---

## 👨‍💻 Author

**Anshumaan Rath**

GitHub: [AnshumaanRath](https://github.com/AnshumaanRath)

```

Let me know if you'd like me to:
- Generate a sample `jacoco-report.png`.
- Create a downloadable ZIP with the above `README.md` file and a sample folder structure.
```
