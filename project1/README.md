# DevOps Project 1 

## Overview
This project demonstrates how to deploy a static website using Docker and Nginx.

## Tools Used
- Git
- Docker
- Nginx

## How to Run

### Step 1: Clone repo
git clone <your-repo-link>

### Step 2: Build image
docker build -t mywebsite:v1 .

### Step 3: Run container
docker run -d -p 8080:80 mywebsite:v1

### Step 4: Open browser
http://localhost:8080

## Project Structure
- index.html
- about.html
- contact.html
- Dockerfile

## Learning Outcome
- Docker image creation
- Container deployment
- Git version control
