# 🚗 Drivers, Vehicles & Licenses Department (DVLD)

![C#](https://img.shields.io/badge/Language-C%23-blue)
![.NET Framework](https://img.shields.io/badge/Framework-.NET%20Framework%204.7.2-purple)
![WinForms](https://img.shields.io/badge/UI-Windows%20Forms-green)
![SQL Server](https://img.shields.io/badge/Database-SQL%20Server-red)
![Architecture](https://img.shields.io/badge/Architecture-3--Tier-orange)
![ADO.NET](https://img.shields.io/badge/Data%20Access-ADO.NET-yellow)
![Git](https://img.shields.io/badge/Version%20Control-Git-orange)

A professional **Drivers, Vehicles & Licenses Department (DVLD)** desktop management system built using **C# Windows Forms**, **.NET Framework 4.7.2**, **SQL Server**, and a **3-Tier Architecture**.

The system automates the complete driving license workflow including people management, users, drivers, local and international licenses, testing process, detained licenses, application management, and license services.

---

# 📸 Application Preview

## 🔐 Login Screen

<p align="center">
<img src="Images/frmlogin.png" width="900">
</p>

---

## 🏠 Main Screen

<p align="center">
<img src="Images/frmMain.png" width="900">
</p>

---

# 📑 Table of Contents

- Features
- Screenshots
- Technology Stack
- Architecture
- Database
- Installation
- Configuration
- Project Structure
- Security Notes
- Known Limitations
- Future Improvements
- Contact

---

# 🚀 Features

## 🔐 Authentication

- Secure user login.
- Username & Password authentication.
- Remember Me feature.
- User permission validation.

---

## 👥 People Management

Manage all people records.

Features

- Add Person
- Update Person
- Delete Person
- Search Person
- View Person Details

---

## 👤 User Management

Manage application users.

Features

- Create Users
- Edit Users
- Activate / Deactivate Users
- View User Details

---

## 🚘 Driver Management

Features

- Register Drivers
- View Driver Information
- Link Driver With Licenses

---

## 📄 License Applications

Supports complete driving license workflow.

Features

- New Local Driving License Application
- International License Application
- Renew License
- Replacement For Damaged License
- Replacement For Lost License
- Release Detained License

---

## 🧪 Driving Tests

Manage testing process.

Features

- Vision Test
- Written Test
- Street Test
- Test Appointments
- Test Scheduling

---

## 🚔 Detained Licenses

Features

- Detain License
- Release License
- View Detained Licenses
- Search Detained Licenses

---

## 🌍 International Licenses

Features

- Issue International License
- Display International License
- Manage International Licenses

---

## ⚙️ Administration

Features

- Manage Application Types
- Manage Test Types

---

# 🖼 Screenshots

# 🔐 Login

<p align="center">
<img src="Images/frmlogin.png" width="850">
</p>

---

# 🏠 Main Window

<p align="center">
<img src="Images/frmMain.png" width="850">
</p>

---

# 👥 People Management

| People List | Add / Update Person |
|--------------|--------------------|
| ![](Images/Pepole/frmListPeople.png) | ![](Images/Pepole/frmAddUpdatePerson.png) |

| Person Details |
|----------------|
| ![](Images/Pepole/frmPersonDetalis.png) |

---

# 👤 User Management

| Users List | User Details |
|------------|--------------|
| ![](Images/User/frmlistUser.png) | ![](Images/User/frmUserDetalis.png) |

| Add / Update User | Change Password |
|-------------------|-----------------|
| ![](Images/User/frmAddUpdateUser.png) | ![](Images/User/frmChingeUser.png) |

---

# 🚘 Drivers

<p align="center">
<img src="Images/Driver/frmListDriver.png" width="850">
</p>

---

# 📄 Local Driving License

| Applications | Add Application |
|---------------|----------------|
| ![](Images/Applications/Driving Licenses Services/Local Driver/frmListLocalDrivingLicense.png) | ![](Images/Applications/Driving Licenses Services/Local Driver/frmAddUpdateLocalDrivingLicense.png) |

| License Details |
|-----------------|
| ![](Images/Applications/Driving Licenses Services/Local Driver/frmShowLocalDrivingLicense.png) |

---

# 🌍 International License

| Applications | Add License |
|---------------|-------------|
| ![](Images/Applications/Driving Licenses Services/International License/frmListInternationalLicense .png) | ![](Images/Applications/Driving Licenses Services/International License/frmAddUpdateInternational License .png) |

| License Details |
|-----------------|
| ![](Images/Applications/Driving Licenses Services/International License/frmShowInternationalLicense .png) |

---
# 🚔 Detained Licenses

| Detain License | Detained Licenses |
|----------------|-------------------|
| ![](Images/Applications/Detain Licenses/frmDetainLicenses.png) | ![](Images/Applications/Detain Licenses/frmListDetainLicenses.png) |

| Release Detained License |
|--------------------------|
| ![](Images/Applications/Detain Licenses/frmReleaseDetainedLicense.png) |

---

# 🪪 Driving License Services

| License History | Renew License |
|-----------------|---------------|
| ![](Images/Applications/Driving Licenses Services/frmLicenseHistory.png) | ![](Images/Applications/Driving Licenses Services/frmRenwApplicationLicense.png) |

| Replace Damaged License | Release Detained License |
|--------------------------|--------------------------|
| ![](Images/Applications/Driving Licenses Services/frmReplacementForDamagedLicense.png) | ![](Images/Applications/Driving Licenses Services/frmReleaseDetainedLicense.png) |

---

# ⚙️ Application Types

| Application Types |
|-------------------|
| ![](Images/Applications/Manage Application Types/frmListManageApplicationTypes.png) |

| Edit Application Type |
|-----------------------|
| ![](Images/Applications/Manage Application Types/frmEditManageApplicationTypes.png) |

---

# 🧪 Test Types

| Test Types |
|------------|
| ![](Images/Applications/Manage Test Types/frmListManageTestTypes.png) |

| Edit Test Type |
|----------------|
| ![](Images/Applications/Manage Test Types/frmEditManageTestTypes.png) |

---

# 🛠 Technology Stack

| Category | Technology |
|----------|------------|
| Language | C# |
| Framework | .NET Framework 4.7.2 |
| UI | Windows Forms |
| Database | Microsoft SQL Server |
| Data Access | ADO.NET |
| SQL Provider | System.Data.SqlClient |
| Architecture | 3-Tier Architecture |
| IDE | Visual Studio |
| Version Control | Git & GitHub |

---

# 🏛 Architecture

The project follows a classic **3-Tier Architecture** that separates the user interface, business logic, and data access layers.

```text
                 +----------------------+
                 |      WinForms UI     |
                 |        (DVLD)        |
                 +----------+-----------+
                            |
                            |
                            ▼
                 +----------------------+
                 |   Business Layer     |
                 |   DVLD_Buisness      |
                 +----------+-----------+
                            |
                            |
                            ▼
                 +----------------------+
                 |   Data Access Layer  |
                 | DVLD_DataAccess      |
                 +----------+-----------+
                            |
                            |
                            ▼
                 +----------------------+
                 |     SQL Server       |
                 |      DVLD DB         |
                 +----------------------+
```

This layered design improves maintainability by separating responsibilities across independent projects.

---

## 🖥 Presentation Layer

Project

```text
DVLD
```

Responsibilities

- Windows Forms user interface.
- Navigation between system modules.
- User interaction.
- Input validation.
- Displaying application data.
- Printing and reporting screens.

Main Modules

```text
Login
Main Screen
People
Users
Drivers
Applications
Licenses
Tests
Application Types
Test Types
```

---

## ⚙️ Business Layer

Project

```text
DVLD_Buisness
```

Responsibilities

- Business Rules.
- Validation.
- Domain Objects.
- License Workflow.
- Driver Management.
- Test Processing.

Main Classes

```text
clsPerson
clsUsers
clsApplication
clsDriver
clsLicense
clsTest
clsInternationalLicense
clsDetainedLicense
```

---

## 🗄 Data Access Layer

Project

```text
DVLD_DataAccess
```

Responsibilities

- SQL Server communication.
- CRUD Operations.
- Execute SQL Queries.
- Stored data retrieval.
- Connection management.

Main Classes

```text
clsPersonData
clsUsersData
clsApplicationData
clsDriverData
clsLicenseData
clsTestData
clsInternationalLicenseData
clsDetainedLicenseData
clsDataAccessSettings
```

---

# 🗄 Database

The application uses

```text
Microsoft SQL Server
```

Database Name

```text
DVLD
```

Main Tables

```text
People
Users
Drivers
Applications
ApplicationTypes
LicenseClasses
Licenses
InternationalLicenses
LocalDrivingLicenseApplications
DetainedLicenses
TestAppointments
Tests
TestTypes
Countries
```

The repository does not include

- Database creation scripts.
- Migration files.
- Seed data.

---

# 📂 Project Structure

```text
DVLD
│
├── DVLD
│   ├── Login
│   ├── People
│   ├── Users
│   ├── Drivers
│   ├── Applications
│   ├── Licenses
│   ├── Tests
│   ├── Resources
│   └── Program.cs
│
├── DVLD_Buisness
│   ├── clsPerson
│   ├── clsUsers
│   ├── clsApplication
│   ├── clsDriver
│   ├── clsLicense
│   ├── clsTest
│   └── ...
│
├── DVLD_DataAccess
│   ├── clsPersonData
│   ├── clsUsersData
│   ├── clsApplicationData
│   ├── clsDriverData
│   ├── clsLicenseData
│   ├── clsTestData
│   └── clsDataAccessSettings
│
├── Database
│
├── Images
│
└── README.md
```
---

# ⚙ Installation

## Requirements

Before running the application, make sure you have:

- Windows
- Visual Studio 2022 (or newer)
- .NET Framework 4.7.2 Developer Pack
- Microsoft SQL Server
- SQL Server Management Studio (SSMS)

---

## Setup

1. Clone the repository.

```bash
git clone https://github.com/Albarafahed/DVLD-Windows-Form-CSharp.git
```

2. Open the solution.

```text
DVLD.sln
```

3. Create the database.

The repository includes a SQL Server database script.

Open:

```text
Database
└── DVLD.sql
```

using **SQL Server Management Studio (SSMS)**, then execute the script to create the **DVLD** database and all required tables.

4. Configure the connection string.

Open:

```text
DVLD_DataAccess
└── clsDataAccessSettings.cs
```

Update the SQL Server name (and credentials if necessary) to match your local SQL Server instance.

5. Build and run the solution.

---

# ▶ Running the Project

After completing the installation:

- Build the solution.
- Set **DVLD** as the Startup Project.
- Press **F5** (or click **Start**) to launch the application.

The application starts with:

```text
Program.cs
      │
      ▼
frmLogin
      │
      ▼
Authentication
      │
      ▼
frmMain
```

---

# 🔄 Application Workflow

The system manages the complete driving license process.

```text
Register Person
        │
        ▼
Create License Application
        │
        ▼
Schedule Required Tests
        │
        ▼
Pass All Tests
        │
        ▼
Issue Driving License
        │
        ▼
License Services
        │
        ├── Renew License
        ├── Replace Lost License
        ├── Replace Damaged License
        ├── Detain License
        ├── Release License
        └── Issue International License
```

---

# 📝 Notes

- Desktop Windows Forms application.
- Built using a 3-Tier Architecture.
- Uses Microsoft SQL Server.
- Database access is implemented with ADO.NET.
- Business logic is separated from the Presentation Layer.
- SQL queries are executed through the Data Access Layer.
- The repository includes the SQL database creation script.

---

# 🔒 Security Notes

Current implementation:

- User authentication is database-based.
- Remember Me stores user credentials locally.
- Database connection information is stored in the Data Access Layer.

Possible improvements:

- Hash user passwords.
- Encrypt stored credentials.
- Move the connection string to `App.config`.
- Use Windows Authentication or a restricted SQL Server account.
- Add centralized logging and exception handling.

---

# ⚠ Known Limitations

Current limitations include:

- No automated tests.
- No logging framework.
- No installer package.
- Connection string is stored in source code.
- Repository Pattern is not implemented.
- No Dependency Injection.
- No localization support.

---

# 🚀 Future Improvements

Possible future enhancements:

### Architecture

- Implement Repository Pattern.
- Add Dependency Injection.
- Improve code separation.
- Introduce Unit of Work Pattern.

### Database

- Database migration scripts.
- Seed data.
- Backup and restore tools.

### Security

- Password hashing.
- Secure Remember Me implementation.
- Role-based authorization.
- Audit logging.

### Features

- Dashboard statistics.
- Export reports to PDF.
- Export reports to Excel.
- Email notifications.
- QR Code support.
- Barcode support.

### Development

- Unit Testing.
- Integration Testing.
- Logging with Serilog or NLog.
- CI/CD pipeline.

---

# 📷 Images

Application screenshots are stored in:

```text
Images
│
├── Applications
├── Driver
├── Pepole
├── User
├── frmlogin.png
└── frmMain.png
```

---

# 📚 Learning Objectives

This project demonstrates practical experience with:

- C#
- Windows Forms
- Object-Oriented Programming (OOP)
- SOLID Principles
- SQL Server
- ADO.NET
- 3-Tier Architecture
- CRUD Operations
- Authentication
- Desktop Application Development

---

# 👤 Author

**Albara Fahed Alharissy**

.NET Developer

- GitHub: https://github.com/Albarafahed
- LinkedIn: https://www.linkedin.com/in/albara-csharp-developer/

---

# ⭐ Support

If you found this project useful, consider giving it a **Star** on GitHub.

---

# 📄 License

This repository does not currently include a LICENSE file.