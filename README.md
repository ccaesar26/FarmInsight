# FarmInsight - Intelligent Platform for Agricultural Farm Management

**Author:** Cezar Constăndoiu

**Scientific Coordinator:** Conf. dr. Alexandra Băicoianu

**Institution:** Universitatea Transilvania din Brașov, Facultatea de Matematică și Informatică

**Project:** Bachelor's Thesis (Lucrare de Licență), 2025

---

## About The Project

**FarmInsight** is a distributed software platform designed to facilitate modern digital management in agricultural farms. The project is the result of my Bachelor's Thesis and aims to demonstrate how modern information technology can support the efficiency and digital transformation of the agricultural sector.

The system integrates two complementary applications:
*   A **complex web interface** for farm managers, enabling detailed plot monitoring, crop cycle management, task planning, and employee administration.
*   A **native Android mobile application** for field workers, ensuring enhanced accessibility to relevant information and daily assigned tasks.

Real-time data synchronization between the two components is achieved using **SignalR**. The entire solution is built upon a modern **microservices architecture**, utilizing robust and scalable technologies like ASP.NET Core for the backend, Angular for the web frontend, and Kotlin with Jetpack Compose for the mobile application.

### Project Repositories

This project is split into three separate repositories, each containing a specific component of the platform:

| Component | Description | Repository Link |
| :--- | :--- | :---: |
| 🖥️ **Backend** | Contains all the microservices built with ASP.NET Core, the API Gateway, and the logic for data processing and persistence. | **[Backend Repository](https://github.com/ccaesar26/FarmDotNetApi)** |
| 🌐 **Frontend** | The Angular single-page application for farm managers, featuring dashboards, maps, and management tools. | **[Frontend Repository](https://github.com/ccaesar26/FarmWebUI)** |
| 📱 **Mobile** | The native Android application for field workers, built with Kotlin and Jetpack Compose. | **[Mobile Repository](https://github.com/ccaesar26/FarmMobileApp)** |

### High-Level Architecture

The platform is designed as a distributed system with the following key components:

![System Architecture Diagram](https://github.com/ccaesar26/FarmInsight/blob/main/architecture-diagram.png) 

### Core Technologies

*   **Backend:** .NET 9, C# 13, ASP.NET Core Web API, Entity Framework Core
*   **Frontend:** Angular 19, TypeScript, RxJS, Angular Signals, PrimeNG
*   **Mobile:** Kotlin, Jetpack Compose, MVVM, Ktor Client, Coroutines
*   **Database:** PostgreSQL (one database per microservice)
*   **Real-time Communication:** SignalR
*   **Asynchronous Communication:** RabbitMQ (for inter-service events)
*   **API Gateway:** Ocelot
*   **External Integrations:**
    *   Copernicus EDO (Drought Data)
    *   OpenWeatherMap API (Weather Forecasts)
    *   Kindwise Crop.Health API (AI-powered Plant Disease Identification)

Thank you for your interest in my Bachelor's Thesis project!
