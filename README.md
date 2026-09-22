# ⚡ Smart Energy Meter

A comprehensive smart energy monitoring backend built with **Node.js, Express.js, MongoDB Atlas, ESP32, and AI/ML integration**.

The system collects real-time electricity data from IoT devices, stores and analyzes energy consumption, detects abnormal usage, generates alerts, and provides AI-powered predictions and chatbot assistance.

---

## 🚀 Features

- 👤 **User Management** — Registration, login, authentication, and profile management
- 🔌 **Device Management** — Add, update, delete, and monitor IoT devices
- ⚡ **Energy Monitoring** — Collect real-time current, voltage, temperature, and power data
- 📊 **Energy Analytics** — Store and retrieve device-wise energy consumption data
- 🤖 **AI/ML Integration** — Predict future energy usage through a Python API
- 🚨 **Smart Alerts** — Detect power spikes and abnormal energy usage
- 💬 **AI Chatbot** — Ask natural-language questions about energy consumption
- 🔐 **JWT Authentication** — Secure user authentication
- 🛡️ **Security** — Helmet, CORS, bcrypt password hashing, and input validation

---

## 🏗️ Architecture

```text
smart-energy-meter/
│
├── config/                 # Database configuration
├── controllers/            # Business logic
├── middleware/             # Authentication & error handling
├── models/                 # Mongoose database schemas
├── routes/                 # Express API routes
├── utils/                  # Notification & email services
│
├── ai_predictor.py         # AI/ML prediction service
├── server.js               # Main Express server
├── package.json            # Project dependencies
└── README.md               # Documentation
