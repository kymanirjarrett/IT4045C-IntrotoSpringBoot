# IT4045C - Intro to Spring Boot

**Name:** Kymani Jarrett  
**Student ID:** M15733207  
**Course:** IT4045C-002 | Enterprise Application Development

## Description

A basic Spring Boot application with a controller that serves two static pages. The homepage
displays a greeting and the about page displays my information.

## How to Run

1. Clone the repository:

- git clone https://github.com/kymanirjarrett/IT4045C-IntrotoSpringBoot.git

- cd IT4045C-IntrotoSpringBoot

2. Run the application:

- ./mvnw spring-boot:run

3. Open a browser to:
    - http://localhost:8080/ (homepage)
    - http://localhost:8080/about (about page)

## Routes

| URL | Serves |
|---|---|
| `/` | `index.html` |
| `/about` | `about.html` |