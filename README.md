# 🧪 Booking API Testing Project

A comprehensive API testing suite for a hotel booking system, created using **Postman** and executed via **Newman**. This project validates RESTful endpoints and provides detailed test reports in HTML format.

---

## 📦 Project Overview

This project automates testing of key functionalities of the Booking API, including:

- ✅ Creating bookings
- 📥 Retrieving booking data
- ✏️ Updating bookings
- ❌ Deleting bookings
- 🔐 Generating authentication tokens

The goal is to ensure the reliability, correctness, and performance of the booking service through automated test execution.

---

## 📁 Folder Structure

📂 booking-api-tests/
├── Booking_Collection.postman_collection.json # Postman collection
├── Booking_Environment.postman_environment.json # Environment variables
├── newman-report.html # Newman HTML test report
└── README.md # Project documentation

---

## ⚙️ Getting Started

### Prerequisites

- [Postman](https://www.postman.com/)
- [Node.js](https://nodejs.org/)
- [Newman CLI](https://github.com/postmanlabs/newman)

Install Newman globally:
```bash
npm install -g newman
Running Tests
Use the following command to run the test suite and generate an HTML report:

bash
Copy
Edit
newman run Booking_Collection.postman_collection.json \
  -e Booking_Environment.postman_environment.json \
  -r cli,html \
  --reporter-html-export newman-report.html
📊 Test Report
An interactive HTML report is generated after test execution: newman-report.html.

It includes:

Total iterations and requests

Assertions passed/failed

Test script performance

Request/response bodies

Headers and timing breakdowns

🛠️ Tools & Technologies
Tool	Description
Postman	API development and manual testing
Newman	CLI runner for Postman collections
HTML	Visual reporting
RESTful APIs	Booking API hosted on Heroku

👤 Author
Md Alif Hossain Parvez
SQA Engineer
Email: alifhossain5321@gmail.com
LinkedIn: https://www.linkedin.com/in/md-alif-hossain-parvez-03727b340/
