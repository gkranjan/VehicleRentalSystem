# 🚗 Vehicle Rental Management System

## 📌 Project Overview

The **Vehicle Rental Management System** is a Java-based application developed to simplify and manage vehicle rental operations. The application provides a structured way to manage vehicles, customers, rental bookings, vehicle availability, and rental transactions.

The system is designed around real-world vehicle rental business requirements, where customers can rent available vehicles for a specific duration and return them after completing their rental period.

This project focuses on implementing Object-Oriented Programming (OOP) principles, modular programming, business logic, and Java exception handling to develop a maintainable and reusable application.

---

## 🎯 Project Objectives

- Develop a structured vehicle rental management application.
- Manage multiple vehicle categories.
- Maintain vehicle availability and rental status.
- Handle customer rental requests.
- Calculate rental charges based on rental duration.
- Manage vehicle booking and return operations.
- Implement real-world business logic using Java.
- Improve code reusability and maintainability.

---

## 🛠️ Technologies & Tools

| Technology | Purpose |
|---|---|
| Java | Core application development |
| Java 8 | Programming language features |
| Eclipse IDE | Development environment |
| Git | Version control |
| GitHub | Source code management |

---

## ⚙️ Core Modules

### 1. Vehicle Management
- Add and manage vehicle details.
- Maintain vehicle registration information.
- Support different vehicle categories.
- Track vehicle availability.

### 2. Customer Management
- Maintain customer information.
- Store customer details for rental operations.
- Associate rental records with customers.

### 3. Vehicle Rental Management
- Display available vehicles.
- Select a vehicle for rental.
- Validate vehicle availability.
- Process rental requests.
- Calculate rental charges.

### 4. Vehicle Return Management
- Process vehicle return requests.
- Update vehicle availability.
- Calculate final rental charges.
- Maintain rental transaction details.

### 5. Rental Calculation
- Calculate rental amounts based on the rental duration.
- Apply vehicle-specific rental rates.
- Generate rental cost details.

---

## 🔄 Application Workflow

The application follows this general business workflow:

1. Application starts.
2. Display the main menu.
3. Select the required operation.
4. Display available vehicles.
5. Enter customer and rental details.
6. Validate vehicle availability.
7. Process the rental request.
8. Calculate rental charges.
9. Complete the vehicle return process.
10. Update vehicle availability.
11. Display transaction details.
12. Exit the application.

---

## 🧠 Java Concepts Implemented

This project provides practical implementation of the following Java concepts:

| Java Concept | Application |
|---|---|
| Classes & Objects | Represent vehicles, customers, and rentals |
| Constructors | Initialize object data |
| Encapsulation | Protect vehicle and customer information |
| Inheritance | Reuse common vehicle properties |
| Polymorphism | Support different vehicle behaviors |
| Abstraction | Define common vehicle operations |
| Method Overloading | Support different method parameters |
| Exception Handling | Handle invalid operations and runtime exceptions |
| Collections Framework | Manage vehicle and rental records |
| Conditional Statements | Implement business decisions |
| Loops | Process repeated menu operations |

---

## 📂 Suggested Project Structure

```text
VehicleRentalSystem/
│
├── src/
│   └── com/
│       └── vehiclerental/
│           │
│           ├── main/
│           │   └── VehicleRentalApp.java
│           │
│           ├── model/
│           │   ├── Vehicle.java
│           │   ├── Car.java
│           │   ├── Bike.java
│           │   ├── Customer.java
│           │   └── Rental.java
│           │
│           ├── service/
│           │   ├── RentalService.java
│           │   └── VehicleService.java
│           │
│           ├── exception/
│           │   └── RentalException.java
│           │
│           └── util/
│               └── RentalCalculator.java
│
└── README.md
```

*Note: This is a suggested structure. Adjust it according to your actual project packages and classes.*

---

## 💡 Real-World Business Scenarios

The application demonstrates how a vehicle rental business can handle different situations:

- A customer requests a vehicle that is available.
- A customer attempts to rent an already rented vehicle.
- A customer returns a vehicle after the rental period.
- The system calculates rental charges.
- The system handles invalid customer or vehicle information.
- Vehicle availability changes after rental and return operations.

---

## 🚀 Future Enhancements

The project can be extended with additional enterprise-level features:

- Database integration using JDBC and MySQL.
- Customer registration and login.
- Admin dashboard for vehicle management.
- Date-based rental booking.
- Automated late-return penalty calculation.
- Payment gateway integration.
- Rental history and transaction reports.
- Spring Boot REST API development.
- Microservices-based architecture.
- Frontend integration using HTML, CSS, and JavaScript.

---

## 📈 Learning Outcomes

By developing this project, I gained practical experience in:

- Designing Java applications using OOP principles.
- Understanding real-world business requirements.
- Implementing reusable and modular code.
- Managing objects and application data.
- Handling exceptions and invalid user inputs.
- Understanding the relationship between different classes.
- Developing a foundation for enterprise Java applications.

---

## ▶️ How to Run the Project

1. Clone the repository:

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

2. Open Eclipse IDE.

3. Import the project:
   - File → Import
   - General → Existing Projects into Workspace
   - Select the project directory.

4. Configure the required Java version.

5. Locate the main application class.

6. Right-click and select **Run As → Java Application**.

---

## 👨‍💻 Author

**Gautam Kumar Ranjan**

Java Backend Developer

- GitHub: https://github.com/gkranjan
- LinkedIn: https://www.linkedin.com/in/gkranjan/

---

⭐ If you find this project useful, feel free to explore the source code and share your feedback.

**Built with Java | Focused on Object-Oriented Programming | Inspired by Real-World Applications**
