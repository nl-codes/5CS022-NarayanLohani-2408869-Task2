# Assessment Submission - Task 2  
**Module:** 5CS022 – Distributed and Cloud Computing

This repository contains the required files for the submission of **Task 2** of the 5CS022 module. The task demonstrates deployment of static web content using two AWS services: **S3** and **Amplify**.

---

## 🗂️ Files in This Repo (For AWS Amplify)

- `page1.html` – A static HTML page linked from `index.html`.  
- `page2.html` – Another static page linked from `index.html`.  
- `image1.png` – Image used by the pages above.

These files are hosted via **AWS Amplify**.

> Both `page1.html` and `page2.html` contain anchor (`<a>`) tags that link back to an `index.html` file hosted separately on **AWS S3**.

---

## 🌐 index.html (Hosted via AWS S3)

- `index.html` is hosted on **AWS S3** as a static website.
- It acts as the **entry point**, containing two buttons/links:
  - One link to `page1.html`
  - One link to `page2.html`

> The links point to the Amplify-hosted versions of those pages.

---

## ✅ Hosting Overview

| File/Component | Hosting Platform |
|----------------|------------------|
| `index.html`   | AWS S3           |
| `page1.html`   | AWS Amplify      |
| `page2.html`   | AWS Amplify      |
| `image1.png`   | AWS Amplify      |

---

## 🚀 Deployment Instructions (for Reviewers)

### 1. AWS S3 Setup (for `index.html`)
- Upload `index.html` to an S3 bucket.
- Enable **Static Website Hosting**.
- Make the file publicly accessible (or as instructed).
- Note the S3 endpoint URL for access.

### 2. AWS Amplify Setup (for this repo)
- Connect this GitHub repository to AWS Amplify.
- Select the main branch and deploy.
- Amplify will provide a public URL.

> Ensure that the `index.html`'s links to `page1.html` and `page2.html` use the correct Amplify URLs.

---

## 📌 Note

This setup is part of the assessment task and is intended for demonstration only.

---
