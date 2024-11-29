# ORM-Hibernate Project with Layered Architecture using JavaFX  

## 📖 Project Overview  
This project is a desktop application built with **JavaFX** and powered by **Hibernate ORM** to manage data persistence. It follows a **layered architecture** to separate concerns, making the codebase more maintainable and scalable.  

### ✨ Features  
- **Layered Architecture**: The project separates the application into three main layers:  
  - **UI Layer** (JavaFX): Handles user interaction and presentation.  
  - **Service Layer**: Contains business logic and intermediates between the UI and data layers.  
  - **Data Access Layer**: Manages database operations using Hibernate ORM.  
- **Database Persistence**: Uses Hibernate to map Java objects to database tables.  
- **Manage Entities**: Includes management of entities such as students, courses, coordinators, and payments.  
- **Custom Exception Handling** and Input Validation.  
- **Role Management** for different types of users (Admin/Coordinator).  
- **Encryption** of sensitive data.  

---

## 🛠️ Technologies Used  
- **JavaFX**: For the user interface.  
- **Hibernate**: For Object-Relational Mapping (ORM).  
- **MySQL**: As the relational database.  
- **Maven**: For dependency management.  
- **JFoenix**: For enhanced JavaFX controls.  

---

## 📂 Project Structure  

/orm-hibernate-javafx-project
├── /src
│ ├── /controller # JavaFX controllers
│ ├── /model # Hibernate entity classes
│ ├── /service # Business logic services
│ ├── /dao # Data access objects (DAOs)
│ └── /util # Utility classes (e.g., DB connection, encryption)
├── /resources
│ ├── /fxml # JavaFX FXML files
│ ├── /css # Stylesheets for UI
│ └── /images # Icons and images
├── pom.xml # Maven configuration
└── README.md # Documentation
