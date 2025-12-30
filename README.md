# 🏃 Sports Performance Tracker with AI Insights

A full-stack fitness tracking application that allows users to log workouts, visualize progress,
upload activity files, and receive AI-powered performance insights with a downloadable training plan.

---

## Features

- User authentication (Signup / Login)
- Log workouts (type, duration, calories, etc.)
- Upload workout data (CSV / GPX)
- Interactive analytics dashboards (charts & trends)
- AI-powered performance analysis using **Google Gemini**
- Export AI-generated weekly training plan as **PDF**
- Modern UI with **Tailwind CSS** & reusable components

---

## Tech Stack

### Frontend
- React (Vite)
- Tailwind CSS
- Victory Charts
- React Markdown
- jsPDF

### Backend
- Node.js
- Express.js
- MongoDB (Mongoose)
- JWT Authentication
- Multer (file uploads)
- Google Gemini AI API

---

## Project Structure

```text
Sports-Performance-Tracker-with-AI-Insights/
├── client/        # Frontend (React)
├── server/        # Backend (Express + MongoDB)
├── _docs/         # Screenshots & demo PDFs
├── _SAMPLE_DEMO_ACCOUNT.md
├── .gitignore
└── README.md
```
## Deployment (Optional)

The application can be deployed using:

- Frontend: Vercel / Netlify
- Backend: Render / Railway
- Database: MongoDB Atlas

Local setup is sufficient for evaluation.

## Setup Instructions

### Backend

```bash
cd server
npm install
cp .env.example .env
npm run dev
```

### Frontend

```bash
cd client
npm install
npm run dev
```
