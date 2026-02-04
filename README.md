# SecureEvent-Serverless-RSVP-Platform

SecureEvent is a secure, serverless RSVP platform built on AWS using Lambda, API Gateway, S3, and CloudFront. It demonstrates Linux-based cloud deployment, IAM least-privilege security, protected REST APIs, environment variable management, and CloudWatch monitoring in a real-world serverless architecture.
---

## 🚀 Project Overview

SecureEvent allows users to:
- View available events
- Submit RSVPs securely
- Fetch attendee statistics via REST APIs

The project follows a **serverless architecture**, ensuring scalability, reduced operational overhead, and secure cloud communication.

---

## 🧱 Architecture

- **Frontend:** Static website hosted on Amazon S3 and delivered via CloudFront  
- **Backend:** AWS Lambda (Node.js)  
- **API Layer:** Amazon API Gateway  
- **Database:** DynamoDB / MySQL  
- **Monitoring:** Amazon CloudWatch  

---

## 🔐 Security Implementation

- IAM roles with **least-privilege access**
- Secure API access using **API Gateway API keys**
- Sensitive data managed using **Lambda environment variables**
- Server-side **input validation**
- Restricted **CORS policies**
- CloudWatch logging and error monitoring

---

## 🛠️ Tech Stack

- **Cloud:** AWS Lambda, API Gateway, S3, CloudFront, IAM, CloudWatch  
- **Backend:** Node.js  
- **Frontend:** HTML, CSS, JavaScript  
- **Database:** DynamoDB / MySQL  
- **OS:** Linux  

---

## 📂 Project Structure

```text
.
├── frontend/
│   ├── index.html
│   ├── style.css
│   └── app.js
├── backend/
│   └── index.js
├── utils/
├── package.json
└── README.md
