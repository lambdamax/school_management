# School Management System

## Table of Contents
- [School Management System](#school-management-system)
  - [Table of Contents](#table-of-contents)
  - [Overview](#overview)
  - [Features](#features)
  - [Technologies Used](#technologies-used)
  - [Main Classes](#main-classes)
  - [Example Usage](#example-usage)
  - [Getting Started](#getting-started)
  - [Requirements](#requirements)
  - [License](#license)

## Overview
This project is a Python-based simulation of a school management system. It models real-world entities such as students, teachers, and courses, allowing users to:
- Manage students, teachers, and courses
- Assign grades and simulate friendships
- Display a summary of the school environment
The simulation is interactive and extensible, making it suitable for educational purposes or as a foundation for more advanced school management applications.

## Features
- Object-oriented design for easy extension
- Add and manage students, teachers, and courses
- Assign teachers to courses
- Enroll students in courses
- Assign and update grades for students
- Simulate friendships among students
- Display a summary of students, grades, favorite subjects, and friendships
- Example Jupyter notebook for running simulations

## Technologies Used
- Python 3.8+
- Object-Oriented Programming (OOP)

## Main Classes
- `Person`: Base class for all people in the school
- `Student`: Inherits from `Person`, tracks grades, favorite subject, and friends
- `Teacher`: Inherits from `Person`, manages courses taught
- `Course`: Holds course name, teacher, and enrolled students
- `School`: Manages all students, teachers, and courses; simulates grades and friendships

## Example Usage
See `test_school.ipynb` for a step-by-step simulation:
1. Create a school, courses, teachers, and students
2. Assign teachers to courses and enroll students
3. Simulate grades and friendships
4. Display a summary of the school environment

## Getting Started
1. Clone the repository:
  ```bash
  git clone [repo_url]
  ```
2. Open `test_school.ipynb` in Jupyter or VS Code to run the simulation interactively.
3. Alternatively, use `school_management.py` to extend or customize the system in your own scripts.

## Requirements
- Python 3.8+
- No external dependencies

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
