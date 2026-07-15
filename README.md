Video Game Database

A full-stack web application for searching and cataloguing family-oriented video games, built as a capstone project during the Tech Elevator software development bootcamp.

Overview

This project lets users browse and search a curated database of video games suited for family play, with data enriched via the official Twitch API. It was built collaboratively by a small team, covering the full stack from database design through a Vue.js front end.

Tech Stack


Backend: Java, Spring Boot
Database: PostgreSQL
Frontend: Vue.js, JavaScript, HTML, CSS
External API: Twitch API (game data integration)


Features


Search and filter a catalog of video games
Family-friendly filtering to help users find age-appropriate titles
Data sourced and kept current via integration with the Twitch API
RESTful backend built with Spring Boot, backed by a PostgreSQL database


Project Structure

TE-Final-Capstone/
├── java/   # Spring Boot backend
└── vue/    # Vue.js frontend

Prerequisites


Java (JDK 11+ recommended)
Node.js and npm
PostgreSQL


Setup

bashgit clone https://github.com/Pbutler34/TE-Final-Capstone.git
cd TE-Final-Capstone


Backend (/java): Configure your PostgreSQL connection details in the Spring Boot application's config file, then build and run it using your IDE (IntelliJ/Eclipse) or the build tool referenced in the java directory (Maven or Gradle wrapper script).
Frontend (/vue): Run npm install followed by npm run serve from the vue directory to start the development server.



Exact build/run commands depend on the build tool used in this project (Maven vs. Gradle) — check the java directory for a pom.xml or build.gradle file to confirm.



Team

Built collaboratively as part of the Tech Elevator full-stack development bootcamp.

License

This project was built for educational purposes as part of a coding bootcamp capstone.
License

This project was built for educational purposes as part of a coding bootcamp capstone.
