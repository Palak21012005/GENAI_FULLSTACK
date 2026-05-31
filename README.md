# AI-Powered Interview Preparation Platform

A full-stack GenAI-powered interview preparation platform that helps users analyze job descriptions and resumes to generate personalized interview preparation strategies.

## Features

* Secure JWT Authentication
* Resume Upload & Analysis
* Job Description Analysis
* AI-Generated Technical Questions
* AI-Generated Behavioral Questions
* Skill Gap Identification
* Personalized Preparation Roadmaps
* Resume PDF Generation
* Responsive Modern UI

## Tech Stack

### Frontend

* React.js
* JavaScript (ES6+)
* HTML5
* CSS3
* SCSS
* Bootstrap

### Backend

* Node.js
* Express.js
* MongoDB
* JWT Authentication
* Multer

### AI Integration

* Google Gemini AI

## Project Structure

```text
Backend/
├── src/
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   ├── middlewares/
│   ├── services/
│   └── config/

Frontend/
├── src/
│   ├── features/
│   ├── components/
│   ├── hooks/
│   └── services/
```

## Installation

### Clone Repository

```bash
git clone [<repository-url>](https://github.com/Palak21012005/GENAI_FULLSTACK.git)
cd interview-ai-yt
```

### Backend Setup

```bash
cd Backend
npm install
```

Create a `.env` file:

```env
PORT=3000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
GOOGLE_GENAI_API_KEY=your_gemini_api_key
```

Start Backend:

```bash
npm start
```

### Frontend Setup

```bash
cd Frontend
npm install
npm run dev
```

## Usage

1. Register/Login
2. Paste a Job Description
3. Upload a Resume or provide a Self Description
4. Generate an Interview Strategy
5. Review Technical Questions
6. Review Behavioral Questions
7. Analyze Skill Gaps
8. Follow the Personalized Roadmap

## Future Improvements

* Interview Simulation
* Voice-Based Mock Interviews
* Company-Specific Interview Sets
* ATS Resume Scoring
* Multi-Language Support

## Author

Palak Singh
