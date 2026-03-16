Microservices Backend System

A scalable backend system built using microservices architecture where different services operate independently and communicate through REST APIs. This project demonstrates how large applications can be structured into smaller, maintainable services.
Built using Python and the Django framework.

This project implements a microservices-based backend system where each service handles a specific domain such as users, products, and orders.
Each service:
- Runs independently
- Has its own logic and endpoints
- Communicates via REST APIs
- This architecture improves scalability, maintainability, and development speed.

Architecture: 

Client (Web / Mobile)
        |
     API Requests
        |
---------------------------------
|         |          |
User    Product     Order
Service  Service    Service
:8001    :8002      :8003

Features

- Microservices-based backend architecture
- Independent services for different functionalities
- REST API communication between services
- Scalable and modular system design
- Clean project structure

Technologies Used

- Python
- Django
- Git
- REST APIs
