# 🚀 Secure File Upload System (Healthcare)

A GUI-less, serverless solution to securely upload healthcare files (lab reports, prescriptions, etc.) to AWS S3 via API Gateway and Lambda. Designed with simplicity, scalability, and HIPAA/GDPR-aligned security in mind.

---

## 🔧 Technologies Used

- **AWS S3 (via Console GUI)** – Secure object storage
- **AWS Lambda (Python)** – Backend function to handle upload logic
- **AWS API Gateway (REST)** – Public endpoint to trigger Lambda
- **IAM Roles & Policies** – Fine-grained permissions
- **Postman** – API testing client
- **GitHub** – Code and documentation version control

---

## 🎯 Project Goals

- Build a lightweight file upload API for healthcare systems  
- Avoid frontend complexity; simulate file upload via Postman  
- Maintain secure, auditable uploads to an S3 bucket  
- Serve as a reusable pattern for healthcare/e-commerce file APIs

---

## 📈 Architecture

![Flowchart](docs/architecture_flowchart.png)

> The system flow includes:
> 1. Client sends a POST request (with file + metadata) via Postman
> 2. API Gateway triggers a Lambda function
> 3. Lambda reads file and uploads securely to a predefined S3 bucket
> 4. Response sent back with status & metadata

---

## 📂 Folder Structure

<img width="879" height="233" alt="image" src="https://github.com/user-attachments/assets/81f27383-4653-43f3-b7e5-07cddff07103" />

