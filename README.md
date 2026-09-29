# 🎓 University Routine Scheduling Management System

<p align="center">
  <img src="https://img.shields.io/badge/PHP-8.x-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP">
  <img src="https://img.shields.io/badge/Laravel-Framework-FF2D20?style=for-the-badge&logo=laravel&logoColor=white" alt="Laravel">
  <img src="https://img.shields.io/badge/MySQL-Database-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL">
  <img src="https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/jQuery-Library-0769AD?style=for-the-badge&logo=jquery&logoColor=white" alt="jQuery">
  <img src="https://img.shields.io/badge/Bootstrap-5-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap">
  <img src="https://img.shields.io/badge/GitHub-Version%20Control-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Architecture-MVC-blue?style=flat-square" alt="MVC">
  <img src="https://img.shields.io/badge/Academic%20Project-Fall%202024-orange?style=flat-square" alt="Academic Project">
  <img src="https://img.shields.io/badge/Project%20Status-85%25%20Completed-success?style=flat-square" alt="Project Status">
</p>

<h3 align="center">Academic Routine & Schedule Management System</h3>

<p align="center">
  A centralized web-based platform for creating, managing, validating, modifying, and viewing academic routines for educational institutions.
</p>

---

## 📌 Table of Contents

* [📖 Project Overview](#-project-overview)
* [🎯 Problem Statement](#-problem-statement)
* [💡 Proposed Solution](#-proposed-solution)
* [🎯 Project Objectives](#-project-objectives)
* [✨ Key Features](#-key-features)
* [🏗️ System Architecture](#️-system-architecture)
* [🔄 System Workflow](#-system-workflow)
* [📦 Core Modules](#-core-modules)
* [🛠️ Technology Stack](#️-technology-stack)
* [🗄️ Database & Data Management](#️-database--data-management)
* [📋 Functional Areas](#-functional-areas)
* [🧪 Testing & Validation](#-testing--validation)
* [📸 Screenshots](#-screenshots)
* [🚀 Installation & Setup](#-installation--setup)
* [⚙️ Environment Configuration](#️-environment-configuration)
* [▶️ Running the Project](#️-running-the-project)
* [📈 Project Status](#-project-status)
* [✅ Implemented Results](#-implemented-results)
* [🔮 Future Improvements](#-future-improvements)
* [📅 Project Timeline](#-project-timeline)
* [🎓 Academic Information](#-academic-information)
* [👨‍💻 Project Team](#-project-team)
* [👨‍🏫 Project Supervisor](#-project-supervisor)
* [📚 Research Background](#-research-background)
* [📖 Project Documentation](#-project-documentation)
* [📑 References](#-references)
* [🙏 Acknowledgements](#-acknowledgements)
* [📄 License](#-license)
* [⭐ Support](#-support)

---

# 📖 Project Overview

The **City University Routine Scheduling Management System** is a web-based academic scheduling application developed to simplify and improve the management of university class routines.

Academic institutions often manage large amounts of scheduling information involving courses, teachers, classrooms, batches, time slots, and academic days. Managing this information manually can result in scheduling conflicts, room allocation problems, data inconsistency, repetitive work, and difficulties when changes need to be made.

This project provides a centralized system where academic routine-related information can be managed through a structured web interface.

The application focuses on:

* Course and routine management
* Faculty and teacher management
* Room management
* Batch management
* Schedule creation and modification
* Schedule validation
* Teacher-wise routine views
* Batch-wise routine views
* Room-wise routine views
* Day-wise routine views
* Printable routine information
* Access control and centralized data management

The project was developed as an academic project for the **Department of Computer Science and Engineering, City University, Bangladesh**.

---

# 🎯 Problem Statement

Traditional academic routine preparation and management can be time-consuming and difficult, particularly when a large number of courses, teachers, rooms, batches, and time slots are involved.

Manual scheduling may cause:

* Duplicate room allocation
* Teacher schedule conflicts
* Incorrect class timing
* Difficulty modifying existing routines
* Repetitive administrative work
* Inconsistent routine data
* Difficulty generating different routine views
* Problems when distributing updated schedules

A centralized digital system can help organize these scheduling activities and make routine management more structured and efficient.

---

# 💡 Proposed Solution

The proposed solution is a **web-based Routine Scheduling Management System** that centralizes academic scheduling information.

The system provides an organized environment for creating and managing routines while allowing users to retrieve schedule information according to teachers, batches, rooms, and days.

The platform is designed around the following principles:

```text
Centralized Data
      ↓
Structured Management
      ↓
Routine Creation
      ↓
Schedule Validation
      ↓
Routine Modification
      ↓
Multiple Routine Views
      ↓
Printable Academic Schedules
```

---

# 🎯 Project Objectives

The primary objectives of this project are:

1. To simplify academic routine creation and management.
2. To reduce scheduling and room allocation conflicts.
3. To centralize academic scheduling information.
4. To provide a structured platform for teachers, courses, rooms, batches, and routines.
5. To allow users to create and modify routines easily.
6. To provide teacher-wise, batch-wise, room-wise, and day-wise routine views.
7. To validate routine information before it is saved or used.
8. To improve the accessibility of academic schedules.
9. To reduce repetitive manual work.
10. To provide a scalable foundation for future scheduling and optimization features.

---

# ✨ Key Features

## 📅 Routine Management

The system supports academic routine management through a centralized web interface.

### Available Operations

* Create routines
* Modify existing routines
* Update classroom information
* Update class time
* Manage routine information by day
* View schedules based on different criteria
* Maintain structured academic schedule information

---

## 🔍 Schedule & Conflict Validation

The system includes schedule validation functionality designed to reduce conflicts and incorrect routine information.

### Validation Areas

* Room allocation
* Class timing
* Routine information
* Schedule consistency
* Conflicting class allocations

The validation process helps improve the reliability of routine information before it is finalized.

---

## 👨‍🏫 Faculty & Teacher Management

The system provides facilities for managing teacher and faculty information.

### Functions

* Add teacher information
* Update teacher information
* Maintain teacher records
* Associate teachers with courses
* Use teacher information in routine generation and reporting

---

## 📚 Course Management

Course information can be managed centrally within the application.

### Functions

* Maintain course records
* Associate courses with teachers
* Associate courses with batches
* Use course information when preparing routines

---

## 👥 Batch Management

The system organizes academic scheduling information according to batches.

This allows users to view and manage routines associated with individual academic batches.

---

## 🏫 Room Management

Classroom information is an important component of academic scheduling.

The system supports:

* Room information management
* Room assignment
* Room-based schedule viewing
* Room conflict validation

---

## 📊 Routine Reports

The system provides multiple routine views for easier academic management.

### 👨‍🏫 Teacher-wise

View routines assigned to a specific teacher.

### 👥 Batch-wise

View routines associated with a specific batch.

### 🏫 Room-wise

View the schedule associated with a specific classroom.

### 📅 Day-wise

View the academic schedule for a specific day.

---

## 🖨️ Print & Export Support

The system supports filtered routine views that can be prepared for printing and academic distribution.

Routine information can be filtered according to:

* Day
* Room
* Teacher
* Batch

---

## 🔐 Authentication & Access Control

The application provides controlled system access through authentication and role-based access management.

This helps ensure that system functions are accessible according to the user's role and permissions.

---

## 🖥️ User-Friendly Interface

The interface is designed to make routine-related tasks easier to perform.

The system focuses on:

* Simple navigation
* Organized pages
* Structured forms
* Responsive layout
* Easy routine management
* Clear schedule presentation

---

# 🏗️ System Architecture

The system follows an **MVC (Model-View-Controller)** based application architecture using the Laravel framework.

```text
                            ┌─────────────────────────────┐
                            │            USERS            │
                            │     Admin / Faculty / Staff │
                            └──────────────┬──────────────┘
                                           │
                                           ▼
                            ┌─────────────────────────────┐
                            │       PRESENTATION LAYER    │
                            │                             │
                            │ HTML5                       │
                            │ CSS3                        │
                            │ Bootstrap                   │
                            │ JavaScript                  │
                            │ jQuery                      │
                            └──────────────┬──────────────┘
                                           │
                                           ▼
                            ┌─────────────────────────────┐
                            │       LARAVEL APPLICATION   │
                            │                             │
                            │      MVC Architecture      │
                            │                             │
                            │ Routes                      │
                            │ Controllers                 │
                            │ Models                      │
                            │ Validation                  │
                            │ Business Logic              │
                            └──────────────┬──────────────┘
                                           │
                                           ▼
                            ┌─────────────────────────────┐
                            │        DATABASE LAYER       │
                            │                             │
                            │           MySQL             │
                            │                             │
                            │ Users                       │
                            │ Teachers                    │
                            │ Courses                     │
                            │ Rooms                       │
                            │ Batches                     │
                            │ Routines                    │
                            └─────────────────────────────┘
```

---

# 🔄 System Workflow

```text
┌─────────────────┐
│    User Login   │
└────────┬────────┘
         │
         ▼
┌─────────────────┐
│    Dashboard    │
└────────┬────────┘
         │
         ▼
┌─────────────────────────────────┐
│ Manage Academic Information     │
│                                 │
│ • Teachers                      │
│ • Courses                       │
│ • Batches                       │
│ • Rooms                         │
└────────┬────────────────────────┘
         │
         ▼
┌─────────────────┐
│ Create Routine  │
└────────┬────────┘
         │
         ▼
┌─────────────────┐
│ Validate Data   │
└────────┬────────┘
         │
         ▼
┌─────────────────┐
│ Save Routine    │
└────────┬────────┘
         │
         ▼
┌─────────────────────────────┐
│ View / Filter Routine       │
│                             │
│ Teacher-wise                │
│ Batch-wise                  │
│ Room-wise                   │
│ Day-wise                    │
└────────┬────────────────────┘
         │
         ▼
┌─────────────────┐
│ Print / Export  │
└─────────────────┘
```

---

# 📦 Core Modules

## 1. 🔐 Authentication Module

Responsible for:

* User login
* User authentication
* Access control
* Role-based permissions

---

## 2. 👨‍🏫 Teacher & Faculty Module

Responsible for:

* Teacher records
* Faculty information
* Teacher-course relationships
* Teacher schedule information

---

## 3. 📚 Course Module

Responsible for:

* Course records
* Course information
* Course-batch relationships
* Course-teacher relationships

---

## 4. 👥 Batch Module

Responsible for:

* Batch information
* Academic group management
* Batch-specific routines

---

## 5. 🏫 Room Module

Responsible for:

* Classroom information
* Room assignment
* Room availability information
* Room-wise scheduling

---

## 6. 🗓️ Routine Module

Responsible for:

* Routine creation
* Routine modification
* Class scheduling
* Time management
* Room assignment
* Schedule organization

---

## 7. 🔍 Validation Module

Responsible for:

* Schedule validation
* Conflict checking
* Room allocation validation
* Routine information validation

---

## 8. 📊 Reporting Module

Provides:

* Teacher-wise reports
* Batch-wise reports
* Room-wise reports
* Day-wise reports
* Filtered routine views
* Printable routine information

---

# 🛠️ Technology Stack

| Category                  | Technology   |
| :------------------------ | :----------- |
| **Frontend**              | HTML5, CSS3  |
| **CSS Framework**         | Bootstrap    |
| **Client-side Scripting** | JavaScript   |
| **JavaScript Library**    | jQuery       |
| **Backend Language**      | PHP          |
| **Backend Framework**     | Laravel      |
| **Database**              | MySQL        |
| **Architecture**          | MVC          |
| **Version Control**       | Git          |
| **Repository Hosting**    | GitHub       |
| **Deployment**            | Cloud Server |

---

# 💻 Development Technologies

## Frontend

```text
HTML5
CSS3
Bootstrap
JavaScript
jQuery
```

## Backend

```text
PHP
Laravel
MVC Architecture
```

## Database

```text
MySQL
```

## Development & Version Control

```text
Git
GitHub
```

---

# 🗄️ Database & Data Management

The system uses **MySQL** as the relational database management system.

The database is designed to manage structured academic scheduling information including:

```text
Users
   │
   ├── Authentication
   └── Access Control

Teachers
   │
   └── Faculty / Teacher Information

Courses
   │
   └── Course Information

Batches
   │
   └── Academic Batch Information

Rooms
   │
   └── Classroom Information

Routines
   │
   ├── Course
   ├── Teacher
   ├── Batch
   ├── Room
   ├── Day
   └── Time
```

---

# 📋 Functional Areas

| Functional Area          | Description                      |
| :----------------------- | :------------------------------- |
| 🔐 Authentication        | Secure user access               |
| 👨‍🏫 Teacher Management | Manage teacher information       |
| 📚 Course Management     | Manage academic courses          |
| 👥 Batch Management      | Manage academic batches          |
| 🏫 Room Management       | Manage classrooms                |
| 🗓️ Routine Management   | Create and modify schedules      |
| 🔍 Validation            | Validate routine information     |
| 📊 Reporting             | Generate different routine views |
| 🖨️ Printing             | Prepare routines for printing    |

---

# 🧪 Testing & Validation

Testing and validation were performed to verify the major functionality of the system.

The testing process focused on:

* Authentication
* Teacher management
* Course management
* Batch management
* Room management
* Routine creation
* Routine modification
* Schedule validation
* Routine filtering
* Teacher-wise routine
* Batch-wise routine
* Room-wise routine
* Day-wise routine
* Print-friendly routine views

The validation process helped identify and reduce scheduling inconsistencies and conflicting resource assignments.

---

# 📸 Screenshots

> Place all project screenshots inside the `screenshots/` directory.

## 🔐 Login Page

![Login Page](screenshots/login.png)

---

## 📊 Dashboard

![Dashboard](screenshots/dashboard.png)

---

## 👨‍🏫 Teacher Management

![Teacher Management](screenshots/teacher-management.png)

---

## 📚 Course Management

![Course Management](screenshots/course-management.png)

---

## 👥 Batch Management

![Batch Management](screenshots/batch-management.png)

---

## 🏫 Room Management

![Room Management](screenshots/room-management.png)

---

## 📅 Routine Management

![Routine Management](screenshots/routine-management.png)

---

## 👨‍🏫 Teacher-wise Routine

![Teacher-wise Routine](screenshots/teacher-wise-routine.png)

---

## 👥 Batch-wise Routine

![Batch-wise Routine](screenshots/batch-wise-routine.png)

---

## 🏫 Room-wise Routine

![Room-wise Routine](screenshots/room-wise-routine.png)

---

## 📆 Day-wise Routine

![Day-wise Routine](screenshots/day-wise-routine.png)

---

# 🚀 Installation & Setup

## 📋 Prerequisites

Before running the project, install the following:

* PHP 8.x
* Composer
* Laravel
* MySQL
* Node.js
* npm
* Git

---

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/city-university-routine-management.git
```

Navigate into the project directory:

```bash
cd city-university-routine-management
```

---

## 2️⃣ Install PHP Dependencies

```bash
composer install
```

---

## 3️⃣ Install Frontend Dependencies

```bash
npm install
```

---

## 4️⃣ Create Environment File

```bash
cp .env.example .env
```

Generate the Laravel application key:

```bash
php artisan key:generate
```

---

# ⚙️ Environment Configuration

Open the `.env` file and configure your database:

```env
APP_NAME="City University Routine Scheduling Management System"
APP_ENV=local
APP_KEY=
APP_DEBUG=true
APP_URL=http://127.0.0.1:8000

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=your_database_name
DB_USERNAME=your_username
DB_PASSWORD=your_password
```

---

# 🗃️ Database Setup

Create a MySQL database and update the `.env` configuration.

Then run:

```bash
php artisan migrate
```

For seeded data:

```bash
php artisan db:seed
```

Or run migration and seeding together:

```bash
php artisan migrate --seed
```

---

# ▶️ Running the Project

Start the Laravel development server:

```bash
php artisan serve
```

Open the application in your browser:

```text
http://127.0.0.1:8000
```

---

# 🎨 Frontend Development

During development, frontend assets can be compiled using:

```bash
npm run dev
```

For production builds:

```bash
npm run build
```

---

# 🧹 Cache & Optimization

When necessary, Laravel cache and configuration can be cleared using:

```bash
php artisan optimize:clear
```

---

# 📈 Project Status

## 🟢 85% Completed

The project reached approximately **85% completion during the academic project evaluation**.

The major routine management functions were implemented, while several advanced features were identified as future improvements.

---

# ✅ Implemented Results

The implemented system successfully provides:

* ✅ Creation of custom routines
* ✅ Modification of existing routines
* ✅ Updating room numbers
* ✅ Updating class times
* ✅ Teacher management
* ✅ Course management
* ✅ Batch management
* ✅ Room management
* ✅ Teacher-wise routines
* ✅ Batch-wise routines
* ✅ Room-wise routines
* ✅ Day-wise routines
* ✅ Routine filtering
* ✅ Schedule validation
* ✅ Print-friendly routine views
* ✅ Centralized routine management
* ✅ User authentication
* ✅ Access control

---

# 📊 Routine Viewing Options

The system provides multiple ways to view academic routines.

```text
                    ACADEMIC ROUTINE
                           │
        ┌──────────────────┼──────────────────┐
        │                  │                  │
        ▼                  ▼                  ▼
   Teacher-wise        Batch-wise         Room-wise
        │                  │                  │
        └──────────────────┼──────────────────┘
                           │
                           ▼
                      Day-wise
```

This allows users to retrieve schedule information according to their specific requirements.

---

# 🧠 Scheduling & Validation Approach

The project addresses academic scheduling through structured routine management and validation.

The overall scheduling process considers information such as:

```text
Teacher
   +
Course
   +
Batch
   +
Room
   +
Day
   +
Time
   ↓
Routine Validation
   ↓
Academic Schedule
```

The project documentation also discusses constraint-based scheduling concepts as part of the research and design background.

---

# 🔮 Future Improvements

Several advanced features were identified for future versions of the system.

## 🤖 AI-Based Optimization

Future versions can introduce AI-based optimization techniques to improve timetable generation and resource utilization.

## 🔔 Real-Time Notifications

Users could receive notifications when routines are created, modified, or updated.

## 📱 Mobile Application

A dedicated mobile application could provide easier access to academic schedules.

## 🧠 Advanced Conflict Resolution

Future versions could provide more advanced techniques for identifying and resolving scheduling conflicts.

## 🏫 Multi-University Support

The architecture could be extended to support scheduling systems for multiple universities or institutions.

## 📊 Advanced Analytics

Future releases could introduce analytics for:

* Room utilization
* Teacher workload
* Schedule distribution
* Resource utilization

## 🔗 SIS / LMS Integration

Integration with existing:

* Student Information Systems
* Learning Management Systems

could improve data synchronization and reduce duplicate data entry.

---

# 📅 Project Timeline

The project activities were carried out between **05 June 2024 and 18 January 2025**.

| Phase | Activity              |
| :---- | :-------------------- |
| 01    | Analysis              |
| 02    | Requirement Gathering |
| 03    | Methodology Planning  |
| 04    | Project Planning      |
| 05    | System Design         |
| 06    | Database Design       |
| 07    | UI Design             |
| 08    | Development           |
| 09    | Pre-Testing           |
| 10    | Final Testing         |
| 11    | Evaluation            |
| 12    | Documentation         |

---

# 🧩 Development Methodology

The project development process followed a structured software engineering workflow.

```text
Requirement Gathering
        ↓
Requirement Analysis
        ↓
System Design
        ↓
Database Design
        ↓
UI Design
        ↓
Implementation
        ↓
Testing
        ↓
Validation
        ↓
Deployment
        ↓
Maintenance & Future Improvement
```

---

# 📝 Requirement Analysis

The system requirements were analyzed based on the needs of academic routine management.

Major requirements included:

* User authentication
* Teacher management
* Course management
* Batch management
* Room management
* Routine creation
* Routine editing
* Routine validation
* Routine filtering
* Multiple schedule views
* Printable schedule information

---

# 🎨 System Design

The project documentation included system design activities such as:

* System workflow design
* Use case analysis
* Activity diagram
* Database design
* Entity Relationship Diagram
* User interface design
* MVC-based application architecture

---

# 📐 System Diagrams

The academic project documentation includes diagrams covering:

### Use Case Diagram

Represents the interaction between users and the system.

### Activity Diagram

Represents the flow of routine-related activities.

### ER Diagram

Represents the relationships between major database entities.

### Workflow Diagram

Represents the overall scheduling and management workflow.

---

# 🎓 Academic Information

| Information                          | Details                                                 |
| :----------------------------------- | :------------------------------------------------------ |
| **Project Title**                    | City University Routine Scheduling Management System    |
| **Degree**                           | Bachelor of Science in Computer Science and Engineering |
| **Department**                       | Department of Computer Science and Engineering          |
| **University**                       | City University                                         |
| **Location**                         | Dhaka, Bangladesh                                       |
| **Semester**                         | Fall 2024                                               |
| **Project Start**                    | 05 June 2024                                            |
| **Project End**                      | 18 January 2025                                         |
| **Project Completion at Evaluation** | 85%                                                     |

---

# 👨‍💻 Project Team

| Name                    | Student ID |
| :---------------------- | :--------: |
| **Md. Forhad Ali**      | 2115602014 |
| **Md. Zihad Hossain**   | 2115602018 |
| **Md. Ibrahim Hossain** | 2115602022 |
| **Abdur Rashid**        | 2115602002 |

---

# 👨‍🏫 Project Supervisor

### Ahsan Habib

**Lecturer & Coordinator**
Department of Computer Science and Engineering
**City University, Bangladesh**

---

# 📚 Research Background

The project was developed with reference to existing research and concepts related to academic scheduling and educational resource management.

Major research areas include:

* Academic Timetabling
* University Scheduling
* Automated Timetabling
* Constraint-Based Scheduling
* Faculty Assignment
* Room Allocation
* Conflict Detection
* Educational Scheduling Systems
* Academic Information Management
* Resource Optimization
* Schedule Sharing
* Centralized Scheduling Platforms
* Access Control
* Data Security
* Scalability and Adaptability
* Customization of Academic Schedules

---

# 🔑 Keywords

```text
Routine Scheduling Management System
Class Schedule Management
Timetable Automation
Educational Scheduling System
Faculty Assignment
Room Allocation
Automated Conflict Detection
Real-Time Updates
Centralized Scheduling Platform
Data Security
Access Control
Scalability and Adaptability
Schedule Sharing
Customization Options
Education Management System
```

---

# 📖 Project Documentation

The complete academic project report covers the following areas:

### Chapter / Section Areas

* Introduction
* Background
* Problem Statement
* Project Objectives
* Proposed Solution
* Literature Review
* Requirement Analysis
* System Analysis
* Methodology
* Project Planning
* System Design
* Database Design
* User Interface Design
* Implementation
* Testing
* Validation
* Results
* Discussion
* Limitations
* Future Work
* Conclusion
* References

---

# 📚 Literature & Research References

The academic project was informed by research related to automated timetabling and scheduling systems, including works such as:

1. Burke, E. K., & Petrovic, S. (2002). Recent research directions in automated timetabling.
2. Schaerf, A. (1999). A survey of automated timetabling.
3. Babaei, H., Karimpour, J., & Hadidi, A. (2015). A survey of approaches for university course timetabling problem.
4. Pillay, N. (2014). A survey of school timetabling research.
5. Wren, A. (1996). Scheduling, timetabling and rostering — A special relationship?
6. City University — Official institutional information and academic context.
7. Software engineering and web application development best practices.

---

# 🧪 Project Evaluation

During the academic evaluation, the implemented system demonstrated the ability to:

* Create custom routines
* Modify existing routines
* Update room and time information
* Display teacher-wise schedules
* Display batch-wise schedules
* Display room-wise schedules
* Display day-wise schedules
* Validate schedule information
* Simplify routine management

The system reached an estimated **85% completion level** during the evaluation stage, with additional advanced features identified for future development.

---

# 🌐 Deployment

The project documentation describes deployment using a **cloud server** environment.

For local development, the project can be executed using Laravel's built-in development server:

```bash
php artisan serve
```

---

# 🔐 Security Considerations

The system includes access control and authentication concepts to protect routine management functions.

Security considerations include:

* User authentication
* Role-based access
* Controlled system operations
* Database validation
* Structured application architecture
* Protection of administrative functions

---

# 📂 Suggested Repository Structure

```text
city-university-routine-management/
│
├── app/
├── bootstrap/
├── config/
├── database/
├── public/
├── resources/
├── routes/
├── storage/
├── tests/
│
├── screenshots/
│   ├── login.png
│   ├── dashboard.png
│   ├── teacher-management.png
│   ├── course-management.png
│   ├── batch-management.png
│   ├── room-management.png
│   ├── routine-management.png
│   ├── teacher-wise-routine.png
│   ├── batch-wise-routine.png
│   ├── room-wise-routine.png
│   └── day-wise-routine.png
│
├── .env.example
├── .gitignore
├── artisan
├── composer.json
├── package.json
└── README.md
```

---

# 💻 Example Application Flow

```text
LOGIN
  │
  ▼
DASHBOARD
  │
  ├───────────────┐
  │               │
  ▼               ▼
TEACHERS       COURSES
  │               │
  └───────┬───────┘
          │
          ▼
       BATCHES
          │
          ▼
        ROOMS
          │
          ▼
       ROUTINE
          │
          ▼
     VALIDATION
          │
          ▼
       REPORTS
          │
     ┌────┼────┐
     │    │    │
     ▼    ▼    ▼
   DAY  ROOM TEACHER
          │
          ▼
        BATCH
          │
          ▼
     PRINT / EXPORT
```

---

# 📌 Project Highlights

<p align="center">

| Highlight | Details                         |
| :-------: | :------------------------------ |
|     🎓    | **Academic Project**            |
|     🏫    | **City University**             |
|     💻    | **Laravel + PHP**               |
|    🗄️    | **MySQL Database**              |
|    🏗️    | **MVC Architecture**            |
|     📅    | **Routine Management**          |
|     🔍    | **Schedule Validation**         |
|     📊    | **Multiple Routine Views**      |
|     ✅     | **85% Completed at Evaluation** |

</p>

---

# 🚀 Future Vision

The project can be further developed into a more advanced academic scheduling platform by introducing:

```text
Current System
      │
      ▼
Advanced Validation
      │
      ▼
Automated Optimization
      │
      ▼
AI-Assisted Scheduling
      │
      ▼
Real-Time Notifications
      │
      ▼
Mobile Application
      │
      ▼
Institution-wide Integration
```

---

# 🙏 Acknowledgements

We would like to express our sincere gratitude to our project supervisor **Ahsan Habib**, Lecturer & Coordinator, Department of Computer Science and Engineering, City University, for his valuable guidance, feedback, encouragement, and support throughout the development of this project.

We would also like to thank the **Department of Computer Science and Engineering, City University** for providing the academic environment, resources, and support required to complete this project.

Finally, we are grateful to everyone who contributed directly or indirectly to the successful completion of this academic project.

---

# 📄 License

This project was developed as an **academic project for educational purposes**.

The source code, documentation, and other project materials are intended primarily for learning, academic demonstration, and portfolio purposes.

---

# ⭐ Support

If you find this project useful or interesting, consider giving the repository a ⭐ on GitHub.

Your support is appreciated and helps showcase the project to other developers, students, researchers, and academic institutions.

---

<p align="center">
  <strong>🎓 City University Routine Scheduling Management System</strong>
</p>

<p align="center">
  Academic Project • Computer Science & Engineering • City University
</p>

<p align="center">
  <strong>Developed by the Project Team</strong>
</p>
