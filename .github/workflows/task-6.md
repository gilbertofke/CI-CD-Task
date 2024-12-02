# Task 6: CI/CD Pipeline with Cloud Integration

## Objective
Create a CI/CD pipeline that deploys a sample Node.js application to an AWS EC2 instance, leveraging AWS services like S3 for artifact storage.

---

## Prerequisites
- **EC2 Instance**: A Linux-based instance with a static Elastic IP and a web server (e.g., Nginx) already set up.
- **GitHub Repository**: A repository to store the application code and workflow files.
- **AWS CLI Installed**: To interact with AWS services.

---

## Steps to Complete the Task

### Step 1: Project Setup

#### 1.1 Create a Simple Application
1. Initialize a new Node.js project:
   ```bash
   mkdir ci-cd-pipeline
   cd ci-cd-pipeline
   npm init -y
