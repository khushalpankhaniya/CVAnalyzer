# CV Analyzer - Resume Parsing Web Application

A **web-based application** built with **Flask** that allows users to upload resumes (PDF, DOC, DOCX) and automatically extracts key information such as **Name, Email, Phone, Skills, Education, and Experience**. The extracted data is displayed on an **admin dashboard**, making it easy for HR teams or recruiters to review candidate profiles efficiently.

---

## Features

- **Upload Resume:** Users can upload their resumes through a user-friendly interface.
- **Automatic Parsing:** Extracts relevant information from resumes:
  - Name
  - Email
  - Phone number
  - Skills (automatically detected)
  - Education (degrees, diplomas, certifications)
  - Experience (years)
- **Admin Dashboard:** View all uploaded resumes and their parsed information.
- **Download Resumes:** Download the uploaded resumes from the dashboard.
- **Delete Functionality:** Admin can remove resumes and their extracted data.
- **Responsive UI:** Mobile-friendly design for both the upload page and dashboard.
- **Supported Formats:** PDF, DOC, DOCX.

---

## Tech Stack

- **Backend:** Python, Flask
- **Frontend:** HTML, CSS, JavaScript
- **Resume Parsing:** `pdfplumber` (PDF), `python-docx` (DOCX)
- **Data Storage:** Local file system (`static/uploads/`)

---

## Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/CVAnalyzer.git
   cd CVAnalyzer
