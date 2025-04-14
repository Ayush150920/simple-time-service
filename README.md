# SimpleTimeService

A simple Python microservice that returns the current timestamp and the client IP address in JSON format.

##  How to Build & Run with Docker

### 1. Clone the repository

git clone https://github.com/<your-username>/simple-time-service.git
cd simple-time-service

### 2. Build the Docker image
docker build -t simple-time-service .

### 3. Run the Docker container
docker run -p 8080:8080 simple-time-service

### 4. Access the service
Visit http://localhost:8080
