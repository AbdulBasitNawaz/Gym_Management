# MUSCLE-HUB: Gym Management System

MUSCLE-HUB is a desktop-based administrative application designed to streamline operations, data organization, and member management for fitness centers. Built using Java Swing and a relational database backend, the system provides a modular dashboard interface to handle daily gym workflows efficiently.

---

## Project Context & Contributions
This application was co-developed as a collaborative project. My specific technical contributions and focus areas on the system included:
* **Object-Oriented Design (OOD):** Applied core OOP pillars—such as Inheritance and Polymorphism—to model scalable system entities (e.g., establishing a base user structure inherited by specialized Member and Trainer classes).
* **Data Encapsulation:** Enforced strict encapsulation across data models to safely manage entity states, member profiles, and financial transactions prior to database commits.
* **Database Engineering & Connectivity:** Mapped application logic to a normalized MySQL relational database, implementing JDBC (Java Database Connectivity) to handle structured CRUD operations and data persistence safely.
* **UI & Logic Separation:** Decoupled the graphical user interface components (Java Swing) from the underlying backend operational logic to maximize code maintainability.
---

## Key Functionalities

* **Administrative Dashboard:** Centralized, modular navigation layout to monitor gym metrics and easily access core system subsystems.
* **Member & Trainer Management:** Automated indexing, profile updating, and tracking workflows for gym personnel and clients.
* **Attendance & Operations:** Systematically logs and tracks daily attendance metrics for members and staff.
* **Financial Monitoring:** Integrated payment status monitoring and subscription tracking interfaces.
* **Secure Authentication:** User login architecture featuring email-based password recovery integration.

---

## Technical Stack

## Technical Stack

### Frontend & GUI
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Java Swing](https://img.shields.io/badge/Java_Swing-007396?style=for-the-badge&logo=java&logoColor=white)

### Database Management & Connectivity
![MySQL](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)
![JDBC](https://img.shields.io/badge/JDBC_Connectivity-437291?style=for-the-badge&logo=data-grip&logoColor=white)

### Third-Party Integrations & Tools
![EmailJS](https://img.shields.io/badge/EmailJS_API-F15A24?style=for-the-badge&logo=email&logoColor=white)
![NetBeans](https://img.shields.io/badge/NetBeans_IDE-1B6AC6?style=for-the-badge&logo=apache-netbeans&logoColor=white)

---

## Getting Started

### Prerequisites
* Java Development Kit (JDK) 8 or higher
* MySQL Server

### Installation & Setup
1. Clone your forked repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/Gym_Management.git](https://github.com/YOUR_USERNAME/Gym_Management.git)
