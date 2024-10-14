
prismMockForOpenapiWithnginxReverseProxy

This project sets up a mocking service with an Nginx reverse proxy to access the service at localhost:8080/api.

Prerequisites
To run Prism and the Nginx container, you need to have Docker installed on your local system.

You can download and install Docker from the following links:

For Windows: https://docs.docker.com/desktop/install/windows-install/
For macOS: https://docs.docker.com/desktop/install/mac-install/
For Ubuntu Linux: https://docs.docker.com/engine/install/ubuntu/


Instructions
After installing Docker, open the terminal (Linux or macOS) or PowerShell (Windows).

Navigate to the cloned directory of this repository.

Run the following command:

Copy code
docker-compose up -d

That's it! Your mocking service for the API definition is now running.


