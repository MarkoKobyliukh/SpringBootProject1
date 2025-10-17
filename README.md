# 🌍 Project 1

This is a simple **Spring Boot + Thymeleaf** web application created as part of a university project at **Vistula University**.  
It demonstrates how to build a basic Spring MVC controller, render dynamic HTML pages using Thymeleaf, and serve static files (like images) from the `/static` folder.

---

## 🚀 Features

- Displays a simple greeting message using Spring Boot and Thymeleaf
- Passes parameters through URL (`/greeting?name=Vistula`)
- Renders dynamic HTML templates with variables
- Serves static files (like images) directly from `/static`
- Uses modern Java (version 21) and Spring Boot (version 3.5.6)

---
### 📷 Screenshots

screenshots folder with different outputs of /greeting

---
## 🧩 Project Structure
src/
├─ main/
│ ├─ java/myproject/project_1/
│ │ ├─ Project1Application.java
│ │ └─ controller/HelloController.java
│ └─ resources/
│ ├─ static/
│ │ └─ Globe.png
│ ├─ templates/
│ │ └─ greeting.html
│ └─ application.properties
├─ pom.xml
├─ .gitignore
└─ README.md

---
## ⚙️ How to Run

### 1️⃣ Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/springboot-hello-vistula.git
cd springboot-hello-vistula
```
### 2️⃣ Run the application
If you are using IntelliJ IDEA, open the project and click Run ▶️ next to
Project1Application.java.

Or, from the terminal:
```bash
mvn spring-boot:run
```

### 3️⃣ Open in your browser
| Endpoint                 | Description                                             | Example                                                                                    |
| ------------------------ | ------------------------------------------------------- | ------------------------------------------------------------------------------------------ |
| `/`                      | Returns "Hello Vistula, in my first Spring controller." | [http://localhost:8080](http://localhost:8080)                                             |
| `/greeting?name=Vistula` | Displays a dynamic greeting page                        | [http://localhost:8080/greeting?name=Vistula](http://localhost:8080/greeting?name=Vistula) |
| `/Globe.png`             | Serves the static image                                 | [http://localhost:8080/Globe.png](http://localhost:8080/Globe.png)                         |

---
### 💬 Example Behavior

When visiting:

http://localhost:8080/greeting?name=Vistula


You’ll see:

Hello, Vistula!
Lorem ipsum dolor sit amet, consectetur adipiscing elit...


and an image loaded from the /static folder.

---
### 🧠 About the .gitignore

The .gitignore file ensures that unwanted or system-specific files don’t appear in your GitHub repository.
It currently excludes:

- Compiled code (/target/)
- IDE configuration files (.idea/, *.iml, .vscode/)
- Temporary build files
- Log and environment files

This keeps the repository clean and lightweight.

---
### 🧰 Technologies Used

- Java 21
- Spring Boot 3.5.6
- Thymeleaf (for dynamic HTML rendering)
- Maven (for dependency management)
- IntelliJ IDEA (recommended IDE)
- Git & GitHub (for version control)

---
### 🧑‍💻 Author

Marko Kobyliukh
Vistula University — Computer Engineering