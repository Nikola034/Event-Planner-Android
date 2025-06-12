# 📱 EventPlanner - Android

A native Android application for the **EventPlanner** platform — developed using Android Studio with modern best practices, providing on-the-go access to event planning features and real-time updates.

---

## 📋 Table of Contents
- [About the Project](#about-the-project)
- [Architecture & Features](#architecture--features)
- [Tech Stack](#tech-stack)
- [Code Quality](#code-quality)
- [My Contributions](#my-contributions)

---

<a name="about-the-project"></a>
## 📖 About the Project

The **Android** repository contains the Android app for **EventPlanner**, offering:
- 🎤 Event Organizers — create, edit, and manage events and participants  
- 🎫 Authenticated Users — browse, register for events, and manage profiles  
- 🛠️ Service/Product Providers — manage their offerings  
- 👤 Guests — browse events and services  
- 🛡️ Admins — monitor system status and users  

The app integrates with backend APIs, supports JWT authentication, and leverages real-time communication through WebSockets.

- [EventPlanner Backend](https://github.com/Nikola034/Event-Planner-Backend)  
- [EventPlanner Frontend](https://github.com/Nikola034/Event-Planner-Frontend) 
- [EventPlanner Selenium Tests](https://github.com/Nikola034/Event-Planner-Selenium-Tests)

---

<a name="architecture--features"></a>
## 🧱 Architecture & Features

### 📱 Android Architecture
- Developed in **Android Studio** using Java 
- Follows MVVM pattern with ViewModels and LiveData  
- Modularized codebase for maintainability and scalability  

### 🔗 API & Authentication
- RESTful API communication with backend services using Retrofit  
- JWT-based authentication and token management  
- Role-based access control for navigation and feature availability  

### 📲 User Interface
- Intuitive, responsive UI with Material Design components  
- Navigation Drawer and Bottom Navigation for easy access  
- Real-time event updates via WebSocket integration  
- Support for offline caching and data synchronization  

---

<a name="tech-stack"></a>
## 🧰 Tech Stack

| Category       | Technologies Used                   |
|----------------|-----------------------------------|
| **Language**   | Java                             |
| **IDE**        | Android Studio                   |
| **Architecture**| MVVM, LiveData, ViewModel        |
| **Networking** | Retrofit, OkHttp                  |
| **Authentication**| JWT                            |
| **Real-Time**  | WebSockets                       |
| **UI Components**| Material Design                  |

---

<a name="code-quality"></a>
## 🧪 Code Quality

- 📏 Clean code with clear separation of concerns  
- 🔄 Code reviews with pull requests to maintain quality  
- 🗂️ Agile development tracked on Trello with sprint retrospectives  

---

<a name="my-contributions"></a>
## 👨‍💻 My Contributions

- 📱 Developed core event management screens and workflows  
- 🔐 Implemented secure JWT authentication and session handling  
- 🌐 Implemented CRUD for events, reservations and products
- 🛠️ Worked on service and product management features  
- 🤝 Collaborated on UI/UX improvements and feedback cycles  
