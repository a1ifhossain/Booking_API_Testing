# 🧪 Booking API Testing Project

A comprehensive API testing suite for a hotel booking system, developed using **Postman** and executed via **Newman**. This project automates validation of RESTful endpoints and generates detailed HTML reports for efficient debugging and quality assurance.

---

## 📦 Project Overview

This project tests the key functionalities of the **Booking API**, including:

* ✅ Creating new bookings
* 📥 Retrieving booking data
* ✏️ Updating existing bookings
* ❌ Deleting bookings
* 🔐 Generating authentication tokens

The goal is to ensure **reliability**, **correctness**, and **performance** of the booking service via automated test execution.

---

## 📁 Folder Structure

```
booking-api-tests/
├── Booking_Collection.postman_collection.json      # Postman collection
├── Booking_Environment.postman_environment.json    # Environment variables
├── newman-report.html                              # Newman HTML test report
└── README.md                                        # Project documentation
```

---

## ⚙️ Getting Started

### ✅ Prerequisites

* [Postman](https://www.postman.com/downloads/)
* [Node.js](https://nodejs.org/)
* [Newman](https://www.npmjs.com/package/newman)

### 🧪 Run Tests with Newman

1. Install Newman globally (if not already installed):

```bash
npm install -g newman
```

2. Run the Postman collection:

```bash
newman run Booking_Collection.postman_collection.json -e Booking_Environment.postman_environment.json -r html --reporter-html-export newman-report.html
```

3. Open `newman-report.html` in your browser to view the test results.

---

## 📊 Test Report Overview

The generated `newman-report.html` includes:

* 🔁 **Total iterations and requests**
* ✅ **Assertions passed** / ❌ **Assertions failed**
* ⏱️ **Test script performance insights**
* 📨 **Request & response bodies**
* 🧾 **Headers and timing breakdowns**

---

## 🛠️ Tools & Technologies

| Tool      | Description                        |
| --------- | ---------------------------------- |
| Postman   | API development and manual testing |
| Newman    | CLI runner for Postman collections |
| HTML      | Interactive test report generation |
| REST APIs | Booking API hosted on Heroku       |

---

## 👤 Author

**Md Alif Hossain Parvez**
🧪 SQA Engineer
📧 Email: [alifhossain5321@gmail.com](mailto:alifhossain5321@gmail.com)
🔗 LinkedIn: [linkedin.com/in/md-alif-hossain-parvez-03727b340](https://linkedin.com/in/md-alif-hossain-parvez-03727b340)

