# 🏡 AI-Powered Real Estate Platform — EstateAI

An AI-powered real estate platform designed to simplify property discovery, improve buyer–agent communication, and streamline property management through modern web technologies and machine learning.

## 📌 Overview

**EstateAI** is a full-stack real estate platform that connects property buyers with agents while providing tools for property listings, bookings, user management, and revenue tracking.

The system consists of three separate applications: a Buyer and Agent Website, an Admin Panel, and a FastAPI Backend. It also integrates AI-powered property discovery, personalized recommendations, and property price prediction to enhance the real estate experience.

## 📂 Project Repositories

The project is divided into three repositories for maintainable development and separation of responsibilities.

### 🌐 1. Buyer and Agent Website

The main web application for buyers and agents to discover properties, manage listings, book viewings, and communicate with each other.

🔗 **GitHub Repository:** [realstate-WebSite](https://github.com/DonShanilka/realstate-WebSite)

### 🛡️ 2. Admin Panel

A separate administrative application for managing platform users, agents, properties, bookings, and revenue-related information.

🔗 **GitHub Repository:** [real-estate-platform-admin-pannel](https://github.com/DonShanilka/real-estate-platform-admin-pannel)

### ⚙️ 3. Backend API

The FastAPI backend responsible for REST APIs, database operations, authentication, authorization, real-time messaging, and AI-powered property services.

🔗 **GitHub Repository:** [real-estate-backend](https://github.com/DonShanilka/real-estate-backend)

## ✨ Key Features

### 🏠 Property Management

- Browse and explore property listings
- Search and filter properties
- View detailed property information
- Manage property listings and related information

### 🤖 AI-Powered Features

- **Natural-Language Property Search:** Find properties using descriptive search queries with rule-based search logic.
- **AI Property Assistant:** Answer property-related questions using available database information.
- **Property Recommendations:** Recommend relevant properties using content-based recommendation techniques.
- **Property Price Prediction:** Predict property prices using a Random Forest regression model built with scikit-learn.

### 👥 User and Agent Management

- User authentication and profile management
- Role-based access control
- Agent management
- Separate administrative functionality

### 📅 Booking Management

- Book property viewings
- Manage viewing requests and bookings
- Track booking information

### 💬 Real-Time Communication

- Real-time buyer–agent messaging
- WebSocket-based communication
- Property-related conversations

### 📊 Admin Dashboard

- User and agent management
- Property and booking oversight
- Revenue tracking and platform analytics

## 🛠️ Technology Stack

### Frontend

- Next.js
- React
- TypeScript
- Tailwind CSS

### Backend

- Python
- FastAPI
- SQLAlchemy
- REST APIs
- WebSockets

### Database and Security

- MySQL
- JWT Authentication
- Role-Based Access Control (RBAC)

### Artificial Intelligence and Machine Learning

- Python
- scikit-learn
- CountVectorizer
- Cosine Similarity
- Random Forest Regression

### Development Tools

- Git
- GitHub
- Postman

## 🔐 Security

- JWT-based authentication
- Role-based authorization
- Protected API endpoints
- Access control for different user roles

## 🚀 Getting Started

Clone the repositories individually.

### Buyer and Agent Website

```bash
git clone https://github.com/DonShanilka/realstate-WebSite.git
```

### Admin Panel

```bash
git clone https://github.com/DonShanilka/real-estate-platform-admin-pannel.git
```

### Backend

```bash
git clone https://github.com/DonShanilka/real-estate-backend.git
```

Follow the setup instructions in each repository to configure environment variables, install dependencies, connect to the database, and run the applications.

## 🎯 Project Goals

- Improve property discovery through intelligent search.
- Help buyers identify suitable properties using recommendations.
- Provide data-driven property price estimates.
- Enable efficient communication between buyers and agents.
- Centralize administrative management and revenue tracking.
- Maintain a modular architecture with separate frontend applications and a shared backend.

## 👨‍💻 Developer

**Nishith Shanilka**

- GitHub: [@DonShanilka](https://github.com/DonShanilka)
- LinkedIn: [Nishith Shanilka](https://www.linkedin.com/in/NishithShanilka/)

## 📄 License

A license has not yet been specified for this project.
