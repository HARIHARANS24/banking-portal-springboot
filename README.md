# 🏦 Banking Portal Application

A modern banking portal application built with Spring Boot, providing secure and efficient banking operations.

## ✨ Features
- User Authentication and Authorization 
- Account Management
- Transaction Processing 
- Secure Banking Operations
- Real-time Balance Updates 
- Transaction History
- User Profile Management 
   
## 🛠 Technologies Used 
- Java 17 
- Spring Boot
- Spring Security
- Spring Data JPA
- MySQL Database
- Maven
- Thymeleaf
- Bootstrap
- HTML/CSS/JavaScript

## 📁 Project Structure
```
banking-app/
├── 📁 src/
│   ├── 📁 main/
│   │   ├── 📁 java/
│   │   │   └── 📁 com/
│   │   │       └── 📁 example/
│   │   │           └── 📁 bankapp/
│   │   │               ├── 📁 config/
│   │   │               │   └── 📄 SecurityConfig.java
│   │   │               ├── 📁 controller/
│   │   │               │   └── 📄 BankController.java
│   │   │               ├── 📁 model/
│   │   │               │   ├── 📄 Account.java
│   │   │               │   └── 📄 Transaction.java
│   │   │               ├── 📁 repository/
│   │   │               │   ├── 📄 AccountRepository.java
│   │   │               │   └── 📄 TransactionRepository.java
│   │   │               ├── 📁 service/
│   │   │               │   └── 📄 AccountService.java
│   │   │               └── 📄 BankappApplication.java
│   │   └── 📁 resources/
│   │       ├── 📁 static/
│   │       ├── 📁 templates/
│   │       └── 📄 application.properties
│   └── 📁 test/
├── 📄 pom.xml
├── 📄 mvnw
├── 📄 mvnw.cmd
└── 📄 .gitignore
```

### 📂 Key Directories and Files
- `src/main/java/com/example/bankapp/` - Main application source code
  - `config/` - Configuration classes
    - `SecurityConfig.java` - Spring Security configuration
  - `controller/` - REST API controllers
    - `BankController.java` - Handles banking operations endpoints
  - `model/` - Entity classes
    - `Account.java` - Account entity with user details
    - `Transaction.java` - Transaction entity for banking operations
  - `repository/` - Data access layer
    - `AccountRepository.java` - Account data access operations
    - `TransactionRepository.java` - Transaction data access operations
  - `service/` - Business logic layer
    - `AccountService.java` - Core banking business logic
  - `BankappApplication.java` - Application entry point
- `src/main/resources/` - Application resources
  - `static/` - Static assets (CSS, JS, images)
  - `templates/` - Thymeleaf templates
  - `application.properties` - Application configuration

## 🚀 Getting Started

### Prerequisites
- Java 17 or higher
- Maven
- MySQL Database

### Installation
1. Clone the repository
```bash
git clone https://github.com/HARIHARANS24/banking-portal-springboot.git
```

2. Navigate to project directory
```bash
cd banking-portal-springboot
```

3. Configure database in `application.properties`

4. Build the project
```bash
mvn clean install
```

5. Run the application
```bash
mvn spring-boot:run
```

## 📚 API Documentation
The API documentation is available at `/swagger-ui.html` when running the application.

## 🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Authors
- **HARIHARANS24** - *Initial work* - [GitHub Profile](https://github.com/HARIHARANS24)

## 🙏 Acknowledgments
- Spring Boot Team
- All contributors who have helped shape this project 
