# HIREAHEAD — Quick Overview

💼 HireAhead — Streamlined Hiring Platform

HireAhead is a full-stack web application designed to simplify the recruitment process by connecting employers and candidates through an intuitive, secure, and role-based system.

⚙️ Key Highlights

Employers: Easily post, edit, or delete job listings and view applicant details from a centralized dashboard.

Candidates: Browse available jobs, apply seamlessly by uploading resumes, and manage all applications in one place.

Security & Efficiency: Includes role-based authentication, password hashing, and centralized error handling for a reliable user experience.

A full‑stack job portal:
- Backend: Node.js + Express + MongoDB (Mongoose), JWT auth, Cloudinary file uploads.
- Frontend: React (Vite).

Run locally (Windows)
1. Backend
   - cd backend
   - npm install
   - copy config/config.env and set MONGO_URI, JWT_SECRET, CLOUDINARY_* (and FRONTEND_URL)
   - npm run dev

2. Frontend
   - cd my-react-app
   - npm install
   - npm run dev

