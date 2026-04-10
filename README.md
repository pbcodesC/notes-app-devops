# Notes App

This is a simple Notes Application built using Django and enhanced with DevOps tools like Docker and Jenkins.

## Tech Stack
- Backend: Django (Python)
- Frontend: HTML, CSS, JavaScript
- DevOps: Docker, Jenkins
- Version Control: Git & GitHub

## Features
- Create notes
- Update notes
- Delete notes

  ## DevOps Workflow
Code → Docker → Jenkins → Deployment

## Requirements
1. Python 3.9
2. Node.js
3. React

## Installation
1. Clone the repository
```
git clone https://github.com/pbcodesc/notes-app-devops.git
```

2. Build the app
```
docker build -t notes-app .
```

3. Run the app
```
docker run -d -p 8000:8000 notes-app:latest
```

## Nginx

Install Nginx reverse proxy to make this application available

`sudo apt-get update`
`sudo apt install nginx`
