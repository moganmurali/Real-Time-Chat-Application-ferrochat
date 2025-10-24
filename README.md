# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.


# 💬 FerroChat – Serverless Real-Time Chat Application in Cloud Computing

FerroChat is a **fully serverless, real-time chat application** built using **Amazon Web Services (AWS)**.  
It enables seamless, secure, and scalable real-time communication between users — without managing any servers.  
This project demonstrates the power of **serverless architecture** for modern cloud-based communication systems.

---

## 🚀 Project Overview

FerroChat allows users to send and receive messages instantly, authenticate securely, and share media — all powered by AWS services.  
The system leverages **Lambda, API Gateway (WebSockets), DynamoDB, Cognito, S3, and SNS** to create a scalable and reliable chat experience.

---

## 🧠 Objectives

- Build a **real-time chat system** using AWS cloud services.  
- Demonstrate a **serverless event-driven architecture**.  
- Ensure **secure authentication**, **scalable backend**, and **cost efficiency**.  
- Use **AWS-managed services** to eliminate infrastructure management.

---

## 🏗️ Architecture

```text
Client (Web / Mobile)
       ↓
Amazon Cognito → Authentication
       ↓
API Gateway (WebSocket API)
       ↓
AWS Lambda Functions
       ↓
Amazon DynamoDB (Chat Data)
       ↓
Amazon S3 (Media Files)
       ↓
Amazon SNS (Push Notifications)

FOLDER STRUCTURE
ferrochat/
│
├── backend/
│   ├── lambda_functions/
│   │   ├── connect_handler.py
│   │   ├── message_handler.py
│   │   └── disconnect_handler.py
│   ├── dynamodb_schema/
│   ├── serverless.yml
│   └── requirements.txt
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── architecture-diagram.png
└── README.md

Author

👤 Mr. Mogan Murali
AWS Cloud & Devops
moganmurali14@gmail.com

