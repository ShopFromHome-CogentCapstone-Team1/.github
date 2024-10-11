# ShopForHome

ShopForHome is an online shopping platform specializing in home décors. This project aims to provide a seamless eCommerce experience for users and administrators, ensuring business continuity for sellers through a robust online presence.

## 🛠 Technologies Used

- **Backend:**
  - Java
  - Spring Boot
  - Kafka
  - MySQL
  - Docker

- **Frontend:**
  - Angular
  - TypeScript
  - Material UI
  - Docker

- **Other Tools:**
  - GitHub for version control
  - Docker Compose for service orchestration

## 🎯 Sprint I Objectives

1. **Create Git Repository**
   - Initialize the Git repository and set up the branching strategy.

2. **Create Database Schema**
   - Design all tables with their relationships.
   - **Location:** `database/schema.sql`

3. **Create Entities in Spring**
   - Develop JPA entities corresponding to the database schema.
   - **Location:** `backend/src/main/java/com/shopforhome/model/`

4. **CRUD Operations on User and Products**
   - Implement Create, Read, Update, Delete functionalities for User and Product entities.
   - **Location:** `backend/src/main/java/com/shopforhome/controller/`

5. **Create an eCommerce Template in Angular (Static)**
   - Develop a static Angular template to display images and product lists.
   - **Location:** `frontend/angular-app/src/app/components/`

6. **Develop Search Functionality in Angular**
   - Implement search features to filter products.
   - **Location:** `frontend/angular-app/src/app/components/`

7. **Bulk Upload Implementation**
   - Enable bulk uploading of products or images.
   - **Location:** `frontend/angular-app/src/app/services/`

## 📁 Repository Structure

### Backend (`backend/`)

- **reports-service/**: Microservice dedicated to generating reports.
- **discount-service/**: Microservice for managing discount coupons.
- **src/main/java/com/shopforhome/**:
  - **controller/**: REST controllers handling HTTP requests.
  - **service/**: Business logic services.
  - **repository/**: Data access layers.
  - **model/**: JPA entities representing database tables.
  - **ShopForHomeApplication.java**: Main application class.
- **src/main/resources/**:
  - **application.properties**: Configuration properties.
  - **schema.sql**: Database schema.
- **Dockerfile**: Docker configuration for backend services.
- **pom.xml**: Maven dependencies and build configurations.

### Frontend (`frontend/`)

- **angular-app/**:
  - **src/app/components/**: Angular components for UI.
  - **src/app/services/**: Services for API interactions.
  - **src/app/models/**: TypeScript interfaces/models.
  - **src/assets/images/**: Folder for uploading images.
  - **src/styles/**: Global styles.
  - **app.module.ts**: Root module.
- **Dockerfile**: Docker configuration for frontend.
- **package.json**: Node.js dependencies and scripts.

### Database (`database/`)

- **schema.sql**: SQL file containing the database structure.

### Root

- **docker-compose.yml**: Orchestrates backend, frontend, and database services.
- **README.md**: Project documentation.
- **.gitignore**: Specifies intentionally untracked files.

## 🛠 Setup Instructions

### Prerequisites

- Docker & Docker Compose installed
- Git installed

### Steps

1. **Clone the Repository**

   ```bash
   git clone https://github.com/ShopFromHome-CogentCapstone-Team1/ShopForHome.git
   cd ShopForHome
