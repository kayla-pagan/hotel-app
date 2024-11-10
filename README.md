# Landon Hotel Scheduling App
## Project Overview
This project is a multithreaded, containerized scheduling application for the Landon Hotel, developed with a Java Spring Boot backend and an Angular frontend. The application supports localization, currency display, and time zone conversions, enhancing user accessibility across regions.

## Project Scope
The backend and frontend structures were pre-built for this application. My role focused on enhancing functionality by implementing multithreading, localization, currency display, and time zone conversions, as well as containerizing the application using Docker for streamlined deployment.

*Note*: This repository does not contain the actual project code, as the code is proprietary and maintained privately. This README serves to document the project features, functionality, and my contributions for reference.

## Key Features
### Localization and Internationalization:
* Implemented resource bundles to support both English and French languages, ensuring compliance with Canadian language requirements.
* Displayed welcome messages in both languages, utilizing multithreading to manage simultaneous language outputs.

### Currency and Time Zone Display:
* Enhanced front-end display to show reservation prices in USD, CAD, and EUR without conversion.
* Developed a Java method for converting time zones between Eastern Time (ET), Mountain Time (MT), and Coordinated Universal Time (UTC), and displayed the time in all three zones for scheduled events.

## Docker and Deployment
### Docker Containerization:
* Built a Dockerfile to containerize the application, integrating both the backend and frontend code into a single image.
* Tested the Dockerfile by creating and running a Docker container for the multithreaded application, confirming functionality and stability within the containerized environment.

### Deployment Planning: 
* Outlined deployment strategy for cloud services, specifying the use of a major cloud provider (AWS, Google Cloud, etc.) to host the Dockerized application, enabling scalable and efficient access for end-users.

