# 📚 Literalura

Literalura is a **Spring Boot application** that consumes the **Gutendex API** to search for books and store them in a **PostgreSQL database** using **Spring Data JPA and Hibernate**.

This project was developed as part of the **Alura Java Challenge**.

---

# 🚀 Features

The application allows users to:

* 🔎 Search books by title using the Gutendex API
* 💾 Save books and authors into a PostgreSQL database
* 📚 List all registered books
* 👨‍💼 List all registered authors
* 📅 List authors alive in a specific year
* 🌍 List books by language

---

# 🧠 Technologies Used

* Java 17+
* Spring Boot
* Spring Data JPA
* Hibernate
* PostgreSQL
* Maven
* Gutendex API

---

# 🌐 API Used

This project uses the public API:

https://gutendex.com

Gutendex provides metadata for more than **70,000 books from Project Gutenberg**.

---

# ⚙️ How to Run the Project

### 1️⃣ Clone the repository

```bash
git clone https://github.com/MashaDBDevep/literalura-springboot.git
```

### 2️⃣ Configure PostgreSQL

Edit the file:

```
src/main/resources/application.properties
```

Example configuration:

```
spring.datasource.url=jdbc:postgresql://localhost/literalura
spring.datasource.username=postgres
spring.datasource.password=yourpassword

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
```

---

### 3️⃣ Run the project

Using Maven:

```bash
mvn spring-boot:run
```

Or run the class:

```
LiteraturaApplication.java
```

---

# 📋 Application Menu

When running the application, you will see:

```
1 - Search book by title
2 - List registered books
3 - List registered authors
4 - List authors alive in a specific year
5 - List books by language
0 - Exit
```

---

# 🗄️ Database

Tables are created automatically by **Hibernate**.

Tables generated:

* `autores`
* `libros`

---

# 👨‍💻 Author

Developed by **MashaDBDevep**

Java + Spring Boot Challenge
