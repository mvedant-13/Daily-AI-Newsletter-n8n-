# Daily-AI-Newsletter-n8n-
Automated workflow that fetches the latest news, summarizes it using Google Gemini, and sends a daily email newsletter. Built with n8n for seamless automation.<br>

🚀 Features<br>
✅ Fetches the latest AI news from multiple sources using RSS or APIs<br>
✅ Summarizes long articles into concise, reader-friendly snippets with Google Gemini<br>
✅ Automatically composes and sends daily email newsletters<br>
✅ Fully customizable for topics, frequency, and recipients<br>
<br>
🛠 Tech Stack<br>
n8n – Automation Platform<br>
Google Gemini – AI for summarization<br>
RSS Feeds / News APIs – News Source<br>
Gmail / SMTP – Email Delivery<br>
<br>
📂 Project Workflow<br>
Fetch News – Use RSS Feed or News API<br>
Summarize – Send articles to Google Gemini for concise summaries<br>
Format Newsletter – Create a clean HTML email<br>
Send Email – Use Gmail/SMTP node in n8n<br>
<br>
⚙️ Setup Instructions<br>
1. Install n8n<br>
    n8n Installation Guide<br>
2. Create Credentials<br>
    Google Gemini API Key<br>
    Gmail or SMTP for email sending<br>
3. Import Workflow<br>
    Download and import the provided workflow.json file into n8n<br>
4. Configure Nodes<br>
    Add your RSS Feed URLs<br>
    Add Gemini API Key in HTTP Request node<br>
    Set email recipient details<br>
5. Activate the Workflow<br>
    Schedule it to run daily<br>

📸 Workflow Diagram
<img width="1915" height="997" alt="Screenshot Project" src="https://github.com/user-attachments/assets/32e0e7a8-8bff-4374-af1e-fd3d98c33ef0" />
