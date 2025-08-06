# Daily-AI-Newsletter-n8n-
Automated workflow that fetches the latest news, summarizes it using Google Gemini, and sends a daily email newsletter. Built with n8n for seamless automation.
Features
✅ Fetches the latest AI news from multiple sources using RSS or APIs

✅ Summarizes long articles into concise, reader-friendly snippets with Google Gemini

✅ Automatically composes and sends daily email newsletters

✅ Fully customizable for topics, frequency, and recipients

Tech Stack
n8n – Automation Platform

Google Gemini – AI for summarization

RSS Feeds / News APIs – News Source

Gmail / SMTP – Email Delivery

📂 Project Workflow
Fetch News – Use RSS Feed or News API

Summarize – Send articles to Google Gemini for concise summaries

Format Newsletter – Create a clean HTML email

Send Email – Use Gmail/SMTP node in n8n

⚙️ Setup Instructions
Install n8n

n8n Installation Guide

Create Credentials

Google Gemini API Key

Gmail or SMTP for email sending

Import Workflow

Download and import the provided workflow.json file into n8n

Configure Nodes

Add your RSS Feed URLs

Add Gemini API Key in HTTP Request node

Set email recipient details

Activate the Workflow

Schedule it to run daily

📸 Workflow Diagram
(Add an image of your n8n workflow here – you can take a screenshot from your n8n UI and upload it.)
