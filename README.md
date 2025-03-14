This project is a high-performance, AI-powered fintech platform designed to facilitate real-time transactions, automated financial analysis, secure account management, and AI-driven fraud detection. Built with a scalable microservices architecture, the system leverages event-driven communication using Apache Kafka and RabbitMQ, ensuring reliable, asynchronous transaction processing. The platform consists of multiple services, including User Service, Transaction Service, Notification Service, and Fraud Detection Service, all containerized with Docker and orchestrated using Kubernetes for high availability. Users can securely transfer funds, monitor transaction history, receive real-time alerts, and manage multiple accounts, all while ensuring fast, encrypted, and compliant financial operations. The backend is built using NestJS (Node.js) with PostgreSQL, while the frontend is developed using React.js with TailwindCSS, offering an intuitive and mobile-friendly user experience. The platform supports RBAC-based authentication using JWT and OAuth 2.0, ensuring secure access control for different user roles, such as Customers, Admins, and Financial Advisors. The AI-powered fraud detection system leverages TensorFlow and OpenAI models to analyze transaction patterns and prevent fraudulent activities in real time. Additionally, the system integrates with external financial APIs (such as Plaid or OpenBanking API) to aggregate and analyze financial data. The entire platform undergoes rigorous unit, integration, and E2E testing using Jest, Cypress, and Supertest, achieving 85%+ code coverage. The CI/CD pipeline is automated using GitHub Actions and Docker, ensuring seamless deployments to AWS/GCP/Azure with Kubernetes, Blue-Green Deployments, and Auto-scaling. Real-time monitoring is implemented using Prometheus, Grafana, and Sentry, enabling continuous tracking of performance, logs, and error rates. This project is built for scalability, security, and compliance with financial regulations, making it a reliable choice for handling high-volume financial transactions efficiently. 

Frontend---
React.js (Next.js), 
TailwindCSS, 
Chart.js/D3.js

Backend----
Node.js (NestJS), 
Apache Kafka, 
PostgreSQL, 
Redis, 
WebSockets

AI & Fraud Detection----
TensorFlow.js, 
ML

Setup & Installation

Prerequisites-----
Docker & Docker Compose, 
Node.js & npm/yarn, 
PostgreSQL & Redis

git clone https://github.com/Satavisha-datta/xnl-21BCE5012-FS-1.git
cd fintech-platform

2. Install Dependencies

cd backend && npm install  
cd frontend && npm install  

3. Start Services

Using Docker: docker-compose up -d
