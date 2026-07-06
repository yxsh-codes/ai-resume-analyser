# AI Resume Analyser & Interview Preparation Platform

> This project is based on an open-source tutorial and has been adapted and is constantly being enhanced by me to deepen my understanding of full-stack development, AI integration, and software engineering practices.

An AI-powered web application that helps users optimize their resumes, analyze job descriptions, and prepare for interviews through intelligent feedback and personalized interview experiences.

## Features

- Upload and analyze resumes using AI
- Generate ATS-friendly resume insights
- Match resumes against job descriptions
- AI-powered interview question generation
- Personalized interview feedback and performance reports
- Secure user authentication
- Responsive and modern user interface

## Tech Stack

### Frontend
- React.js
- Vite
- JavaScript
- CSS
- Axios

### Backend
- Node.js
- Express.js
- MongoDB
- JWT Authentication
- REST APIs

### AI & Services
- Gemini API / OpenAI API
- PDF Processing
- Resume Parsing

## Project Structure

```
ai-resume-analyser/
│
├── Frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── Backend/
│   ├── src/
│   ├── server.js
│   └── package.json
│
└── README.md
```

## Installation

### Clone the repository

```bash
git clone https://github.com/yxsh-codes/ai-resume-analyser.git
```

### Install dependencies

Frontend

```bash
cd Frontend
npm install
npm run dev
```

Backend

```bash
cd Backend
npm install
npm start
```

## Environment Variables

Create a `.env` file inside the Backend directory and configure:

```env
PORT=5000
MONGODB_URI=your_database_url
JWT_SECRET=your_secret_key
GEMINI_API_KEY=your_api_key
```

## Future Improvements

- Voice-based AI interviews and connecting real interviewers as well
- Coding interview mode
- Interview analytics dashboard
- Resume version comparison and suggestions based on job description
- Multi-language support
- Recruiter dashboard

## Learning Outcomes

This project helped strengthen my understanding of:

- Full Stack Web Development
- REST API Development
- Authentication & Authorization
- AI API Integration
- Database Design
- Responsive UI Development
- Project Structure and Deployment

## Author

**Yash Chowrasia**

B.Tech, Electronics & Communication Engineering

NIT Durgapur