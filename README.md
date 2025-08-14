# Academic Course & Grade Management System

A web-based platform to manage user authentication, course information, and student grades.

## Features

- **Authentication & Access Control** – Secure login/signup with role-based permissions.
- **User Dashboards** – Separate interfaces for students, faculty, and admins.
- **Course Management** – View, add, edit, and manage course details.
- **Grades Management** – Faculty can input/update grades; students can view their grades.
- **Admissions** – Manage and display enrollment information.
- **Navigation & UI** – User-friendly interface with intuitive navigation.

## Architecture

The system follows a **microservices architecture** with dedicated modules for:
- **Authentication Service**
- **Course Management Service**
- **Grade Tracking Service**

This design supports **scalability** and **maintainability**, allowing each service to be developed, deployed, and scaled independently.
