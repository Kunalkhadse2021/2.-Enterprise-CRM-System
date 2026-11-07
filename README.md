# 2.-Enterprise-CRM-System
A web-based CRM system to manage customers, sales leads, track pipelines, and monitor business performance.
# Enterprise CRM System

## Project Overview
Enterprise CRM System is a web-based application designed to manage customers, sales leads, sales pipelines, and business activities efficiently.

## Features
- User Registration and Login
- Secure JWT Authentication
- Customer and Lead Management
- Sales Pipeline Tracking
- Dashboard with Business Analytics
- Admin and Sales User Roles
- Search and Filter Leads
- Recent Activity Tracking
- Responsive User Interface

## Technologies Used
- React.js
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- HTML, CSS, JavaScript

## Project Structure
```text
enterprise-crm-system/
├── client/
│   ├── src/
│   │   ├── components/
│   │   ├── context/
│   │   └── pages/
│   └── package.json
├── server/
│   ├── src/
│   │   ├── config/
│   │   ├── controllers/
│   │   ├── middleware/
│   │   ├── models/
│   │   └── routes/
│   └── package.json
├── package.json
├── README.md
└── .gitignore
```

## Installation and Setup

### 1. Clone Repository
```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Open Project Folder
```bash
cd enterprise-crm-system
```

### 3. Install Dependencies
```bash
npm install
```

### 4. Configure Environment
Copy `server/.env.example` to `server/.env` and configure:

```env
PORT=5000
MONGODB_URI=mongodb://127.0.0.1:27017/enterprise_crm
JWT_SECRET=your_long_random_secret
CLIENT_URL=http://localhost:5173
```

### 5. Start the Application
```bash
npm run dev
```

### 6. Open in Browser
Frontend: http://localhost:5173

Backend: http://localhost:5000

## Project Purpose
The main purpose of this project is to simplify customer relationship management, improve sales tracking, and help businesses monitor their performance.

## Future Enhancements
- Email Notifications
- Advanced Sales Reports
- Customer Communication Tools
- Payment Integration
- Export Reports

## Author
Kunal Khadse

## License
Developed for educational and internship purposes.
