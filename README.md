
# Voting System

A user-friendly and secure voting system built with Spring Boot. Ideal for small to medium elections, ensuring transparent and reliable voting.

## Features

- **Voter**: Register, log in, cast votes, and manage profiles.
- **Admin**: Manage elections, oversee results, and handle users.
- **Profile**: Securely manage personalized user profiles.
- **User**: Account management and activity tracking.

## Tech Stack

- Spring Boot
- Spring Security
- Hibernate/JPA
- Thymeleaf
- MySQL

## Setup

### Requirements

- JDK 11+
- Maven
- MySQL

### Installation

1. **Clone the repo:**
  
    git clone https://github.com/Umeshpatil1932/voting-system.git
  

2. **Go to project directory:**
  
    cd voting-system
 

3. **Configure your database:**
    - Edit `application.properties` with your MySQL settings.

4. **Build the project:**
    
    mvn clean install
   

5. **Run the app:**
  
    mvn spring-boot:run


### How to Use

1. Open `http://localhost:8080`.
2. Register as a voter and log in.
3. Cast your vote.
4. Admins can log in to manage the election process.
