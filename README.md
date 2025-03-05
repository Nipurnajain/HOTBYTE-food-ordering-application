# HotByte - Full-Stack Web Application

HotByte is a full-stack web application designed to provide customers with a seamless and user-friendly platform for ordering food online. The platform enables restaurants to manage their menus and orders efficiently while offering real-time order tracking and notifications to customers.

## Features

### User Features
1. **User Registration & Authentication**: Secure user signup and login using JSON Web Tokens (JWT).
2. **Menu Browsing**: Explore categorized menu items with descriptions, prices, and images.
3. **Cart Management**: Add, remove, and manage items before checkout.
4. **Order Placement**: Place orders and receive email notifications.
5. **Order Tracking**: Real-time order status updates via email.
6. **Order History**: View past orders and details.

### Restaurant Features
1. **Restaurant Management**: Add, edit, and delete menu items.
2. **Discount Management**: Set discount prices for specific items.
3. **Order Processing**: View and update order status.
4. **Order History**: Track past orders.

### Admin Features
1. **User & Restaurant Management**: Add, remove, and manage user and restaurant accounts.
2. **Menu & Order Management**: View all menu items, restaurants, and orders.

## Technologies Used

### Frontend
- HTML, CSS, Bootstrap, Angular

### Backend
- Java, Spring Boot

### Database
- MySQL / SQL Server

### Authentication
- JSON Web Tokens (JWT) for secure user authentication

## Development Process

1. **User & Restaurant Registration/Login**
2. **Secure authentication with JWT**
3. **Restaurant account creation & management**
4. **User Dashboard**
   - Browse menu categories & search items
   - Add items to cart & checkout securely
5. **Restaurant Dashboard**
   - Menu creation & management
   - Order tracking & status updates
6. **Admin Dashboard**
   - User & restaurant account management
   - Menu & order supervision

## Security & Compliance

- **Secure user authentication using JWT**
- **Role-based access control for users, restaurants, and admins**
- **Data validation and secure storage for sensitive information**

## Getting Started

### Prerequisites
- Java Development Kit (JDK)
- Node.js and npm
- Angular CLI
- MySQL / SQL Server

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/HotByte.git
   cd HotByte
   ```

2. **Backend Setup**
   - Navigate to the backend directory
   - Configure the `application.properties` file with your database credentials
   - Build and run the Spring Boot application
     ```bash
     mvn clean install
     mvn spring-boot:run
     ```

3. **Frontend Setup**
   - Navigate to the frontend directory
   - Install dependencies
     ```bash
     npm install
     ```
   - Run the Angular application
     ```bash
     ng serve
     ```

4. **Database Setup**
   - Import the provided SQL script to set up the database schema
   - Ensure the database is running and accessible

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/YourFeatureName`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/YourFeatureName`)
5. Open a pull request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to all contributors who have helped in the development of HotByte.
- Special thanks to the open-source community for providing valuable resources and tools.

---

Feel free to reach out if you have any questions or need further assistance!
