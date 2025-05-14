# 🚗 CAR RENTAL SYSTEM

Welcome to the **CAR RENTAL SYSTEM**! This project is a simple yet powerful demonstration of how **Object-Oriented Programming (OOP)** principles can be applied to solve real-world problems in software development. 

---

## 🌟 Key Features

- **🔐 User Management**: Supports multiple user types like customers and admins.
- **🚘 Vehicle Management**: Add, remove, and manage vehicles efficiently.
- **📅 Booking System**: Allows customers to book vehicles based on availability.
- **💾 Persistent Storage**: Keeps track of all bookings, users, and vehicles.

---

## 🧩 Core OOP Principles Used

### 1. **Encapsulation** 📦
   - Keeps data secure by restricting direct access to it through public methods.
   - Example: The vehicle class has private attributes for its details, accessed and modified through getters and setters.

### 2. **Inheritance** 🧬
   - Promotes code reusability by inheriting common properties and behaviors.
   - Example: Admin and Customer classes inherit from a base `User` class.

### 3. **Polymorphism** 🎭
   - Enables using a single interface to handle multiple data types or classes.
   - Example: A common `displayDetails` method behaves differently for Vehicle and Booking objects.

### 4. **Abstraction** 🎨
   - Hides complex implementation details and exposes only essential features.
   - Example: Users interact with a simplified booking interface without knowing backend details.

---

## 🛠️ Technologies Used

- **Language**: Java
- **Paradigm**: Object-Oriented Programming

---

## 🚀 How to Run

1. **Clone the Repository** 🖥️
   ```bash
   git clone https://github.com/your-username/car-rental-system.git
   cd car-rental-system
   ```

2. **Compile the Code** 🛠️
   ```bash
   javac -d bin src/**/*.java
   ```

3. **Run the Application** ▶️
   ```bash
   java -cp bin Main
   ```

---

## 🧑‍💻 Future Enhancements

- 🛡️ Implement security features like role-based access control.
- 🌐 Add a web interface for better usability.
- 📊 Include reporting and analytics for admins.

---

## 💬 Feedback

Feel free to share your feedback or contribute to the project by raising an issue or creating a pull request!

---

Happy Renting! 🚗💨
