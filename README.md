## Smart Healthcare Monitoring System Using AWS Services

The Smart Healthcare Monitoring System is a cloud-based healthcare application developed using Amazon Web Services (AWS) to simplify patient health monitoring and improve communication between doctors and patients. The primary objective of this project is to provide an efficient and reliable platform for monitoring patient health conditions, managing medical information, and identifying potential health risks through automated alerts.

The system uses **Amazon S3** to store patient health records and CSV files containing vital information such as oxygen saturation (SpO2) and other health parameters. **AWS Lambda** is used to process the uploaded data, perform backend operations, and evaluate patient health conditions based on predefined threshold values. **Amazon DynamoDB** stores and manages patient-related information, enabling efficient retrieval and access to health records. **Amazon SNS (Simple Notification Service)** is integrated to generate automated notifications whenever a patient's vital readings cross predefined safety limits. **Amazon API Gateway** connects the AWS backend services with the web-based application and enables communication between the frontend and backend.

The application provides two separate dashboards: a Doctor Dashboard and a Patient Dashboard. The Doctor Dashboard allows doctors to view patient records, monitor their health conditions, identify patients who require immediate attention, and access relevant medical information. The Patient Dashboard enables patients to view their personal health information, monitor their vital readings, and check their current health status.

One of the key features of this project is its automated alert mechanism, which helps identify abnormal health readings and notify patients when their vital parameters exceed the defined limits. This supports early identification of potential health concerns and encourages timely medical attention.

The project demonstrates how cloud computing and serverless architecture can be used to develop scalable and cost-effective healthcare solutions. By integrating multiple AWS services with web technologies, the system aims to make healthcare monitoring more accessible, organized, and efficient while reducing the need for continuous manual monitoring.

**Technologies Used:** Amazon S3, AWS Lambda, Amazon DynamoDB, Amazon SNS, Amazon API Gateway, HTML, CSS, JavaScript, and CSV datasets.
