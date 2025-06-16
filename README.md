# eureka-student-microservice


# Student Microservice - Eureka Client (GET Endpoint)

This is a simple Spring Boot microservice that registers itself with a Eureka Discovery Server and exposes a RESTful `GET` endpoint for retrieving static student information.

## 📌 Description

This microservice demonstrates a basic implementation of a REST API within a microservices architecture using **Spring Boot** and **Spring Cloud Eureka**. It is intended as a reference example for setting up a Eureka client and testing a basic `GET` request using **Postman**.

## ✅ Features

- Exposes a `GET` endpoint at `/student`
- Returns a static student object in JSON format
- Runs on port `8080`
- Ready to register with Eureka server (port `8761`) if available

## 🔗 Endpoint

```http
GET http://localhost:8080/student
