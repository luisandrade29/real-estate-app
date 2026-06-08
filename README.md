# 🏠 Real Estate Management App

A full-stack real estate platform built with **Spring Boot** (backend) and **React.js** (frontend), featuring RESTful APIs and full database integration via JPA/Hibernate.

---

## 🚀 Tech Stack

| Layer | Technology |
|-------|-----------|
| Backend | Java · Spring Boot · REST API |
| Frontend | React.js · Bootstrap |
| ORM | JPA / Hibernate |
| Database | MySQL |
| Tools | Git · Maven · VS Code |

---

## ✨ Features

- 📋 Property listing and management (CRUD)
- 🔍 Search and filter properties by location, price, type
- 👤 User authentication and role management
- 📊 RESTful API with full documentation
- 🗄️ Relational database with JPA/Hibernate integration
- 📱 Responsive UI with React.js and Bootstrap

---

## 🏗️ Architecture

```
├── backend/                  # Spring Boot application
│   ├── src/main/java/
│   │   ├── controllers/      # REST controllers
│   │   ├── services/         # Business logic
│   │   ├── repositories/     # JPA repositories
│   │   └── models/           # Entity classes
│   └── pom.xml
│
└── frontend/                 # React application
    ├── src/
    │   ├── components/       # Reusable components
    │   ├── pages/            # Page components
    │   └── services/         # API calls
    └── package.json
```

---

## ⚙️ Getting Started

### Prerequisites
- Java 17+
- Node.js 18+
- MySQL 8+

### Backend
```bash
cd backend
# Configure database in src/main/resources/application.properties
./mvnw spring-boot:run
```

### Frontend
```bash
cd frontend
npm install
npm start
```

The app will be available at `http://localhost:3000`

---

## 📡 API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/api/properties` | List all properties |
| GET | `/api/properties/{id}` | Get property by ID |
| POST | `/api/properties` | Create new property |
| PUT | `/api/properties/{id}` | Update property |
| DELETE | `/api/properties/{id}` | Delete property |

---

## 👨‍💻 Author

**Luís Quintas**
- 💼 Salesforce Developer | Full-Stack Java/React
- 🎓 M.Sc. ICT student @ Universidade da Beira Interior
- 🔗 [LinkedIn](https://www.linkedin.com/in/luís-de-andrade-60241a247)
- 📧 quintasluis75@gmail.com

---

## 📄 License

MIT License — feel free to use this project as a reference.
