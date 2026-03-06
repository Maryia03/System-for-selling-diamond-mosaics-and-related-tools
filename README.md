# System for selling diamond mosaics and related tools
A full-stack web application for browsing and managing mosaics.
The system allows users to view mosaics on the main page with filtering and sorting, while administrators can add new mosaics through an admin interface.

## 🛠️ Technologies
- Java 17
- Spring Boot
- React
- MySQL
- JWT authentication
- Docker

## 🧑‍💻 Features
- User:
  - Register and log in
  - Browse diamond mosaics and tools
  - View mosaic and tool pages
  - Search mosaics using filters (size, price)
  - Search tools using filters (price)
  - Add mosaics and tools to cart
  - Make orders
  - View past orders and current orders

- Admin:
  - Add new mosaics and tools
  - Edit mosaic and tools information
  - Delete mosaics and tools
  - View and manage customer orders
  - Update order status
  - Block / unblock users
  - Manage users accounts

## ⚙️ Running the Project
- Backend:
  - cd backend
  - ./mvnw spring-boot:run
- Frontend:
  - cd frontend
  - npm start
- Docker:
  - docker compose up --build

