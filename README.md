Below is a **professional, university-level README.md** you can directly paste into your GitHub repository for this project.

---

# Flight Management System (C++ – Data Structures)

## 📌 Project Overview

The **Flight Management System** is a console-based C++ application designed to demonstrate the practical implementation of **core data structures** in a real-world scenario.
The system manages flights, passengers, bookings, and cancellations efficiently using multiple data structures, ensuring optimized search, insertion, and deletion operations.

This project is suitable for **Data Structures & Algorithms (DSA)** courses and showcases how abstract concepts are applied in software systems.

---

## 🎯 Objectives

* To implement and integrate multiple data structures in a single system
* To manage flight and passenger data efficiently
* To simulate real-world booking, cancellation, and search operations
* To demonstrate algorithmic concepts such as **BST traversal**, **hashing**, **queue processing**, **stack history**, and **searching techniques**

---

## 🧱 Data Structures Used

| Component            | Data Structure           | Purpose                                 |
| -------------------- | ------------------------ | --------------------------------------- |
| Flights              | Binary Search Tree (BST) | Store and search flights by Flight ID   |
| Passengers           | Hash Table (Chaining)    | Fast insertion and lookup of passengers |
| Booking Requests     | Queue (Linked List)      | FCFS booking request handling           |
| Confirmed Bookings   | Singly Linked List       | Store confirmed bookings                |
| Cancellation History | Stack (Linked List)      | Track cancelled bookings (LIFO)         |

---

## ⚙️ Features

### ✈️ Flight Management

* Add new flights
* Display all flights (in-order traversal)
* Search flight by ID (BST search)
* Search flights by destination
* Binary search on sorted Flight IDs

### 👤 Passenger Management

* Add passengers (auto-generated Passenger ID)
* Display all passengers
* Search passenger by ID (hash lookup)
* Search passenger by name (linear search)

### 📑 Booking System

* Enqueue booking requests (FCFS)
* Process single or all booking requests
* Seat availability management
* Display confirmed bookings

### ❌ Cancellation Management

* Cancel bookings
* Restore seat availability
* Maintain cancellation history using stack
* Optionally remove booking permanently

### 🧪 Demo Support

* Seed sample data for quick testing

---

## 🛠️ Compilation & Execution

### Compile the program:

```bash
g++ -std=c++11 flight_management.cpp -o flight_mgmt
```

### Run the program:

```bash
./flight_mgmt
```

---

## 📂 File Structure

```
flight_management.cpp   # Main source code
README.md               # Project documentation
```

---

## 🧠 Algorithms Demonstrated

* Binary Search Tree insertion and traversal
* Hashing with chaining
* Linear search
* Binary search
* Queue-based FCFS processing
* Stack-based undo/history mechanism

---

## 🧪 Sample Data

The system includes a **sample data seeding option**:

* 3 Flights
* 2 Passengers

This allows quick demonstration without manual data entry.

---

## 📚 Academic Relevance

This project is ideal for:

* Data Structures coursework
* Practical lab demonstrations
* Viva and project defense
* Understanding real-life applications of DSA

---

## 🚀 Future Enhancements

* File handling for persistent storage
* Login system (Admin/User)
* GUI version (Qt / JavaFX)
* Sorting flights by time or price
* Database integration

---

## 👨‍💻 Author

**Syed Intisar Raza**
Computer Science Student (BSAI)
Data Structures & Algorithms Project

