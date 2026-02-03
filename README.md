# Docker Flask Redis Application

This project is a simple Flask web application that uses Redis to count the number of visits.  
The application is fully containerized using Docker.

---

## Technologies Used
- Python (Flask)
- Redis
- Docker
- Docker Compose

---

## How to Run the Application

### 1. Clone the repository
```bash
git clone https://github.com/VAISHNAVREDDYDANDU/docker-flask-redis.git
cd docker-flask-redis
### 2. Build and run containers
```bash
docker compose up --build
### 3. Open the application
Open your browser and go to:
http://localhost:5000
Each refresh increases the visit count stored in Redis.
## Expected Output
Hello! This page has been visited X times.
---

## Screenshots

### Docker Containers Running
![Docker Containers](screenshots/docker-containers.png
)

### Application Output (Browser)
![Application Output](screenshots/browser-output.png
)

### Terminal Output
![Terminal Output](screenshots/terminal-output.png
)
