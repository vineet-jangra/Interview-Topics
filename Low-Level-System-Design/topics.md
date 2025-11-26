# **1. OOP Foundation**

* Classes & Objects
* Abstraction
* Encapsulation
* Inheritance
* Polymorphism (compile-time & runtime)
* Composition vs Aggregation
* Interfaces & Abstract classes
* Object lifecycle
* Immutability

---

# **2. SOLID Principles**

* S — Single Responsibility Principle
* O — Open/Closed Principle
* L — Liskov Substitution Principle
* I — Interface Segregation Principle
* D — Dependency Inversion Principle

---

# **3. Core Design Principles**

These are frequently tested in LLD interviews:

* DRY (Don’t Repeat Yourself)
* YAGNI
* KISS
* Separation of Concerns
* Law of Demeter
* Favor composition over inheritance
* Encapsulate what varies
* High Cohesion, Low Coupling

---

# **4. Design Patterns (Very Important)**

### ✔ Creational

* Factory
* Abstract Factory
* Builder
* Singleton
* Prototype

### ✔ Structural

* Adapter
* Decorator
* Composite
* Facade
* Proxy

### ✔ Behavioral

* Strategy
* Observer
* Command
* Chain of Responsibility
* State Pattern
* Template Method
* Iterator


### Others
* Bridge
* Null
* Difference between multiple related patterns and how they are related
---

# **5. Common LLD Interview Problems (Must-Practice)**

These represent **90% of real interview questions**.

### 🔹 **Object-Oriented System Design**

* Parking Lot
* Elevator System
* Library Management System
* Flight Booking System
* Splitwise
* Movie Ticket Booking
* Hotel Booking System
* Food Delivery (Zomato/Swiggy)
* Ride Sharing (Uber/Ola)
* Notification Service
* Rate Limiter
* Logging Framework
* Cache (LRU/LFU)
* Snakes & Ladders / Tic Tac Toe / Chess
* Pub-Sub System
* File System design
* URL Shortener (LLD side)
* ATM Machine design
* Vending Machine
* Auction/Bidding System

### 🔹 **Concurrency-Based LLD Problems**

Common in Google/Uber:

* Thread-safe queue
* Rate limiter with concurrency
* Producer-consumer
* Reader-writer lock
* Thread pool
* Deadlock prevention design
* Blocking queue
* Meta (SDE2 Requirement: You will be asked to code a ThreadSafeCache or a BlockingQueue. You need to master Java's ReentrantLock, Condition, and CompletableFuture.)
---

# **6. Machine Coding Round (Clean Code + Functional LLD)**

Companies like Uber, Flipkart, Hotstar ask this.

### ⚙ **Skills Required**

* Write production-grade code with:

  * Modular structure
  * Clean classes
  * Interfaces where needed
  * No global variables
  * Proper models/entities
  * Error handling
  * Basic unit tests (optional but good)
  * Clear input–output handling

### 📌 **Machine Coding Topics**

* Build LRU Cache
* Snake & Ladder (complete game engine)
* Tic Tac Toe (with Bot levels)
* Logging Framework
* BookMyShow like seat booking
* Splitwise (full flow)
* Cricket Scoreboard System
* Pub-Sub system
* Elevator Controller
* In-memory Key-Value Store
* Rate Limiter (Token bucket / Leaky bucket)
* Inventory Management
* Parking Lot with multiple floors

### 🧩 Machine Coding Techniques

* Interface-driven coding
* Separation of use-cases
* DTOs & models
* Validation & exceptions
* Pure OO design (no leaking state)
* In-memory storage using maps/lists
* Avoiding God classes
* Proper package structure

---

# **7. UML & Diagrams (Used in Interviews)**

* Class diagrams
* Sequence diagrams
* Object interaction diagrams
* Component relationships
* State diagrams (for elevators, games, etc.)

---

# **8. Data Modeling (Important for LLD)**

* Entities & relationships
* ER modeling basics
* One-to-many, many-to-many mapping
* Choosing correct data structures
* Normalization basics
* Designing storage models for OOP systems

---

# **9. Testing & Best Practices**

* Unit testing basics
* Mocking (Mockito style)
* Writing testable classes
* Logging & error handling
* Code readability practices
* Boundary condition handling

---

# **10. Coding Constructs (Often Used in LLD)**

* Maps, Lists, Sets, Queues
* Priority queues
* Custom comparators
* Enums
* Exceptions
* Interfaces & anonymous classes
* Immutable collections