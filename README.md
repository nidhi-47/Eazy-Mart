# Eazy-Mart
# Project Overview - Online Shop Management Platform

The Online Shop Management Platform is a feature-rich web application designed and developed using the Spring MVC framework. It serves as a comprehensive platform for managing and transacting a diverse range of items. With a strong focus on security, the application implements Role-Based Access Control (RBAC) to provide multiple roles with varying security access levels.

## Features

- **Role-Based Access Control (RBAC):** The application offers different user roles with varying permissions, ensuring secure access to specific functionalities based on user privileges.

- **Cart Functionality:** Users can add items to their shopping cart, review the cart contents, and proceed to checkout for a seamless shopping experience.

- **User Management:** The platform includes user management capabilities, enabling administrators to add, update, and delete user accounts.

- **Wallet Functionality:** Users can manage their wallet, check balances, and perform transactions using the integrated wallet feature.

## Technology Stack

- **Java:** The core language used for application development.
- **Spring MVC Framework:** The backbone of the application, facilitating structured development and clean separation of concerns.
- **Spring Security:** Ensuring a robust authentication and authorization mechanism with role-based access control.
- **MySQL Database:** Storing and retrieving data efficiently using a MySQL backend.
- **Jackson Library:** For seamless JSON processing and serialization, enabling smooth communication between frontend and backend components.

## Functionality and Implementation

### Spring MVC Framework

The application's architecture follows the Model-View-Controller (MVC) pattern, providing a structured and organized codebase. Spring MVC is utilized for handling incoming requests, managing data flow, and rendering appropriate views.

### Role-Based Access Control (RBAC)

Multiple user roles, such as Admin, Customer, and Guest, are implemented using Spring Security. Each role has specific permissions, ensuring secure access and data protection.

### Cart, User, and Wallet Functionality

The Cart functionality is implemented using Spring MVC's controller, allowing users to add items to their cart, review selections, and proceed to checkout. User management includes CRUD operations, enabling administrators to manage user accounts. The Wallet functionality offers seamless fund transactions for registered users.

### Data Access Object (DAO) Pattern

The application effectively handles CRUD operations and data-specific queries using the Data Access Object (DAO) pattern. This design pattern provides a clean separation between business logic and data access layers, enhancing maintainability and scalability.

## Getting Started

To run the application locally, follow these steps:

1. Ensure you have Java and MySQL installed on your system.
2. Clone the repository and import the project into your preferred IDE.
3. Configure the database connection properties in the `application.properties` file.
4. Build and run the application using your IDE or Maven.

For detailed documentation and API references, refer to the project's [Wiki](wiki) section.

## Conclusion

The Online Shop Management Platform offers a user-friendly and secure solution for managing a wide variety of items with distinct user roles and functionalities. Its robust implementation using the Spring MVC framework ensures a smooth and efficient web application experience.


