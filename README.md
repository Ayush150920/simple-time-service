# SimpleTimeService

A simple Python microservice that returns the current timestamp and the client IP address in JSON format.

## 🔧 How to Build & Run with Docker

### 1. Clone the repository
git clone https://github.com/<your-username>/simple-time-service.git
cd simple-time-service

### 2. Build the Docker image
docker build -t simple-time-service

### 3. Run the Docker container
docker run -p 8080:8080 simple-time-service

### 4.Access the service
Visit http://localhost:8080

### 5.
aws_region       = "us-east-1"
vpc_cidr         = "10.0.0.0/16"
container_image  = "4303644d1db83731962701a3520c047d994b4f1d46be2488b066c2b825127989/simple-time-service"
