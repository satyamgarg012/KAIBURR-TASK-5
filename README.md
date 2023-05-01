# KAIBURR-TASK-5

This is a README file for the CI/CD pipeline of a Java REST API using Jenkins, Maven, Git, Docker, and Tomcat.

Project Description
This project is a Java REST API that is deployed using a CI/CD pipeline. The pipeline includes building the code using Maven, committing the changes to Git, creating a Docker image of the application, and deploying it to a Tomcat server.

Prerequisites

Java 8 or higher
- Maven
- Git
- Docker
- Tomcat
- Jenkins

Setup

- Clone the project repository to your local machine.
- Open the Jenkins dashboard and create a new pipeline job.
- Configure the pipeline job to use the project repository as the source code.
- Set up the build process by adding the following build steps:
   Run Maven to build the application.
   Commit the changes to Git.
   Create a Docker image of the application.
   Push the Docker image to a Docker registry.
- Set up the deployment process by adding the following deploy steps:
   Pull the Docker image from the Docker registry.
   Deploy the Docker container to a Tomcat server.
   
Usage

Once the pipeline is set up, any changes to the source code will automatically trigger a new build and deployment. You can monitor the progress of the pipeline and view the logs on the Jenkins dashboard.

Contributing
If you would like to contribute to this project, please create a pull request with your changes. Before submitting a pull request, please make sure that all tests pass and that your changes do not break the existing functionality.
