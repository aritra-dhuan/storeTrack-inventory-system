# 📦 StoreTrack Inventory System

A lightweight Java-based inventory management application designed for small businesses to efficiently manage stock and handle customer billing operations.

---

## 🚀 Features

* Add, update, and search product details
* Real-time inventory tracking
* Billing system with cart-based functionality
* Low stock alerts (threshold below 5)
* Prevents invalid or negative stock transactions
* Interactive user feedback messages

---

## 🏗️ Project Structure

StoreTrack/
│
├── Product.java        # Defines product attributes (id, name, price, stock)
├── Inventory.java      # Manages product storage and operations
├── CartItem.java       # Represents items added to cart
├── Bill.java           # Handles billing logic and calculations
├── Main.java           # Entry point (menu-driven interface)

---

## 🧠 Concepts Used

* Object-Oriented Programming (OOP)
* Encapsulation and modular design
* Java Collections Framework

  * HashMap → Efficient product lookup (O(1))
  * ArrayList → Managing cart items
* Input handling using Scanner

---

## ⚙️ How to Run

### 🔹 Prerequisites

* Java installed (JDK 8 or above)
* Terminal or command prompt

### 🔹 Steps to Execute

1. Clone the repository
   git clone https://github.com/aritra-dhuan/storetrack-inventory-system.git

2. Navigate to the project folder
   cd storetrack-inventory-system

3. Compile all Java files
   javac *.java

4. Run the program
   java Main

---

### 🔹 Expected Output

* A menu-driven interface will appear in the terminal
* Users can perform operations like:

  * Add products
  * Update inventory
  * Generate bills
  * View stock details

---

### 🔹 Notes

* Ensure all `.java` files are in the same directory before compiling
* If `javac` or `java` is not recognized, verify Java installation

---

## ⚡ Key Functionalities

### Add Product

* Insert new products with ID, name, price, and stock

### Update Product

* Modify details of existing products

### Billing System

* Add items to cart
* Generate total bill
* Automatically updates stock after purchase

### Stock Validation

* Ensures stock does not go below zero

---

## 🛠️ Challenges Solved

* Fixed Scanner input issues (nextInt() and nextLine() handling)
* Implemented validation to prevent negative stock
* Improved user interaction with dynamic feedback messages

---

## 🔮 Future Improvements

* File handling for persistent data storage
* GUI implementation using JavaFX
* Database integration (MySQL)
* Advanced analytics and reporting

---

## 📚 Learning Outcomes

* Practical understanding of data structures
* Writing modular and maintainable code
* Handling edge cases and user inputs
* Applying programming concepts to real-world problems

---

## 👤 Author

Aritra Dhuan

---

## ⭐ Acknowledgment

This project was developed as part of a BYOP Capstone to solve real-world inventory problems faced by small businesses.
