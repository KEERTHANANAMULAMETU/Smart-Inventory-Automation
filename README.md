📘 Smart Business Automations using RAG Logic (n8n Workflows)

🚀 Overview

This project includes two automation workflows built in n8n, inspired by the RAG (Retrieval–Augmentation–Generation) concept.
Instead of retrieving text for AI chat like traditional RAG systems, these workflows use the same logic to automate real-world business tasks — handling orders, emails, and Google Sheets in real time.


---

🧩 Workflows Included

🗂️ 1. Task Management Agent (with Google Sheets)

Trigger: New row added to Google Sheets

Goal: Notify the admin whenever a new order or task is added to the sheet.

🔁 Flow (RAG Breakdown)

RAG Phase	Description

Retrieve	Detects a new row added to Google Sheets.
Augment	Formats the sheet data into a clean, structured email summary.
Generate	Sends an automatic email notification to the admin or team.


⚙️ Tech Stack

n8n

Google Sheets API

Gmail API


🧠 Outcome

Automates task tracking — no manual refresh or check needed. The system instantly informs the admin of new updates or entries.


---

📦 2. Automated Order Response System (Email-Based)

Trigger: New order email received via Gmail

Goal: Instantly reply to customers with a personalized thank-you email after an order is received.

🔁 Flow (RAG Breakdown)

RAG Phase	Description

Retrieve	Extracts structured order details (Customer Name, Product, Quantity, Price) from incoming email text using regex.
Augment	Inserts these details into a personalized thank-you message template.
Generate	Automatically sends the email back to the customer through Gmail.


⚙️ Tech Stack

n8n

JavaScript (for extraction and templating)

Gmail API


🧠 Outcome

Acts as a 24/7 customer engagement bot — auto-responding to customers, improving experience, and saving response time.


---

⚡ RAG Concept in Business Automation

These two workflows together demonstrate how RAG thinking can be applied beyond LLMs:

Concept	AI RAG	Workflow RAG

Retrieve	Fetch context from a knowledge base	Fetch data from email or sheet
Augment	Add context to prompt	Format or personalize the data
Generate	Produce a response	Generate an action (email/notification)


This makes business operations context-aware, data-driven, and self-operating — just like an AI assistant for enterprise tasks.

<img width="1894" height="734" alt="Screenshot 2025-10-05 195147" src="https://github.com/user-attachments/assets/25585abc-9b33-427e-b513-59c48dd8adb5" />

<img width="1919" height="716" alt="Screenshot 2025-10-05 195207" src="https://github.com/user-attachments/assets/2ffc95dd-e079-4dde-8a37-def418c76b39" />



