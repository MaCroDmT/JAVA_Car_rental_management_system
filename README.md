# Car Rental Management System

This is a **Java-based console application** for managing a Car Rental service. It includes functionality for managing vehicles, customers, and rentals, with an admin login system for access control.

## 📋 Features

### 🔐 Admin Login
- Multiple hardcoded admin credentials
- Access control loop until successful login

### 🚗 Vehicle Management
- Add a new vehicle
- Remove a vehicle
- Search a vehicle by ID
- View all vehicles

### 👥 Customer Management
- Add a new customer with full details
- Remove an existing customer
- Search for a customer by ID
- View all customers

### 📄 Rental Management
- Rent a vehicle to a customer
- Input rental and return dates

## 🗂️ Package Structure

- `classes.*` – Expected to include concrete classes like `Customer`, `Manager`, `Rentals`, etc.
- `abstracts.Vehicle` – Assumed abstract class for base vehicle-related functionality

## 🧾 Technologies Used

- **Java** (JDK 8+)
- **Console-based UI**
- **SimpleDateFormat** for date parsing

## ✅ Requirements

- JDK 8 or higher
- Java-compatible IDE or terminal

## ▶️ How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/car-rental-management.git
   cd car-rental-management
   ```

2. Compile the project:

   ```bash
   javac Start.java
   ```

3. Run the application:

   ```bash
   java Start
   ```

4. Login using one of the hardcoded admin accounts:

   ```
   Username: prottoy
   Password: 21-45640-3
   ```

   (Other valid credentials are also supported.)

## ⚠️ Notes

- Admin credentials are hardcoded for simplicity.
- No persistent storage (like a database or file I/O) is used — data is stored in memory during runtime.
- Proper package structure and additional class files (like `Manager`, `Vehicle`, `Customer`, etc.) must be present for the application to run successfully.

## 🛠️ To-Do / Possible Enhancements

- Add file or database persistence
- Improve input validation and error handling
- Separate UI and business logic more cleanly
- Implement rental return and history tracking

## 📄 License

This project is licensed under the [MIT License](LICENSE).
