# 🏥 Smart Healthcare Monitoring System Using AWS

**A cloud-based healthcare monitoring platform designed to help doctors monitor patient health conditions and identify critical cases through a centralized dashboard.**

## 📌 Project Overview

The **Smart Healthcare Monitoring System** is a web-based healthcare application designed to simplify patient monitoring and improve communication between doctors and patients.

The system provides separate dashboards for doctors and patients. Doctors can monitor patient vital signs, review health information, identify patients who require immediate attention, and track their availability. Patients can view their health information through a dedicated portal.

The project is designed around AWS cloud services to support secure data storage, serverless processing, and automated health alerts.

## 🎯 Objectives

- Develop a centralized platform for monitoring patient health.
- Provide separate login interfaces for doctors and patients.
- Display patient vital signs in an easy-to-understand dashboard.
- Identify patients with abnormal health readings.
- Generate alerts when vital readings cross predefined thresholds.
- Explore AWS cloud services for healthcare data management.
- Improve communication between patients and healthcare professionals.

## ✨ Key Features

### 👨‍⚕️ Doctor Dashboard
- View patient information.
- Monitor patient vital signs.
- Identify patients requiring immediate attention.
- View detailed patient information.
- Update doctor availability status.
- Review patient health alerts.

### 🧑‍🦽 Patient Dashboard
- Access a dedicated patient portal.
- View personal health information.
- Monitor vital readings.
- View doctor availability information.

### 🚨 Health Alert System
- Check patient readings against predefined thresholds.
- Identify potentially critical patient conditions.
- Display alert notifications.
- Maintain an alert log in the dashboard.

### 📂 CSV Data Upload
- Upload patient health records through a CSV file.
- Process uploaded patient information.
- Display patient records in the dashboard.
- Identify abnormal readings using threshold-based checks.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Webpage structure |
| CSS3 | Styling and layout |
| JavaScript | Frontend functionality |
| Tailwind CSS | Responsive user interface |
| Google Fonts | Typography |
| Amazon S3 | Cloud storage for patient datasets |
| AWS Lambda | Serverless data processing |
| Amazon DynamoDB | NoSQL patient data storage |
| Amazon SNS | Health alert notifications |
| Amazon API Gateway | Backend API communication |

*Note: The AWS services listed describe the intended cloud architecture. Actual integration requires the corresponding backend services and API configuration.*

## ☁️ AWS Architecture

The proposed system uses the following AWS components:

1. **Amazon S3:** Stores uploaded patient CSV datasets.
2. **AWS Lambda:** Processes patient health information and performs threshold checks.
3. **Amazon DynamoDB:** Stores structured patient information and health records.
4. **Amazon SNS:** Sends notifications when critical health conditions are detected.
5. **Amazon API Gateway:** Provides API endpoints for communication between the frontend and backend.

### System Workflow

```text
        Patient Health CSV
                |
                v
          Amazon S3
                |
                v
          AWS Lambda
                |
        Health Data Processing
                |
          +-----+-----+
          |           |
          v           v
      DynamoDB     Threshold Check
          |           |
          |           v
          |        Amazon SNS
          |           |
          |           v
          |     Alert Notification
          |
          v
      API Gateway
          |
          v
     Web Dashboard
       /       \
      v         v
   Doctor    Patient
   Portal     Portal
```

## 📁 Project Structure

```text
Smart-Healthcare-Monitoring-System/
│
├── index.html
│
├── healthcare_monitoring_javascript.js
│
├── README.md
│
└── screenshots/
    ├── login-page.png
    ├── doctor-dashboard.png
    └── patient-dashboard.png
```

*The structure above is a suggested GitHub organization. Update it to match the files in your actual repository.*

## 🚀 Getting Started

### Prerequisites

- A computer with an internet connection.
- Visual Studio Code or another code editor.
- A modern web browser.
- An AWS account for cloud-service integration.

### Installation

**Step 1: Clone the repository**

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

**Step 2: Open the project folder**

```bash
cd Smart-Healthcare-Monitoring-System
```

**Step 3: Open the application**

Open `index.html` in your browser, or use the Live Server extension in Visual Studio Code.

**Step 4: Explore the application**

- Open the login interface.
- Select the doctor or patient role.
- Explore the respective dashboard.
- Upload a patient CSV file to test the data-processing interface.
- Explore the health alert and patient information sections.

## 📊 Health Monitoring

The application is designed to monitor patient vital readings such as:

- SpO₂ (Blood Oxygen Saturation)
- Heart Rate
- Other available patient health measurements

The system uses predefined thresholds to identify abnormal readings. These thresholds are intended for demonstration purposes and should not be treated as medical diagnosis criteria.

## 🔮 Future Enhancements

- Complete integration with AWS Lambda and API Gateway.
- Real-time patient data synchronization using DynamoDB.
- Actual Amazon SNS notification delivery.
- Secure authentication and role-based access control.
- Integration with wearable health-monitoring devices.
- Historical health records and trend visualization.
- Improved data privacy and security.

## 🔐 Security Considerations

Healthcare information is sensitive. A production deployment should implement:

- Secure authentication and authorization.
- HTTPS communication.
- AWS IAM least-privilege permissions.
- Encryption of stored and transmitted data.
- Proper validation of uploaded CSV files.
- Protection of patient information and API endpoints.

Do not upload real patient records, AWS credentials, API secrets, or other confidential information to a public GitHub repository.

## 👨‍💻 Project Information

**Project Title:** Smart Healthcare Monitoring System Using AWS Services

**Developed By:** Trilokesh Panda

**Registration Number:** 24BDS1095

**Branch:** B.Tech – Data Science

**Institution:** VIT Chennai

**Domain:** Cloud Computing | Healthcare Technology | Web Development

## 📜 License

This project is intended for educational and academic purposes. You may add an MIT License if you wish to permit reuse and modification under its terms.

---

⭐ **If you find this project interesting, consider giving the repository a star!**
