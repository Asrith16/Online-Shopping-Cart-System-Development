# Online Shopping Cart System Development

This repository contains the implementation of a **terminal-based shopping cart system** developed using **C++** and **Java**. The project was focused on building a multi-user shopping portal that incorporates fundamental concepts of Object-Oriented Programming (OOP) to handle core functionalities like product search, sorting, and order management.

## Project Overview

The primary goal of this project was to develop an efficient and user-friendly shopping system that operates via a terminal interface. By utilizing C++ for core functionality and Java for additional modular components, this system was designed to simulate the backend operations of an e-commerce platform.

### Key Features:

1. **Object-Oriented Design**:
   - The entire system is built using OOP principles, ensuring modularity, reusability, and maintainability. Classes are designed to represent various entities such as products, users, and shopping carts, facilitating structured interaction and data management.

2. **Product Search and Sorting**:
   - The system allows users to search for products based on multiple criteria, such as category or product name. The products can also be sorted by different attributes like price, quantity, or rating, ensuring a smooth user experience when navigating through the product catalog.

3. **Order Management**:
   - The backend logic efficiently handles order placement, updates product quantities after each purchase, and allows users to view their cart and order summary. Error handling is implemented to manage situations like out-of-stock products or invalid inputs.

4. **Multi-user Support**:
   - The application supports multiple users, each having an independent shopping session. User sessions are managed in a way that ensures data integrity, with each user able to browse, add products to their cart, and finalize their orders independently.

### Project Workflow:

1. **User Authentication**:
   - Upon starting the system, users are authenticated using basic login credentials. New users can register themselves, while existing users can log in to access their shopping cart and previous orders.

2. **Product Catalog Navigation**:
   - Users can browse the available products, filter items by category, and sort them based on attributes like price, rating, or popularity. The catalog is dynamically updated as products are added or removed from the cart.

3. **Cart and Checkout System**:
   - After selecting products, users can view their shopping cart, update quantities, or remove items. The system also allows users to proceed to checkout, where their order is processed, and a final order summary is displayed.

4. **Backend Operations**:
   - Behind the scenes, the application manages data persistence using file handling and ensures the cart state is saved between user sessions. Efficient algorithms are implemented to ensure that search, sort, and checkout operations are handled with minimal delay.

### Technologies Used:

- **C++**: Used for the core backend logic, including managing the product database, implementing sorting/search algorithms, and order management.
- **Java**: Used for creating modular components and handling specific features that complement the core system, such as user authentication and session handling.
- **OOP Principles**: Applied throughout the project to design scalable and maintainable code, focusing on modularity and abstraction.

### Conclusion:

This project successfully demonstrates the development of a terminal-based multi-user shopping cart system using **C++** and **Java**, showcasing proficiency in **Object-Oriented Programming** and backend design. By focusing on efficient search, sort, and order management, this system emulates the backend operations of a functional e-commerce platform while providing a seamless shopping experience for multiple users.
