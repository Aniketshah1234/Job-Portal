# <p align="center">💼 JobPortal: The Ultimate MERN Recruitment Suite</p>

<p align="center">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" />
  <img src="https://img.shields.io/badge/Redux_Toolkit-764ABC?style=for-the-badge&logo=redux&logoColor=white" />
</p>

---

## 📖 Executive Summary
**JobPortal** is a high-performance, full-stack recruitment platform designed to streamline the hiring process. Built with the **MERN stack**, it provides a seamless interface for job seekers to discover opportunities and for recruiters to manage talent. The application features **secure JWT-based authentication**, real-time state management via **Redux Toolkit**, and cloud-based media storage via **Cloudinary**. This project showcases a scalable architecture ready for production-level deployment.

---

## ✨ Features & Technical Implementation

| Feature | ⚙️ Technical Implementation |
| :--- | :--- |
| 🔐 **Role-Based Auth** | Utilizes **JWT (JSON Web Tokens)** stored in HTTP-only cookies to distinguish between `Student` and `Recruiter` roles. Secured via custom backend middleware. |
| 🏢 **Company Profiles** | Recruiters can register companies, upload logos via **Cloudinary**, and manage branding. Data is persistent and linked to job postings. |
| 📄 **Job Lifecycle** | Full CRUD functionality for jobs. Recruiters can post, update, and close listings, while candidates can browse using advanced search filters. |
| 📁 **Resume Management** | Seamlessly handles `.pdf` and image uploads using **Multer** and **DataURI** to stream files directly to the cloud, ensuring high availability. |
| ⚡ **Reactive State** | Global state management via **Redux Toolkit** ensures that job lists and user profiles update instantly across the UI without refreshing. |

---

## 🏗️ System Architecture

```text
jobportal/
├── 📁 backend/
│   ├── 📁 controllers/    # Logic for Jobs, Users, and Applications
│   ├── 📁 models/         # Mongoose Schemas (User, Job, Company)
│   ├── 📁 routes/         # Express API route definitions
│   └── 📄 index.js        # Server entry point
└── 📁 frontend/
    ├── 📁 src/
    │   ├── 📁 redux/      # Store and Slices
    │   └── 📁 pages/      # Home, Jobs, Admin Dashboards
---
🚀 Installation & Local Development
1. Clone & Install
git clone [https://github.com/Aniketshah1234/jobportal.git](https://github.com/your-username/jobportal.git)
cd jobportal
---
# Install Backend
cd backend && npm install

# Install Frontend
cd ../frontend && npm install
---
2. Configure Environment
Create a .env file in the backend directory:
---

-----

## 📌 Live Demo

[🚀 Click here to view the deployed project](https://6943fd8475772f053a2d0f1a--celadon-bonbon-0835ee.netlify.app//)


-----

---



