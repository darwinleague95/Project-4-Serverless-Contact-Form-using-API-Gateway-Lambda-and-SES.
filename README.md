# Project-4-Serverless-Contact-Form-using-API-Gateway-Lambda-and-SES.

## 📋 Project Overview

This project demonstrates how to build a **Serverless Contact Form** that:
- Collects user input via an HTML form.
- Sends the form data to **AWS Lambda** via **API Gateway**.
- Uses **Amazon SES (Simple Email Service)** to deliver the form data as an email.

No backend server is required — this is a fully serverless application using AWS.

---

## 🛠️ Key AWS Services Used
- **Amazon API Gateway**: Receives HTTP POST requests from the contact form.
- **AWS Lambda**: Processes the form data and triggers email delivery.
- **Amazon SES**: Sends the email with the submitted contact form details.

---

## 🧩 Project Architecture

```plaintext
User (Form Submission)
          ↓
   API Gateway (HTTP POST)
          ↓
   AWS Lambda (Python)
          ↓
Amazon SES (Email Service)
          ↓
    Email Sent to Inbox
