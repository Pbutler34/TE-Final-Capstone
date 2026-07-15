# Video Game Database

A full-stack web application for searching and cataloguing family-oriented video games, built as a capstone project during the Tech Elevator software development bootcamp.

## Overview

This project lets users browse and search a curated database of video games suited for family play, with data enriched via the official Twitch API. It was built collaboratively by a small team, covering the full stack from database design through a Vue.js front end.

## Tech Stack

- **Backend:** Java 11, Spring Boot 2.3
  - Spring Data JDBC
  - Spring Security with JWT authentication (jjwt)
  - Bean Validation
- **Database:** PostgreSQL
- **Frontend:** Vue.js, JavaScript, HTML, CSS
- **External API:** Twitch API (game data integration)
- **Build Tool:** Maven

## Features

- Search and filter a catalog of video games
- Family-friendly filtering to help users find age-appropriate titles
- Data sourced and kept current via integration with the Twitch API
- RESTful backend built with Spring Boot, backed by a PostgreSQL database

## Project Structure

```
TE-Final-Capstone/
├── java/   # Spring Boot backend
└── vue/    # Vue.js frontend
```

### Prerequisites

- Java 11 (JDK)
- Maven (or use the included Maven wrapper, if present: `mvnw`)
- Node.js and npm
- PostgreSQL

### Setup

```bash
git clone https://github.com/Pbutler34/TE-Final-Capstone.git
cd TE-Final-Capstone
```

**Backend (`/java`):**
```bash
cd java
# Configure your PostgreSQL connection details in application.properties
mvn spring-boot:run
```

**Frontend (`/vue`):**
```bash
cd vue
npm install
npm run serve
```

## Team

Built collaboratively as part of the Tech Elevator full-stack development bootcamp.

## License

This project was built for educational purposes as part of a coding bootcamp capstone.
License
