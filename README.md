# ORONIX Tasks

Oronix Tasks is a cloud-based task management application built on a fully serverless architecture using AWS architecture.
It allows users to securely create, update, and manage personal tasks from any device, with a separate admin panel and role-based access control.
The system is lightweight, scalable, and designed for seamless use across devices via a responsive web interface hosted on Amazon S3.

---

##  Features

- **Secure Authentication** — User sign-up, login, and session management via Amazon Cognito
- **Task Management** — Create, read, update, and delete personal tasks
- **Admin Panel** — Separate admin interface with elevated permissions
- **Accessible from Anywhere** — Fully cloud-hosted, no local setup needed
- **Responsive Design** — Works seamlessly across desktop and mobile browsers
- **Serverless Architecture** — Auto-scales with demand, zero server maintenance

---

## Main Screens
- **Login Screen**

   <img width="1602" height="758" alt="image" src="https://github.com/user-attachments/assets/dea25b99-79bc-4570-ab6c-d93a2d8fce13" />

- **Home Screen**

  <img width="1602" height="758" alt="image" src="https://github.com/user-attachments/assets/28143000-e6a9-4ce9-bb10-8d0168d2128d" />

- **Admin Screen**

  <img width="1602" height="758" alt="image" src="https://github.com/user-attachments/assets/231782b1-7100-4c9d-a568-38991ea2158e" />



  
---

## Architecture

```
Browser (S3 Static Site)
        │
        ▼
Amazon API Gateway
        │
        ▼
  AWS Lambda Functions
        │
        ▼
  Amazon DynamoDB
```

Authentication is handled by **Amazon Cognito**, which issues JWT tokens validated by API Gateway on every request.

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | HTML, CSS, JavaScript |
| Hosting | Amazon S3 (static website) |
| Authentication | Amazon Cognito |
| API | Amazon API Gateway |
| Business Logic | AWS Lambda |
| Database | Amazon DynamoDB |

---

## 📂 Project Structure

```
ORONIX_Tasks/
├── css/                  # Stylesheets
├── js/                   # JavaScript logic
├── logo and favicon/     # Branding assets
├── index.html            # Login / landing page
├── homePage.html         # User task dashboard
└── admin.html            # Admin panel
```

---

## About the Project

This project was developed as part of the Computer Science Bachelor's degree at **Ruppin Academic Center**, demonstrating practical use of cloud-native services and serverless architecture patterns.
