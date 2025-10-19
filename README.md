# API Data Enrichment and Email Automation (n8n Workflow)
This n8n workflow automates the process of identifying missing data in an Excel sheet and enriching it using external APIs, followed by AI-based analysis and email notifications.

🚀 Workflow Overview

Trigger – Starts when the workflow is manually executed.

Get Row(s) in Sheet – Reads data from a Google Sheet to find missing values (like Age, Gender, or Nation).

API Requests –

Agify API → Predicts Age based on Name

Genderize API → Predicts Gender based on Name

Nationalize API → Predicts Nationality based on Name

Append or Update Row in Sheet – Updates the Google Sheet with enriched data fetched from APIs.

AI Agent (ChatGPT) – Analyzes the updated data or creates a summary using the OpenAI Chat Model.

Send Message (Gmail) – Sends the analyzed or summarized data via email automatically.

⚙️ Features

Detects and fills missing Age, Gender, and Nation fields automatically.

Uses Agify, Genderize, and Nationalize APIs for enrichment.

Integrated with OpenAI Chat Model for smart AI insights.

Sends result summary directly via Gmail.

📊 Example Output
ID	Name	Age	Gender	Nation
101	Sai Nihar	44	Male	IN
102	Ananya Sharma	45	Female	IN
💡 Use Case

Ideal for automating data cleanup, enrichment, and AI-powered reporting from spreadsheets — all handled seamlessly within n8n.

<img width="1600" height="789" alt="image" src="https://github.com/user-attachments/assets/87819368-1e02-4e60-947d-92eac753e9f9" />
