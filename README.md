# Nasdaq-100 ETF Explorer Web App Deployment-_and-_Orchestration

## Overview

This repository is dedicated to the deployment and orchestration of Nasdaq-100 ETFs Explorer Wrb application, facilitating a seamless interaction between the frontend and backend components of our application through Docker Compose. It is designed to streamline the setup and management of our application's infrastructure, allowing for easy deployment across different environments.

## Architecture

The application utilizes a client-server architecture, ensuring a distinct separation between the backend (Django REST Framework) and the frontend (ReactJS). Below are the repositories for the backend and frontend components:

Backend: https://github.com/Bouille-L/Nasdaq-100_back_end.git
Frontend: https://github.com/Bouille-L/Nasdaq-100_front_end.git


## Prerequisites

Before proceeding, ensure you have the following installed:
- Docker
- Docker Compose
- Git (for cloning the necessary repositories)

## Repository Structure

Explain that the Dockerfiles are located in their respective frontend and backend repositories, and that this repository contains the `docker-compose.yml` for orchestrating those services together.

## Getting Started

### Cloning the Repositories

1. Clone the frontend repository:
   ```
   git clone [https://github.com/Bouille-L/Nasdaq-100_front_end.git]
   ```
2. Clone the backend repository:
   ```
   git clone [https://github.com/Bouille-L/Nasdaq-100_back_end.git]
   ```
3. Clone this deployment and orchestration repository:
   ```
   git clone [https://github.com/Bouille-L/Deployment-_and-_Orchestration.git]
   ```

### Configuring Frontend-Backend Communication(in case local developement)

Frontend URL Configuration: Set your backend URL in the frontend component(ChartTQQQ, ChartQQQ, ChartSQQQ and Contactus, News)

CORS Configuration: Ensure the backend is configured to accept requests from your frontend's local address(by adding the frontend's local URL to CORS_ALLOWED_ORIGINS in settings.py)



### Running the Application

Navigate to the directory containing `docker-compose.yml` and start the services:

```
cd [https://github.com/Bouille-L/Deployment-_and-_Orchestration.git]
docker-compose up -d
```

## For further questions or contributions, feel free to contact me via Github Channel.


---

This `README.md` template is tailored to your specific setup, focusing on the importance of the `docker-compose.yml` in orchestrating your application's containers. Adjust the content to fit your project's details and requirements, ensuring it provides a comprehensive guide for your team and any external contributors.
