 Student Performance Monitor (n8n Workflow)
 
Automated system to monitor student performance, attendance, and assignment scores — with real-time alerts to teachers and parents using n8n.

What It Does?

✅ Tracks student attendance via Google Forms

📝 Records assignment scores in Google Sheets

🚨 Automatically alerts teachers/parents of low-performing students via Twilio (WhatsApp/SMS) or Slack

Tools Used

n8n – Workflow automation

Google Sheets – Stores performance data

Google Forms – Captures attendance

Twilio – Sends WhatsApp/SMS alerts

Slack – Optional alert channel for teachers

Workflow Steps

Trigger: New form submission or data update

Condition: Checks for missing attendance or low scores

Action: Sends alert message via WhatsApp or Slack

Log/Update: Stores alert status in Google Sheet
