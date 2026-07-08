# 🚗 DVLD - Drivers, License & Vehicle Department System

![C#](https://img.shields.io/badge/Language-C%23-blue)
![.NET Framework](https://img.shields.io/badge/Framework-.NET%20Framework-purple)
![SQL Server](https://img.shields.io/badge/Database-SQL%20Server-red)
![Architecture](https://img.shields.io/badge/Architecture-3--Tier-green)
![Git](https://img.shields.io/badge/Version%20Control-Git-orange)

A professional desktop application for managing **drivers, driving licenses, vehicles, tests, and department operations**.

The project was developed using **C# WinForms**, **SQL Server**, and a **3-Tier Architecture**, applying software engineering principles such as **SOLID**, **Clean Code**, and **Separation of Concerns**.

---

# 📑 Table of Contents

* [System Demo](#-system-demo)
* [Features](#-features)
* [Technology Stack](#-technology-stack)
* [Architecture](#-architecture)
* [Database](#-database)
* [Installation](#-installation)
* [Project Structure](#-project-structure)
* [Engineering Practices](#-engineering-practices)
* [Future Improvements](#-future-improvements)
* [Contact](#-contact)

---

# 📺 System Demo

A complete UI walkthrough and system demonstration:

🔗 LinkedIn Demo:
https://www.linkedin.com/posts/albara-csharp-developer_dvld-drivers-license-and-vehicle-department-ugcPost-7458877382670704640-vkzf

---

# 🚀 Features

## 🚘 License Management

* Issue local driving licenses.
* Renew expired licenses.
* Replace lost or damaged licenses.
* Issue international licenses.
* Detain and release licenses.

## 📝 Testing System

* Vision test management.
* Written test management.
* Practical driving test management.
* Retake test handling.

## 👤 People Management

* Manage drivers and personal information.
* Store profile images.
* Validate personal data.

## 👥 User Management

* Authentication system.
* Role-based permissions.
* User activation and management.

## 📋 Application Workflow

* Track application lifecycle.
* Manage application types.
* Maintain operation history.

---

# 🛠 Technology Stack

| Category          | Technology           |
| ----------------- | -------------------- |
| Language          | C#                   |
| Framework         | .NET Framework       |
| UI                | Windows Forms        |
| Database          | Microsoft SQL Server |
| Data Access       | ADO.NET              |
| Architecture      | 3-Tier Architecture  |
| Design Principles | SOLID                |
| Version Control   | Git & GitHub         |

---

# 🏛 Architecture

The application follows a **3-Tier Architecture**:

```
Presentation Layer (UI)
          |
          ↓
Business Logic Layer (BLL)
          |
          ↓
Data Access Layer (DAL)
          |
          ↓
SQL Server Database
```

## Presentation Layer

Responsible for:

* User interface.
* User interaction.
* Form navigation.
* Displaying information.

## Business Logic Layer

Responsible for:

* Business rules.
* Validation.
* Application workflows.
* Processing operations.

## Data Access Layer

Responsible for:

* Database communication.
* CRUD operations.
* Stored procedures execution.
* Data retrieval.

---

# 🗄 Database

The project includes a complete SQL Server database script.

Location:

```
Database/DVLD.sql
```

The script contains:

* Database creation.
* Tables.
* Relationships.
* Constraints.
* Views.
* Stored Procedures.
* Initial data.

---

# ⚙ Installation

## Requirements

Before running the project, install:

* Visual Studio
* .NET Framework
* Microsoft SQL Server
* SQL Server Management Studio (SSMS)

---

## Database Setup

1. Open SQL Server Management Studio.
2. Execute:

```
Database/DVLD.sql
```

3. Make sure the database:

```
DVLD
```

was created successfully.

4. Open the project in Visual Studio.

5. Update the connection string if required.

6. Build and run the application.

---

# 📂 Project Structure

```
DVLD
│
├── Project
│   ├── Presentation Layer
│   ├── Business Logic Layer
│   └── Data Access Layer
│
├── Database
│   └── DVLD.sql
│
├── README.md
└── .gitignore
```

---

# 🧠 Engineering Practices

This project applies:

* Object-Oriented Programming (OOP)
* SOLID Principles
* Clean Code Practices
* Separation of Concerns
* Database Normalization
* Reusable Components
* Layered Architecture

---

# 🔮 Future Improvements

Possible future enhancements:

* Migration to ASP.NET Core Web API.
* Modern web frontend.
* Automated testing.
* Logging system.
* Advanced reporting dashboard.
* Cloud database deployment.

---

# 📧 Contact

**Albara Fahed Alharissy**

Software Engineer | C# .NET Developer

LinkedIn:
https://www.linkedin.com/in/albara-csharp-developer/

GitHub:
https://github.com/Albarafahed
