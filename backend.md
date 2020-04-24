# Backend
## Architecture

Webclient <-> Webserver <-> Application Services <-> Backend Services <-> Database

The Webbrowser loads static content containing the frontend code from Nginx running on the webserver. 
The frontend code uses a RESTful API to interact with Teacher application or the user application which are running on the application server. These two server applications use RESTful API to communicate with the business backend application. Only the business backend code connects to the database.

## Tech Stack
- Github
- Docker
- Nginx
- Java
- Spring Boot
- RESTful API + Swagger
- Gradle
- JPA / Hibernate
- (some tool for DB design change tracking - maybe liquibase or flyway)
- PostgreSQL

## Development Workflow
Github Flow + Jenkins build pipline (build + test + deploy)
Task tracking using a kanban board: https://github.com/orgs/klassecloud/projects/1

Documentation in markdown files as part of the git repositories.

## Testing
The goal ist to implement basic tests using JUnit 5 for automatic pull request testing and quality control. (Don't spend too much time of the hackathon on writing tests, still try to get the `low hanging fruits` / easy tests)

## Server Infrastructure
To simplify development of a quality product, the following infrastructure was set up and configured:
- Application Server to host the most recent version of klasse.cloud
- Database Server using PostgreSQL
- Monitoring Server using GrayLog, Grafana and influxDB
- Build Server using Jenkins, SonarQube and Artifactory

## Others
ensure that scalability is posible
Monitoring-Server
Build-Server
