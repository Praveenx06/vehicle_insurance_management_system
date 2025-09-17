"# vehicle_insurance_management_system" 

Short description :

A web-based Vehicle Insurance Management System that allows users to manage vehicles, proposals, policies, add-ons and payments. The application supports role-based authentication (Admin and User), navigation and routing, and a layered architecture with a Spring Boot backend using JWT-based authentication.

Features : 

User registration and login (JWT authentication)

Role-based access control: Admin and User

CRUD operations for Vehicle entity

Create and manage Proposals (user-submitted insurance requests)

Issue and manage Policies from proposals

Add and configure Add-ons for policies

Payment flow for purchasing policies or add-ons

Clean navigation and routing in the frontend (separate flows for Admin and User)

Layered architecture (Controller → Service → Repository) for maintainability

Tech Stack

Backend: Spring Boot (REST API), Spring Security (JWT), Hibernate / Spring Data JPA

Database: MySQL

Frontend: React 19 vite — routing and role-based UI flows
