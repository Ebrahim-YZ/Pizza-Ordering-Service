# Pizza-Ordering-Service

This is a full-stack web application built using React.js (frontend) and Node.js with Express (backend), along with PostgreSQL for data storage. The app allows users to order pizzas with customizable toppings, register multiple restaurants, and implements role-based access control (RBAC) for different user roles such as Customers and Restaurant Managers.

Key Features:
User Management: Customer and restaurant manager registration, authentication (JWT-based).
Pizza & Toppings Management: Dynamic creation and management of pizzas and toppings by restaurant managers.
Order Management: Customers can place orders and track them. Managers can view and update order statuses.
Role-Based Access Control: Implemented using CASL for managing permissions based on user roles.

Tech Stack:
Frontend: React.js, Material UI, Material React Table
Backend: Node.js, Express, PostgreSQL
Validation: Zod
Authorization: CASL