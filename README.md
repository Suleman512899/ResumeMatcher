# Resume Matcher AI

## 📌 Overview

Resume Matcher AI is an intelligent web application that analyzes resumes and matches them with job descriptions using Artificial Intelligence. The system extracts skills from uploaded resumes, compares them against job requirements, calculates a matching score, and provides AI-powered recommendations to improve candidate-job alignment.

The application is built using **ASP.NET Core MVC**, **SQLite**, **Groq LLaMA AI API**, and modern frontend technologies such as **Bootstrap**, **jQuery**, and **Three.js**.

---

## 🚀 Features

### 📄 Resume Parsing

* Upload resumes in PDF format.
* Extract resume content automatically using iText7.

### 🤖 AI Skill Extraction

* Uses Groq AI to identify and extract technical and soft skills from resumes.
* Detects relevant keywords and competencies.

### 🎯 Job Matching

* Compares candidate skills with job requirements.
* AI-powered matching using Groq LLaMA models.

### 📊 Match Score Calculation

* Calculates compatibility percentage between resume and job description.
* Custom scoring logic implemented in C#.

### 💡 AI Recommendations

* Suggests missing skills.
* Provides recommendations to improve job compatibility.

### 📈 Dashboard Analytics

* View resume analysis results.
* Display matching scores and extracted skills.
* User-friendly dashboard interface.

### 🗄 Database Storage

* Stores resumes, job descriptions, matching scores, and recommendations.
* Powered by SQLite database.

### 🎨 Modern User Interface

* Responsive Bootstrap design.
* Interactive Three.js visual effects.
* Real-time UI updates using jQuery.

---

## 🛠 Technologies Used

### Backend

* ASP.NET Core MVC
* C#
* Entity Framework Core

### Database

* SQLite

### Artificial Intelligence

* Groq AI API
* LLaMA Models

### Frontend

* HTML5
* CSS3
* JavaScript
* Bootstrap
* jQuery
* Three.js

### Resume Processing

* iText7 PDF Parser

---

## 🏗 System Architecture

```text
User
 ↓
Bootstrap UI / jQuery
 ↓
ASP.NET Core MVC Controllers
 ↓
Entity Framework Core
 ↓
SQLite Database
 ↓
Groq LLaMA AI API
 ↓
Results Processing
 ↓
Dashboard Display
```

---

## 📂 Project Structure

```text
ResumeMatcherAI/
│
├── Controllers/
├── Models/
├── Views/
├── wwwroot/
│   ├── css/
│   ├── js/
│   └── assets/
│
├── Data/
├── Services/
├── AI/
├── ResumeParser/
├── Database/
├── appsettings.json
├── Program.cs
└── README.md
```

---

## ⚙ Installation

### Prerequisites

* .NET 8 SDK (or latest version)
* Visual Studio 2022
* SQLite
* Groq API Key

### Clone Repository

```bash
git clone https://github.com/yourusername/resume-matcher-ai.git
cd resume-matcher-ai
```

### Restore Packages

```bash
dotnet restore
```

### Configure API Key

Add your Groq API key in:

```json
{
  "GroqSettings": {
    "ApiKey": "YOUR_API_KEY"
  }
}
```

### Run Application

```bash
dotnet run
```

Application will be available at:

```text
https://localhost:5001
```

---

## 🔄 Workflow

1. User uploads a PDF resume.
2. iText7 extracts resume content.
3. Groq AI extracts skills and experience.
4. User enters or selects a job description.
5. AI compares resume against job requirements.
6. Matching score is calculated.
7. AI generates recommendations.
8. Results are stored in SQLite.
9. Dashboard displays analytics and matching results.

---

## 📊 Future Enhancements

* Multiple resume comparison
* Resume ranking system
* Recruiter dashboard
* Job portal integration
* Email notifications
* Advanced analytics
* Export reports to PDF
* User authentication and authorization

---

## 🎯 Use Cases

* HR Recruitment
* Applicant Screening
* Resume Evaluation
* Career Guidance
* Skill Gap Analysis
* Job Recommendation Systems

---


