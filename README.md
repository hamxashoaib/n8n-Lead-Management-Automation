# 🚀 n8n Lead Management Automation

An end-to-end lead management workflow built with **n8n** that automatically captures form submissions, detects duplicate leads, stores unique records in Google Sheets, and sends personalized confirmation emails.

Designed to eliminate repetitive manual work, improve response times, and streamline the lead management process.

---

## ✨ Features

- Automatically captures new Google Form submissions
- Cleans and maps incoming lead data
- Detects duplicate email addresses
- Prevents duplicate lead entries
- Stores unique leads in Google Sheets
- Sends personalized Gmail confirmation emails
- Fully automated workflow with no manual intervention

---

## 🛠️ Tech Stack

- n8n
- Google Forms
- Google Sheets
- Gmail
- Google OAuth
- REST APIs
- Docker

---

## 🔄 Workflow

```text
Google Form
      │
      ▼
Google Sheets Trigger
      │
      ▼
Edit Fields
      │
      ▼
Duplicate Check
      │
 ┌────┴────┐
 │         │
 ▼         ▼
Duplicate  New Lead
 │          │
 ▼          ▼
Stop     Append Lead
              │
              ▼
 Send Confirmation Email

---

## 📂 Repository Structure

```
n8n-Lead-Management-Automation/
│
├── workflow/
│   └── n8n-Lead-Management-Automation.json
│
├── images/
│   └── workflow.png
│
├── README.md
└── LICENSE
```

---

## 🚀 Getting Started

1. Clone this repository

```bash
git clone https://github.com/hamxashoaib/n8n-Lead-Management-Automation.git
```

2. Import the workflow into n8n.

3. Configure your credentials:
   - Google Sheets OAuth
   - Gmail OAuth

4. Replace the placeholder Spreadsheet ID with your own.

5. Activate the workflow.

---

## 💼 Business Value

This workflow helps businesses:

- Reduce repetitive manual tasks
- Eliminate duplicate lead records
- Organize leads automatically
- Respond instantly to new inquiries
- Improve lead management efficiency

---

## 👨‍💻 Author

**Hamza Shoaib**

AI Automation Engineer

- GitHub: https://github.com/hamxashoaib
- LinkedIn: https://www.linkedin.com/in/ch-hamza-shoaib/

---

⭐ If you found this project useful, consider giving it a star.
