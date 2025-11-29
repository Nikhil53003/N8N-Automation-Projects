# Social Media Content Generator With Approval System

AI-powered automation workflow built using **n8n**, **Google Gemini**, **Google Sheets** & **Gmail**.  
This system fully automates idea collection, content generation, approvals, and publishing logs for LinkedIn & Instagram.

---


## 🚀 Overview

This project is a **fully automated social media content pipeline** that eliminates manual content creation and approval processes.  
It uses **AI (Gemini)** to generate platform-ready posts, sends **HTML approval emails**, and logs everything to **Google Sheets** after approval.

Perfect for:  
✔ Social media teams  
✔ Agencies  
✔ Solopreneurs  
✔ Marketing automation setups  

---

## ⚙️ System Architecture


---

## ✨ Key Features

### 🔹 1. AI-Generated Content
Automatically generates:

- LinkedIn post text + hashtags  
- Instagram caption + emojis + hashtags  

Output is clean **JSON** for reliability.

---

### 🔹 2. HTML Approval Email
Creates a modern, styled approval email that includes:

- Topic  
- LinkedIn content  
- Instagram content  
- Hashtags  
- Item-by-item layout  

---

### 🔹 3. Google Sheets Sync
Logs:

- Content  
- Hashtags  
- Status  
- Date  
- Platform output  

---

### 🔹 4. Scheduled Automation
Trigger daily/weekly auto-runs via the **n8n schedule node**.

---

### 🔹 5. Full Multi-Item Support
Aggregates all content ideas → builds a combined email → splits and logs approved items.

---

## 🛠️ Tech Stack

| Component | Technology |
|----------|------------|
| Automation Engine | n8n |
| AI Generator | Google Gemini (PaLM) |
| Email System | Gmail API (OAuth2) |
| Data Source | Google Sheets |
| Scripting | JavaScript (Code Nodes) |
| Storage | Google Sheets |

---

## 📂 Project Structure


---

## 🔧 Setup Instructions

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/social-media-content-generator.git
cd social-media-content-generator

2️⃣ Import Workflow Into n8n

Open n8n

Click Import Workflow

Upload the .json file

3️⃣ Add Required Credentials

Inside n8n:

Service	Credential Needed
Google Sheets	OAuth2 API
Gmail	OAuth2 API
Google Gemini	API Key
4️⃣ Connect Your Sheet

Ensure your Google Sheet contains:

Topic Title

LinkedInPost

LinkedIn Hashtags

InstagramPost

Instagram Hashtags

Status

Date

row_number

▶️ Usage

✔ Add topics to the Google Sheet
✔ Workflow runs automatically (or manually)
✔ AI generates posts
✔ Approver receives an HTML email
✔ Approve or reject using built-in buttons
✔ Approved posts get logged in Google Sheets

📸 Screenshots (Add your own)
Workflow Overview

/screenshots/workflow-diagram.png

Approval Email Preview

/screenshots/email-preview.png

Google Sheet Output

/screenshots/google-sheet.png

🚀 Future Improvements

Auto-post directly to LinkedIn & Instagram

Add AI-generated images for each post

Add analytics dashboard for content performance

Add multi-user approval routing

👨‍💻 Author

Nikhil
AI Automation Engineer | n8n Specialist | Workflow Developer

If you found this project helpful, please ⭐ star this repository!
