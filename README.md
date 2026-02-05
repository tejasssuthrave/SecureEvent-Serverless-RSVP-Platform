# SecureEvent – Serverless RSVP Platform

SecureEvent is a secure, cloud-native serverless RSVP application built on AWS.
It demonstrates real-world Linux, Cloud, Database, and Security practices using AWS managed services and RESTful APIs.

---

## 🚀 Project Overview

SecureEvent allows users to:
- View available events
- Submit RSVPs securely
- Store and retrieve event and attendee data from a managed database

The project follows a **serverless architecture** with a **managed relational database (Amazon RDS)**, making it suitable for real-world cloud deployments.

---

## 🧱 Architecture

- **Frontend:** Static website hosted on Amazon S3 and delivered via CloudFront  
- **Backend:** AWS Lambda (Node.js)  
- **API Layer:** Amazon API Gateway  
- **Database:** Amazon RDS (MySQL)  
- **Monitoring:** Amazon CloudWatch  
- **OS & Tooling:** Linux, AWS CLI, Sqlectron  

---

## 🗄️ Database Design (Amazon RDS)

- MySQL database hosted on **Amazon RDS**
- Tables designed with primary and foreign keys
- Managed and queried using **Sqlectron**
- Secure access controlled via **VPC Security Groups**

### Tables
- `events` – stores event details  
- `rsvps` – stores attendee RSVP information  

---

## 🔐 Security Implementation

- IAM roles with **least-privilege access** for Lambda
- Secure database access using **VPC security groups**
- API protection using **API Gateway API keys**
- Sensitive configuration managed via **Lambda environment variables**
- Server-side **input validation**
- Restricted **CORS policies**
- CloudWatch logging and monitoring

---

## 🛠️ Tech Stack

- **Cloud:** AWS Lambda, API Gateway, S3, CloudFront, RDS, IAM, CloudWatch  
- **Backend:** Node.js  
- **Frontend:** HTML, CSS, JavaScript  
- **Database:** MySQL (Amazon RDS)  
- **OS:** Linux  
- **DB Client:** Sqlectron  

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
├── database/
│   └── schema.sql
├── package.json
└── README.md
