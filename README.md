# AI Powered HR Resume Screening System (n8n)

An advanced AI-driven HR automation workflow built using n8n that automatically screens resumes, verifies candidate authenticity using LinkedIn data, scores applicants with AI, and sends automated HR responses.

---


# Features

## Resume Parsing
- Extracts text from uploaded PDF resumes
- Supports automated candidate processing

## AI-Based Candidate Scoring
- Uses OpenRouter LLM for intelligent resume evaluation
- Calculates:
  - AI Score
  - Match Percentage
  - Hiring Decision

## LinkedIn Verification
- Extracts LinkedIn profile from resume
- Scrapes candidate LinkedIn data using Apify
- Detects:
  - Fake experience
  - Skill mismatches
  - Date inconsistencies
  - Education mismatches

## Automated HR Workflow
- Shortlist candidates automatically
- Send interview emails
- Send rejection emails
- Maintain merit lists

## HR Notifications
- Slack alerts for HR team
- Google Sheets logging system

---

# Tech Stack

- n8n
- OpenRouter AI
- Apify LinkedIn Scraper
- Google Sheets API
- Slack API
- Gmail API

---

# Workflow Overview

1. Candidate submits application form
2. Resume text extracted
3. Job description fetched
4. LinkedIn profile extracted
5. LinkedIn verification performed
6. AI evaluates candidate
7. Candidate scored automatically
8. HR emails triggered
9. Data stored in Google Sheets
10. Slack notification sent

---

# Workflow Screenshot

Add your workflow screenshot here.

---

# Installation

## Import Workflow

1. Open n8n
2. Click Import Workflow
3. Upload the JSON file

---

# Required Credentials

Configure these credentials inside n8n:

- OpenRouter API
- Google Sheets OAuth
- Gmail OAuth
- Slack OAuth
- Apify API

---

# Decision Logic

| Score | Result |
|---|---|
| 7+ | Shortlisted |
| 5-7 | Merit List |
| Below 5 | Rejected |

---

# Verification Logic

The workflow compares:
- Resume vs LinkedIn
- Experience consistency
- Skills match
- Education authenticity

---

# Use Cases

- HR Automation
- Resume Screening
- Recruitment Agencies
- AI Hiring Systems
- Candidate Verification

---

# Future Improvements

- ATS Integration
- Multi-language support
- Voice interview AI
- Face verification
- Advanced fraud detection

---

# Author

Made by CIA India

---

# License

MIT License
