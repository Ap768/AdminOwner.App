# Admin Owner Management System

A Spring Boot web application for managing Admins, Owners, and Properties.

## Tech Stack
- Java 17
- Spring Boot
- Spring MVC
- Spring Data JPA
- MySQL
- Thymeleaf
- HTML / CSS

## How to Run
1. Create database:
   CREATE DATABASE admin_owner_db;
2. Update MySQL credentials in application.properties
3. Run:
   AdminOwnerAppApplication
4. Open:
   http://localhost:8080/login

## Admin Login
Email: admin@gmail.com  
Password: admin123  

## Flow
- Admin logs in
- Admin creates Owner
- Owner logs in
- Owner adds / updates / deletes properties

## Features
- Role based login (Admin / Owner)
- Property CRUD
- Success messages
- Chatbot support
