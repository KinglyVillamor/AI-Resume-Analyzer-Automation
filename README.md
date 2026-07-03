# AI Resume Analyzer & Candidate Screening System

## Overview

The AI Resume Analyzer & Candidate Screening System is an end-to-end recruitment automation solution built with n8n and Google Gemini. The workflow automates resume intake, candidate evaluation, qualification scoring, document management, and applicant communication, significantly reducing manual screening effort for recruiters.

The system receives resumes through email, extracts and analyzes PDF content using AI, compares candidate qualifications against predefined job requirements, generates hiring recommendations, and automatically routes applicants through the appropriate recruitment process.

---

## Key Features

- Automated resume submission via email
- PDF resume extraction and text processing
- AI-powered candidate evaluation using Google Gemini
- Intelligent match scoring and recommendation generation
- Automated qualification filtering
- Candidate data storage in Google Sheets
- Resume archiving in Google Drive
- Automated approval and rejection email notifications
- End-to-end workflow automation with no manual intervention

---

## System Workflow

```text
Candidate Sends Resume
          │
          ▼
     Gmail Trigger
          │
          ▼
   PDF Text Extraction
          │
          ▼
   Google Gemini Analysis
          │
          ▼
 Candidate Scoring Engine
          │
          ▼
      Decision Logic
      ┌─────────────┐
      │   IF Node   │
      └──────┬──────┘
             │
     ┌───────┴────────┐
     ▼                ▼

  Rejected        Qualified
     │                │
     ▼                ▼
Rejection Email   Resume Storage
                  Google Drive
                        │
                        ▼
                Candidate Database
                  Google Sheets
                        │
                        ▼
                 Approval Email
```

---

## Technology Stack

### Workflow Automation
- n8n

### Artificial Intelligence
- Google Gemini API

### Cloud Services
- Gmail API
- Google Drive API
- Google Sheets API

### Data Processing
- PDF Extraction
- JSON Processing
- JavaScript Expressions

### Integration & Automation
- REST APIs
- Conditional Logic
- Email Automation
- Document Management

---

## AI Evaluation Structure

The system generates structured candidate assessments in JSON format:

```json
{
  "candidate_name": "John Doe",
  "skills": [
    "JavaScript",
    "HTML",
    "CSS"
  ],
  "match_score": 92,
  "strengths": [
    "Strong frontend development experience",
    "Experience with REST APIs"
  ],
  "missing_skills": [],
  "recommendation": "Proceed",
  "reason": "Candidate demonstrates strong alignment with the role requirements and possesses all core technical competencies."
}
```

---

## Business Value

This solution automates several time-consuming recruitment tasks:

- Resume collection
- Candidate screening
- Qualification assessment
- Applicant communication
- Resume organization
- Candidate record management

By leveraging AI-driven evaluation, recruiters can focus on interviewing qualified candidates instead of manually reviewing every application.

---


## Skills Demonstrated

This project showcases:

- Workflow Automation
- AI Integration
- API Integration
- Business Process Automation
- PDF Document Processing
- Conditional Logic Design
- Data Management
- Cloud Service Integration
- Recruitment Process Automation

---


## Author

**Kingly Villamor**

IT Graduate | AI Automation Enthusiast | Full-Stack Developer

This project was developed as part of my portfolio to demonstrate practical applications of AI, workflow automation, and business process optimization using modern cloud technologies.
