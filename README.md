# TastyBuddy Backend

TastyBuddy is a Spring Boot-based backend application designed to power the TastyBuddy platform. It manages the core business logic, API endpoints, and data configurations for the service.

## 🚀 Tech Stack

*   **Java:** 21
*   **Framework:** Spring Boot
*   **Build Tool:** Maven

## 📋 Prerequisites

Before you begin, ensure you have the following installed:
*   Java Development Kit (JDK) 17 or higher
*   Apache Maven (or use the included Maven Wrapper)

## 🛠️ Getting Started

### 1. Clone the Repository
```bash
git clone [https://github.com/rushikesh028/tastybuddy-backend.git](https://github.com/rushikesh028/tastybuddy-backend.git)
cd tastybuddy-backend


tastybuddy-backend/
├── .mvn/                # Maven Wrapper files
├── src/
│   ├── main/
│   │   ├── java/        # Java source files (Controllers, Services, Repositories, Models)
│   │   └── resources/   # Application configuration (application.properties)
│   └── test/            # Unit and integration tests
├── mvnw                 # Maven wrapper script for Linux/macOS
├── mvnw.cmd             # Maven wrapper script for Windows
└── pom.xml              # Maven project object model dependencies


## 🔧 Configuration & Environment

The application relies on standard Spring configurations. Before running the service, ensure you have:
*   Configured your database credentials in `src/main/resources/application.properties`.
*   Verified that port `8080` (or your configured custom port) is available.

## 🤝 Contributing

Contributions are welcome! If you find a bug, have an optimization idea, or want to request a new feature:
1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.
