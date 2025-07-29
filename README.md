# Pet Adoption Project

This is a full-stack web project for a pet adoption platform.
- **Frontend**: [React.js](https://github.com/sarah20030409/pet-adoption-frontend)
- **Backend**:  [Python Flask](https://github.com/sarah20030409/pet-adoption-backend)
- **Database**: MySQL

## 🐳 Run the whole project using Docker

This backend project includes:
- Flask API (Python)
- A MySQL database with preloaded schema/data

### ✅ One Command to Start Everything
```bash
git clone https://github.com/sarah20030409/pet-adoption-docker.git
cd pet-adoption-docker
docker-compose up --build
```
⚠️ Note: If port 3306 is already in use (e.g., from a local MySQL installation), please modify the port mapping in `docker-compose.yml` to something like `3307:3306`, and update the corresponding environment variables.

