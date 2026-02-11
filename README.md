# 📅 Timetable Management Application | IFRI Integration Project 2022-2023 

A modern web application for managing and planning timetables for students, teachers, and administrators. Built with **Django**, this app allows real-time timetable management, role-based dashboards, and smooth user experience.  

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Django](https://img.shields.io/badge/Django-4.2-green.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

## 📋 Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## ✨ Features

### 🎯 Core Features
- **Role-based dashboards**: Admin, Teacher, Student
- **Timetable management**: Create, update, view timetables
- **User authentication**: Secure login for different roles
- **History tracking**: Keep records of recent timetables

### 🎨 User Interface
- **Modern and responsive design**: Works on desktop and mobile
- **Interactive dashboards**: View statistics and schedules at a glance
- **Previews**: Quick access to timetables and schedule details

### 🔧 Technical Features
- **Built with Django**: Reliable web framework
- **SQLite database**: Lightweight and easy to setup
- **Secure password handling**: Django built-in auth system
- **Extensible architecture**: Easy to add new roles or features

## 🚀 Installation

### Prerequisites
- Python 3.8+
- pip
- Django installed (`pip install Django`)

### Steps

```bash
# Clone the repository
git clone https://github.com/v1p3r75/PIL1_2223_4.git
cd PIL1_2223_4

# Apply database migrations
python manage.py migrate

# Run the server
python manage.py runserver 8000
