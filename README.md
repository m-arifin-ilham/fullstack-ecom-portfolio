## Overview: Building the Digital Backbone for E-commerce

This prototype showcases a collection of interconnected projects designed to form the backend and a core analytical frontend for a modern e-commerce platform. The goal is to demonstrate proficiency in building robust, scalable, and data-driven web applications by separating concerns into specialized services.

### The Business Scenario: An Online Bookstore's Digital Foundation 📚

Imagine a growing online bookstore that needs a solid digital infrastructure to manage its products, handle user accounts, and track sales performance. This collection of projects addresses these critical needs:

1. **Managing the Book Catalog:** A centralized system to store and organize all available books, their prices, and inventory levels.

2. **Handling User Accounts:** A secure way for customers to register, log in, and manage their profiles.

3. **Tracking Sales & Insights:** A system to record every book sale and provide real-time analytical insights into sales trends and product performance.

These projects collectively form the digital backbone, allowing the online bookstore to operate efficiently, securely, and make data-driven decisions.

## Architectural Overview

Here's a high-level view of how these services interact:
![E-commerce Platform Architecture](assets/ecom_architecture_diagram.png)

## Individual Projects

Each project in this portfolio is a standalone repository, developed with a focus on best practices, clean architecture, and specific functionalities.

### 1. User Management RESTful API (Flask Backend)

* **Repository:** [User Management API GitHub Repo](https://github.com/m-arifin-ilham/User-Management-API)

* **Description:** A secure and scalable backend API for managing user accounts. It features robust user registration, login with JWT access and refresh tokens, role-based authorization, and secure password management. This API serves as the central authentication and user profile service for the entire e-commerce ecosystem.

* **Key Skills Showcased:** Python, Flask, RESTful APIs, JWT Authentication, API Security, Layered Architecture, SOLID Principles.

### 2. Product Catalog API (Django Backend)

* **Repository:** [Product Catalog API GitHub Repo](https://github.com/m-arifin-ilham/Product-Catalog-API)

* **Description:** A feature-rich RESTful API built with Django and Django REST Framework (DRF) for managing a comprehensive product catalog. It supports full CRUD operations for products and categories, advanced filtering, dynamic sorting, and basic inventory management (including a custom purchase endpoint). This API provides the core product data for the e-commerce platform.

* **Key Skills Showcased:** Python, Django, Django REST Framework, ORM, Advanced Filtering & Sorting, API Documentation (drf-yasg).

### 3. Simple Sales Tracker (Flask Backend & React Frontend)

* **Frontend Repository:** [Sales Tracker Frontend GitHub Repo](https://github.com/m-arifin-ilham/Sales-Tracker-Frontend)

* **Backend Repository:** [Sales Tracker Backend GitHub Repo](https://github.com/m-arifin-ilham/Sales-Tracker-Backend)

* **Description:** A full-stack web application that allows users to record new sales and visualize sales data. The Flask backend stores sales records and integrates with the Product Catalog API to decrement stock. The React frontend provides a user-friendly interface for data input and displays interactive charts (total revenue, sales by product) for quick insights.

* **Key Skills Showcased:** Python (Flask), React, Full-Stack Development, API Integration, Data Visualization (Recharts), Responsive UI (Tailwind CSS).

## Technologies Across the Portfolio

This portfolio demonstrates versatility across various Python and JavaScript technologies:

* **Backend:** Python (Flask, Django, Django REST Framework, Gunicorn)

* **Frontend:** React, Vite, Tailwind CSS, Axios, Recharts

* **Databases:** SQLite (for local development), PostgreSQL (for deployment consideration)

* **Security:** Bcrypt, JWT

* **Development Practices:** RESTful API Design, Layered Architecture, SOLID Principles, Test-Driven Development (TDD), Version Control (Git)

## Getting Started with the Ecosystem

To run this entire ecosystem locally, you would typically:

1. Clone each individual repository.

2. Follow the setup instructions in each repository's `README.md`.

3. Ensure your backend APIs are running (User Management, Product Catalog, Sales Tracker backend).

4. Start your frontend application.

## Future Vision

This portfolio represents a foundational infrastructure. Future enhancements could include:

* Full deployment of all services to a cloud platform (e.g., Render, AWS).

* Integration of the User Management API for user-specific sales tracking and authentication in the Sales Tracker frontend.

* Implementing a shopping cart and checkout process in the frontend, consuming the Product Catalog API.

* Adding more advanced analytics and machine learning models for sales forecasting or customer segmentation.

*Developed by [Muhammad Arifin Ilham](https://www.linkedin.com/in/arifin-ilham-at-ska/)*
*Current Date: August 9, 2025