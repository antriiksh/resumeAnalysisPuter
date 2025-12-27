# AI Resume Analyzer

An AI-powered web application that analyzes resumes against specific job descriptions to provide ATS (Applicant Tracking System) scores, improvement tips, and detailed feedback.

## 🚀 Features

- **AI Analysis**: Uses Puter.js AI to analyze your resume and provide feedback based on a job title and description.
- **ATS Scoring**: Get an estimate of how well your resume matches the job requirements.
- **PDF Processing**: Upload your resume in PDF format, which is automatically processed and analyzed.
- **Application Tracking**: Keep track of all your resume submissions and the feedback received for each.
- **Modern Tech Stack**: Built with React Router v7, Tailwind CSS, and Puter.js.

## 🛠️ Tech Stack

- **Framework**: [React Router v7](https://reactrouter.com/) (formerly Remix)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **AI & Backend**: [Puter.js](https://puter.com/) (for Cloud Storage, KV Store, and AI capabilities)
- **PDF Library**: [pdfjs-dist](https://github.com/mozilla/pdf.js)
- **State Management**: [Zustand](https://github.com/pmndrs/zustand)

## 📋 Prerequisites

Before you begin, ensure you have the following installed:
- [Node.js](https://nodejs.org/) (v20 or higher recommended)
- [npm](https://www.npmjs.com/)

## ⚙️ Installation & Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/antriiksh/ai-resume-analyser.git
   cd ai-resume-analyser
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Development Mode**:
   Start the development server:
   ```bash
   npm run dev
   ```
   Open [http://localhost:5173](http://localhost:5173) in your browser.

4. **Build for Production**:
   ```bash
   npm run build
   ```

## 📂 Project Structure

- `app/components`: Reusable UI components (Navbar, FileUploader, ScoreGauge, etc.)
- `app/lib`: Core logic including Puter.js integration and PDF processing.
- `app/routes`: Application pages (Home, Upload, Resume analysis, etc.)
- `public`: Static assets like images and workers.

## 📄 License

This project is private and for educational purpose. Created by [Antriksh](https://github.com/antriiksh)

---
Built with ❤️ using React Puter.js
