# Automated Lead Management & Email Tracking System

## Overview

The **Automated Lead Management & Email Tracking System** is a modern CRM application designed to help businesses efficiently manage customer leads, automate email communication, and monitor engagement. It provides an intuitive dashboard for tracking leads, organizing follow-ups, and analyzing email performance.

This project demonstrates full-stack web development concepts including lead management, email automation, analytics, and responsive UI design.

---

# Features

## Authentication

* User Login
* User Registration
* Secure Authentication
* Password Encryption

## Lead Management

* Add New Lead
* Edit Lead Information
* Delete Lead
* Search Leads
* Filter by Status
* Lead Details View

## Email Management

* Send Emails
* Email History
* Email Templates
* Scheduled Follow-ups

## Email Tracking

* Email Sent Status
* Email Open Tracking
* Click Tracking
* Reply Tracking
* Delivery Status

## Dashboard

* Total Leads
* Emails Sent
* Conversion Rate
* Open Rate
* Monthly Analytics
* Recent Activities

## Analytics

* Lead Growth
* Email Performance
* Conversion Funnel
* Follow-up Statistics

## Responsive Design

* Desktop Support
* Tablet Support
* Mobile Support

---

# Technology Stack

### Frontend

* React.js
* Tailwind CSS
* JavaScript (ES6+)
* HTML5
* CSS3

### Backend

* Node.js
* Express.js

### Database

* MongoDB

### Authentication

* JWT
* bcrypt

### Email Service

* Nodemailer

### Charts

* Chart.js

---

# Project Structure

```text
lead-management-system/
│
├── client/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   ├── assets/
│   │   ├── App.jsx
│   │   └── main.jsx
│   └── package.json
│
├── server/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── config/
│   ├── server.js
│   └── package.json
│
└── README.md
```

---

# Installation

## Clone the Repository

```bash
git clone https://github.com/yourusername/lead-management-system.git
cd lead-management-system
```

## Install Frontend

```bash
cd client
npm install
```

## Install Backend

```bash
cd ../server
npm install
```

---

# Environment Variables

Create a `.env` file inside the **server** directory.

```env
PORT=5000

MONGODB_URI=your_mongodb_connection_string

JWT_SECRET=your_secret_key

EMAIL_USER=your_email@example.com

EMAIL_PASS=your_email_password
```

---

# Run the Application

### Start Backend

```bash
cd server
npm run dev
```

### Start Frontend

```bash
cd client
npm run dev
```

The application will be available at:

Frontend:

```
http://localhost:5173
```

Backend:

```
http://localhost:5000
```

---

# API Endpoints

## Authentication

```
POST /api/auth/register
POST /api/auth/login
GET  /api/auth/profile
```

## Leads

```
GET    /api/leads
POST   /api/leads
PUT    /api/leads/:id
DELETE /api/leads/:id
```

## Emails

```
POST /api/email/send
GET  /api/email/history
```

## Analytics

```
GET /api/analytics
```

---

# Future Improvements

* AI Lead Scoring
* Email Personalization
* CRM Integrations
* WhatsApp Notifications
* SMS Integration
* Calendar Integration
* Role-Based Access Control
* Multi-Tenant Support
* Real-Time Notifications
* Export to Excel and PDF

---

# License

This project is licensed under the MIT License.

---

# Author

**Yash Srivastava**

Email: [your-email@example.com](mailto:your-email@example.com)

GitHub: https://github.com/yourusername

LinkedIn: https://linkedin.com/in/your-profile
