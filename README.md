# 🍔 Food Delivery System – Java Spring Boot Microservices

The **Food Delivery System** is a backend microservices-based application developed using **Java Spring Boot**.  
It simulates a real-world online food ordering and delivery platform where users can browse restaurants, place orders, make payments, and track deliveries.

This project demonstrates **real-world microservices architecture**, backend design patterns, and scalable system design.

---

## 🚀 Features

- User registration and login
- Restaurant and menu management
- Food ordering system
- Order status tracking
- Payment processing
- Delivery partner assignment
- Scalable microservices architecture

---

## 🧩 Microservices Architecture

| Service Name | Responsibility |
|-------------|---------------|
| User Service | User registration & profile |
| Restaurant Service | Restaurant & menu management |
| Order Service | Order creation & tracking |
| Payment Service | Payment processing |
| Delivery Service | Delivery assignment & tracking |
| API Gateway | Central request routing |
| Config Server | Centralized configuration |
| Eureka Server | Service discovery |

---

## 🔧 Tech Stack

- Java 17  
- Spring Boot  
- Spring Cloud (Eureka, Gateway, Config Server)  
- Spring Data JPA  
- MySQL  
- REST APIs  
- Maven  
- Docker (optional)

---

## 📂 Project Structure

food-delivery-system
│
├── user-service
├── restaurant-service
├── order-service
├── payment-service
├── delivery-service
├── api-gateway
├── config-server
├── eureka-server
└── README.md


---

## 🔄 Food Order Workflow

1. User registers and logs in  
2. User browses restaurants and menus  
3. User places a food order  
4. Payment Service processes payment  
5. Order Service updates order status  
6. Delivery Service assigns delivery partner  
7. User tracks order until delivery  

---

## 🛠️ How to Run the Project

### Prerequisites
- Java 17+
- Maven
- MySQL
- IDE (IntelliJ / Eclipse)

### Steps

1. Clone the repository
   ```bash
   git clone https://github.com/your-username/food-delivery-system.git


Configure database details in application.yml

Start services in the following order:

Config Server

Eureka Server

All Microservices

API Gateway

📌 Sample API Endpoints

POST /users/register → Register user

GET /restaurants → List restaurants

GET /menus/{restaurantId} → View menu

POST /orders → Place order

POST /payments/pay → Make payment

GET /delivery/{orderId} → Track delivery

🎯 Purpose of This Project

Learn Spring Boot Microservices

Understand food delivery business logic

Practice order & payment workflows

Build resume & interview-ready project

📈 Future Enhancements

JWT authentication & authorization

Kafka-based event-driven architecture

Real-time order tracking using WebSockets

Redis caching

Docker & Kubernetes deployment

Admin & Restaurant dashboards

👨‍💻 Author

Developed by Java Backend Developer
Focused on Spring Boot, Microservices, and Scalable Backend Systems

⭐ If you find this project useful, please give it a star!

