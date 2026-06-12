# Restful-Booker-API-Testing-using-Postman-Newman
![Postman](https://img.shields.io/badge/Postman-API%20Testing-orange?logo=postman&logoColor=white)
![Newman](https://img.shields.io/badge/Newman-CLI%20Automation-blue)
![JavaScript](https://img.shields.io/badge/JavaScript-Test%20Scripts-yellow?logo=javascript&logoColor=black)

![CI/CD](https://img.shields.io/badge/CI%2FCD-Automated%20Testing-brightgreen?logo=githubactions&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-Newman%20Run-2088FF?logo=githubactions&logoColor=white)

![Status](https://img.shields.io/badge/Status-Completed-success)
![API Testing](https://img.shields.io/badge/API%20Testing-Automation-green)
![Coverage](https://img.shields.io/badge/Test%20Coverage-100%25-brightgreen)
![Assertions](https://img.shields.io/badge/Assertions-44%20Passed-success)


![Postman](https://img.shields.io/badge/Postman-API%20Testing-orange?logo=postman&logoColor=white)
![Newman](https://img.shields.io/badge/Newman-CLI%20Runner-blue)
![JavaScript](https://img.shields.io/badge/JavaScript-Test%20Scripts-yellow?logo=javascript&logoColor=black)
![CI/CD](https://img.shields.io/badge/CI%2FCD-Automated%20Testing-brightgreen?logo=githubactions&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-success)
![Coverage](https://img.shields.io/badge/Test%20Coverage-100%25-brightgreen)


🚀 Overview

This project is a complete API Automation Testing Framework built for the Restful Booker API using Postman and Newman.

It simulates a real-world QA workflow including:

Authentication flow
CRUD operations
API chaining
Dynamic data handling
Automated validation
Professional HTML reporting
⚡ Key Highlights

✔ 17 API Requests Automated
✔ 44 Assertions Executed
✔ 100% Test Pass Rate
✔ ~409ms Average Response Time
✔ Full CRUD Workflow Covered
✔ Zero Failed Tests in Final Execution


Restful-Booker-API-Testing/
│
├── collection/
│   └── Restful Booker API Testing.postman_collection.json
│
├── environment/
│   └── RestfulBooker.postman_environment.json
│
├── reports/
│   ├── Basic_Report.html
│   └── Detailed_Report.html
│
└── README.md

🧪 Features
🔐 Authentication
Token generation using /auth
Dynamic token storage using environment variables
📖 Booking Retrieval
Get all booking IDs
Filter by name
Filter by check-in/check-out dates
✏️ Update Flow
Create booking
Full update (PUT)
Partial update (PATCH)
Verification after update
🗑️ Delete Flow
Create booking
Delete booking
Verify deletion (negative testing)
❤️ Health Check
Ping endpoint validation
🛠️ Tech Stack
Tool	Purpose
🟠 Postman	API Design & Testing
🔵 Newman	CLI Test Execution
🟡 JavaScript	Test Scripts
🌐 REST API	Backend Service
📊 htmlextra	HTML Reporting
🔄 Test Workflow
Auth Token Generation
        ↓
Booking Retrieval
        ↓
Create Booking
        ↓
Update Booking (PUT)
        ↓
Partial Update (PATCH)
        ↓
Delete Booking
        ↓
Verification & Health Check
📡 API Coverage
Method	Endpoint	Description
GET	/booking	Get booking list
GET	/booking/{id}	Get booking details
POST	/booking	Create booking
POST	/auth	Generate token
PUT	/booking/{id}	Full update
PATCH	/booking/{id}	Partial update
DELETE	/booking/{id}	Delete booking
GET	/ping	Health check
🧠 Assertions Used
Status Code Validation
Response Time Validation (< 2s)
Response Body Validation
Data Integrity Checks
Negative Testing (404 validation)
📊 Newman Test Report Summary
Metric	Value
Requests	17
Assertions	44
Failed Tests	0
Success Rate	✅ 100%
Avg Response Time	409ms
Data Received	55 KB
📈 HTML Reports

This project generates professional QA reports using Newman:

📄 Basic Report
Summary of execution
Pass/fail overview
📊 Detailed Report (htmlextra)
Request & response logs
Headers & payload inspection
Assertion breakdown
Performance metrics
▶️ How to Run
1️⃣ Install Newman
npm install -g newman
npm install -g newman-reporter-htmlextra
2️⃣ Run Tests
newman run "Restful Booker API Testing.postman_collection.json" \
-e "RestfulBooker.postman_environment.json"
3️⃣ Generate HTML Report
newman run "Restful Booker API Testing.postman_collection.json" \
-e "RestfulBooker.postman_environment.json" \
-r cli,htmlextra \
--reporter-htmlextra-export reports/Detailed_Report.html
📚 What I Learned
API Automation from scratch
Postman collection design
Newman CLI execution
Real-world API chaining
Debugging API failures
Writing robust test assertions
Generating QA-grade reports
🔮 Future Improvements
CI/CD Integration (GitHub Actions)
Jenkins Pipeline Execution
Dockerized Newman Runner
Schema Validation (JSON Schema)
Parallel Execution
Advanced Reporting Dashboard
👨‍💻 Author

Akash Roy
🎓 Computer Science & Engineering Student
🧪 QA | API Automation | Software Testing Enthusiast
🚀 Future SQA Engineer

⭐ Repository Purpose

This project demonstrates a real-world API automation testing lifecycle using industry-standard tools, focusing on:

✔ Automation
✔ Reusability
✔ Scalability
✔ Professional reporting
✔ QA best practices
