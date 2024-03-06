# Microservices Project
This GitHub repository encompasses an extensive microservices-based backend solution for a hotel service application, meticulously crafted using the Spring Boot framework. The project is comprised of three distinct microservices: UserService, HotelService, and RatingService. Additionally, it integrates crucial components such as API Gateway, Config Server, Discovery Client, Service Registry, Feign Client, Resilience4j Circuit Breaker, Retry Mechanism, Rate Limiter, and Spring Security with Okta. To ensure reliability and functionality, all endpoints have undergone rigorous testing using Postman.

# Microservices
- UserService: Responsible for managing user-related operations, including user registration and user profile management.
- HotelService: Handles the various functionalities associated with hotels, ensuring efficient management.
- RatingService: Facilitates the submission and retrieval of hotel ratings and reviews by users.

# Components
The project leverages several components to augment its functionality:

- API Gateway: Serves as a centralized entry point for all client requests, efficiently directing them to the respective microservices.
- Config Server (GitHub): Centralizes configuration management, retrieving configurations from a GitHub repository to simplify the management and modification of settings.
- Discovery Client: Allows microservices to dynamically discover and communicate with each other, eliminating the need for hardcoding service locations.
- Service Registry (Spring Eureka): Employs Spring Eureka to enable microservices to register themselves and facilitates service discovery.
- Feign Client (Spring Cloud Routing): Provides a declarative approach to API calls between microservices, streamlining inter-service communication.
- Netflix Eureka Client (Spring Cloud): Utilized for registering microservices with the Eureka Service Registry, enhancing service discovery capabilities.
- Resilience4j Circuit Breaker: Implements the Resilience4j Circuit Breaker pattern to prevent cascading failures and enhance fault tolerance during remote service calls.
- Retry Mechanism: Automates the retrying of failed requests, bolstering the overall reliability of the system.
- Rate Limiter: Controls the rate of incoming requests to prevent overloading the microservices.
- Spring Security with Okta: Integrates Spring Security with Okta for robust authentication and authorization, ensuring secure access to the microservices.
