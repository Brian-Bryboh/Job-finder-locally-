
# Local Job Finder

A simple Java Spring Boot application to help connect job seekers with local employers, designed especially for low-income communities.

## Features
- User registration and login (Employer & Job Seeker)
- Employers can post job openings
- Job seekers can browse and apply for jobs
- Job filtering by location and category
- Simple frontend using Thymeleaf

## Technologies Used
- Java
- Spring Boot
- Thymeleaf
- MySQL
- Maven

## Setup Instructions

1. Clone the repository or unzip the downloaded file.

2. Configure the database:
   - Create a MySQL database named `jobfinder`
   - Update `src/main/resources/application.properties` with your MySQL credentials

3. Build the project using Maven:

mvn clean install

4. Run the application:

mvn spring-boot:run

5. **Access the app in your browser:**

http://localhost:8080

## Directory Structure

src/ ├── main/ │   ├── java/com/jobfinder/ │   │   ├── controller/ │   │   ├── model/ │   │   ├── repository/ │   ├── resources/ │   │   ├── templates/ │   │   └── application.properties

## Future Improvements
- Add user authentication and authorization (Spring Security)
- Add pagination and filtering on job listings
- Implement job application tracking
- Add admin panel for moderation


