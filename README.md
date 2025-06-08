# 🎓 Institute Management System (IMS)

> A comprehensive command-line based Institute Management System built with Bash Shell scripting

[![Made with Bash](https://img.shields.io/badge/Made%20with-Bash-1f425f.svg)](https://www.gnu.org/software/bash/)
[![OS Project](https://img.shields.io/badge/Course-Operating%20Systems-blue.svg)](#)
[![University](https://img.shields.io/badge/University-NUCES-green.svg)](#)

## 📋 Table of Contents

- [🎯 Project Overview](#-project-overview)
- [✨ Features](#-features)
- [🔧 OS Concepts Implemented](#-os-concepts-implemented)
- [🚀 Getting Started](#-getting-started)
- [🛠️ System Requirements](#️-system-requirements)
- [🎭 User Roles](#-user-roles)
- [🔍 Demo](#-demo)
- [👤 Contributing](#-contributing)

## 🎯 Project Overview

The **Institute Management System** is a command-line application that simulates a complete educational institution management platform. Built entirely in Bash Shell scripting, it demonstrates core Operating System concepts through practical implementation.

### Key Objectives
- 🏫 Manage students, teachers, courses, and enrollments
- 👨‍💼 Implement role-based access control
- 📈 Handle grading and performance tracking
- 🔄 Demonstrate OS concepts in real-world scenarios

## ✨ Features

### 🔐 Multi-User Authentication
- **Admin Panel**: Complete system control
- **Teacher Portal**: Course and grade management
- **Student Dashboard**: Personal academic tracking

### 📚 Academic Management
- ➕ Create and manage semesters
- 👨‍🎓 Student registration and profiles
- 👩‍🏫 Teacher management
- 📖 Course creation and enrollment
- 📊 Grade calculation and reporting

### 🛡️ Security Features
- Password-protected admin access
- ID-based authentication for users
- Input validation and error handling
- Data integrity checks

## 🔧 OS Concepts Implemented

### 1. 📂 **File Handling**
```bash
# Persistent data storage using CSV files
- student.csv, teacher.csv, course.csv, courseEnroll.csv
- Real-time file read/write/append operations
```

### 2. ⚙️ **Process Control & Execution**
- Menu-driven interface simulating process scheduling
- Function-based modular execution
- Loop control structures for program flow

### 3. 👤 **User Management & Access Control**
- Role-based permission system
- Simulated OS-level privilege management
- Secure authentication mechanisms

### 4. 🔍 **Input Validation & Error Control**
- Conditional logic for data validation
- File existence checks to prevent crashes
- Duplicate record prevention

### 5. 🔄 **Inter-Process Communication (IPC)**
- Function return values as shared memory
- Shared CSV file access between functions

### 6. 📅 **Scheduling Logic**
- Menu selection simulating job scheduling
- Task-specific execution based on user roles

## 🚀 Getting Started

### Prerequisites
- 🐧 Ubuntu/Linux operating system
- 🖥️ Terminal/Shell access
- 📝 CSV file reader (optional, for data viewing)

### Installation

1. **Clone the repository**
```bash
git clone <https://github.com/MudasirNaeem1/Institute-Managment-System-Shell-Script>
cd Institute-Managment-System-Shell-Script
```

2. **Make the script executable**
```bash
chmod +x InstituteManagementSystem.sh
```

3. **Run the application**
```bash
./InstituteManagementSystem.sh
```

### Login Options
1. **Admin Login** - Full system access
2. **Teacher Login** - Course and grade management
3. **Student Login** - Personal dashboard

### Sample Navigation
```
=== Institute Management System ===
1. Admin Login
2. Teacher Login  
3. Student Login
4. Exit
Enter your choice: 1
```

## 🛠️ System Requirements

### Hardware Requirements
- 💾 Minimum 512MB RAM
- 💿 10MB free disk space
- 🖥️ Any computer capable of running Linux

### Software Requirements
- 🐧 **Ubuntu/Linux** (Ubuntu highly preferred)
- 🖥️ **Bash Shell** (pre-installed on most Linux systems)
- 📊 **CSV Reader** (optional - LibreOffice Calc, Excel, etc.)

### Verification Commands
```bash
# Check Bash version
bash --version

# Verify script permissions
ls -la InstituteManagementSystem.sh
```

## 🎭 User Roles

### 👨‍💼 Admin
- ✅ Create/modify/delete students and teachers
- 📋 Manage courses and semesters
- 👀 View all system data
- 🔧 System configuration

### 👩‍🏫 Teacher
- 📚 View assigned courses
- 👥 Manage course enrollments
- 📝 Update student grades
- 📊 Generate grade reports

### 👨‍🎓 Student
- 📖 View enrolled courses
- 📈 Check grades and performance
- 📋 View personal academic record
- 📊 Track semester progress

## 🔍 Demo 

```
┌─────────────────────────────────────┐
│     Institute Management System     │
├─────────────────────────────────────┤
│  1. Admin Login                     │
│  2. Teacher Login                   │
│  3. Student Login                   │
│  4. Exit                            │
└─────────────────────────────────────┘
Enter your choice: _

```

## 👤 Contributing

We welcome contributions! 

  Interested in educational AI research? ⭐ **Star this repository!**
  
  Have questions about the implementation? 💭 **Let's discuss!**
  
</div>
<div align="center">  
  
  Found this project interesting? ⭐ **Star the repository!**
  
  Have suggestions? 💭 **Reach out!**
  
  ![Visitors](https://visitor-badge.laobi.icu/badge?page_id=MudasirNaeem1.Institute-Managment-System-Shell-Script)
</div>
