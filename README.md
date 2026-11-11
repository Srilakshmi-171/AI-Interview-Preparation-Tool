
# AI Interview Preparation Tool

An AI-powered interview preparation platform designed to help candidates improve their technical knowledge and interview skills through practice questions and mock interviews.

## About the Project

The AI Interview Preparation Tool provides an interactive platform where users can explore interview questions, practice technical interviews, and track their preparation progress.

It integrates Google's Gemini API to generate AI-powered interview content.

## Features

- User Registration and Login
- AI-powered Interview Question Generation
- Mock Interview Practice
- Multiple Technical Roles and Topics
- Interview Preparation Dashboard
- User Progress Tracking
- Practice History and Performance Summary

## Technologies Used

**Frontend**
- HTML5
- CSS3
- JavaScript

**Backend**
- Node.js
- Express.js

**Database**
- MongoDB
- Mongoose

**AI Integration**
- Google Gemini API

## Project Structure

```text
AI-Interview-Preparation-Tool/
├── Main/
│   ├── Dashboard/
│   ├── Mock-Interview/
│   ├── Roles/
│   └── interview-questions-ai/
├── images/
├── singup/
├── index.html
├── script.js
├── style.css
├── server.js
├── package.json
├── package-lock.json
├── .gitignore
└── README.md
```

## Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/Srilakshmi-171/AI-Interview-Preparation-Tool.git
```

### 2. Navigate to the project directory

```bash
cd AI-Interview-Preparation-Tool
```

### 3. Install dependencies

```bash
npm install
```

### 4. Configure environment variables

Create a `.env` file in the project root directory.

Add your own Gemini API key and MongoDB connection string using the variable names expected by `server.js`.

Example:

```env
GEMINI_API_KEY=your_gemini_api_key
```

Do not upload your `.env` file or expose your API key publicly.

### 5. Start the backend server

```bash
node server.js
```

### 6. Open the application

Open `index.html` in your browser to access the frontend.

## Future Enhancements

- Advanced interview performance analytics
- Improved AI-based answer evaluation
- Additional technical interview categories
- Enhanced user experience and interface

## Author

**Srilakshmi**

GitHub: [Srilakshmi-171](https://github.com/Srilakshmi-171)
