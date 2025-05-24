<h1 align="center">Hi 👋, I'm Guillermo</h1>
<h3 align="center">A passionate web developer from Mexico 💥.</h3>

---

### About Me

As a dedicated **web developer**, I specialize in building robust and scalable applications. My primary expertise lies in **backend development** with **Java** and the powerful **Spring Boot** framework. I also possess a strong foundation in **frontend technologies**, including **CSS** for crafting appealing user interfaces and **JavaScript** for dynamic client-side logic. Additionally, I have some familiarity with **Python**, which broadens my capabilities in various software development contexts.

---

### My Current Focus

- 🔭 I’m currently working on: **My personal projects with Java and Spring Boot**, focusing on practical applications to solidify my skills.
- 🌱 I’m currently learning: **Spring Boot** (deepening my understanding), **Java 8** (mastering new features), **Object-Oriented Programming (OOP)** principles, and **Linux** for deployment and system administration.
- 💬 Ask me about: **Java 😎** – I'm always happy to discuss it!

---

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://linkedin.com/in/https://www.linkedin.com/in/guillermo-torres-041798190/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="https://www.linkedin.com/in/guillermo-torres-041798190/" height="30" width="40" /></a>
<a href="https://instagram.com/https://www.instagram.com/guillermo_wright23?igsh=mth1a2xkcm14ctdhnq==" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="https://www.instagram.com/guillermo_wright23?igsh=mth1a2xkcm14ctdhnq==" height="30" width="40" /></a>
</p>


<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://aws.amazon.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="aws" width="40" height="40"/> </a> <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://www.djangoproject.com/" target="_blank" rel="noreferrer"> <img src="https://cdn.worldvectorlogo.com/logos/django.svg" alt="django" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://golang.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/go/go-original.svg" alt="go" width="40" height="40"/> </a> <a href="https://www.java.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/> </a> <a href="https://www.linux.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/> </a> <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://nodejs.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/> </a> <a href="https://www.photoshop.com/en" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/photoshop/photoshop-line.svg" alt="photoshop" width="40" height="40"/> </a> <a href="https://postman.com" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" alt="postman" width="40" height="40"/> </a> <a href="https://spring.io/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/springio/springio-icon.svg" alt="spring" width="40" height="40"/> </a> </p>



### My Projects

Here are some of the projects I've been working on, showcasing my skills in Java, Spring Boot, and web development:

#### **crud-spring**
* **Description:** This project is a foundational example of a **CRUD (Create, Read, Update, Delete)** application built with **Java** and the **Spring Boot** framework. It demonstrates how to perform the four basic operations for managing data, typically interacting with a database. This type of project is essential for understanding how to build robust backend systems and RESTful APIs.
* **Technologies Used:** Java, Spring Boot, [You might want to add specific database used, e.g., H2, MySQL, PostgreSQL, and any frontend if applicable].
* **Features:**
    * **Create:** Functionality to add new data records.
    * **Read:** Ability to retrieve existing data records, either individually or as a list.
    * **Update:** Methods to modify or edit existing data.
    * **Delete:** Capability to remove data records from the system.
* **Status:** [e.g., In Progress, Completed, Looking for feedback]
* **Repository:** [https://github.com/Guillermocode23/crud-spring](https://github.com/Guillermocode23/crud-spring)

##### **Internal Structure of `src/main/java/com/memo/love`**

While I couldn't directly inspect the files in this specific directory, based on standard Spring Boot conventions for a CRUD application, the `com.memo.love` package likely contains the core components that implement the CRUD functionality for a particular entity (which could be named "love" or related to notes/relationships, given the package name). You'll typically find a layered architecture within this package:

* **Entity/Model:** This would be a Java class (e.g., `Love.java`) annotated with `@Entity`. It defines the structure of the data that's being managed, with fields representing the attributes (columns) in your database table.
* **Repository:** An interface (e.g., `LoveRepository.java`) that extends Spring Data JPA's `JpaRepository` or `CrudRepository`. This powerful component provides ready-to-use methods for interacting with the database, handling common operations like saving, finding, and deleting data without writing boilerplate code.
* **Service:** A class (e.g., `LoveService.java` or `LoveServiceImpl.java`) annotated with `@Service`. This layer contains the business logic of your application. It acts as an intermediary between the controller and the repository, performing operations like data validation, complex data manipulation, and transaction management.
* **Controller:** A REST Controller class (e.g., `LoveController.java`) annotated with `@RestController` or `@Controller`. This component handles incoming HTTP requests from clients. It defines the API endpoints (URLs) for each CRUD operation (e.g., for creating a new "love" record, retrieving all, updating one, or deleting one) and then calls the service layer to perform the necessary actions, finally returning the appropriate HTTP responses.

This layered approach ensures a clean separation of concerns, making the application easier to understand, maintain, and scale.

#### **crud_java**
* **Description:** This project is a Java application designed to process data from a text file and load it into a MySQL database. Specifically, it handles information related to products and suppliers, populating two database tables: **TB_PRODUCTO** (for products) and **TB_PROVEEDOR** (for suppliers). The program intelligently reads the input text file, extracts relevant data, and then inserts these records into the corresponding tables using SQL queries. A notable feature is its ability to check for the existence of a supplier; if a supplier from the file is not found in the database, a new record is automatically inserted into the `TB_PROVEEDOR` table.
* **Technologies Used:** Java, MySQL, Text File Processing, SQL Queries.
* **Features:**
    * **Text File Parsing:** Reads and extracts product and supplier data from a specified text file.
    * **Database Loading:** Inserts extracted product data into the `TB_PRODUCTO` table.
    * **Supplier Management:** Automatically inserts new supplier records into the `TB_PROVEEDOR` table if they do not already exist.
    * **Data Persistence:** Utilizes SQL queries to ensure data is correctly stored in the MySQL database.
* **Status:** [e.g., In Progress, Completed, Looking for feedback]
* **Repository:** [https://github.com/Guillermocode23/crud_java](https://github.com/Guillermocode23/crud_java)
---
⭐️ From [Guillermo]
