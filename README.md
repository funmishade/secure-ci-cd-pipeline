# Secure CI/CD Pipeline

A beginner-friendly DevOps project demonstrating a secure CI/CD pipeline using a Flask web application as the example app. This project includes Dockerization, Git version control, and will later integrate CI/CD tools.

---

## Features

- Flask web application skeleton
- Local run testing with Python
- Docker-ready for containerization
- Ready for CI/CD integration (GitHub Actions / Jenkins)
- Designed to demonstrate DevOps best practices for beginners

---

## Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/funmishade/secure-ci-cd-pipeline.git
   cd secure-ci-cd-pipeline/app
   
2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt

3. **Run the app locally:**
   ```bash
   python app.py

4. **Run the app locally:**
   ```bash
  http://localhost:5000
   
## Folder Structure

secure-ci-cd-pipeline/
├── app/
│   ├── app.py
│   └── requirements.txt
├── .gitignore
└── README.md

## Next Steps / TODO

Dockerize the Flask app for containerized deployment

Implement CI/CD pipeline using GitHub Actions or Jenkins

Add security scanning (SAST/DAST) for the application
