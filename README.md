Project 3: Multi-Modal Visual Invoice Agent

Description: A vision-integrated agent that automates the extraction of financial data from physical or digital invoices.

🟢 Key Features:

OCR & Data Extraction: Uses Claude Vision to identify vendors, dates, tax amounts, and line items.

Automatic Mapping: Directly pushes extracted data into Google Sheets or Airtable for accounting.

Human-in-the-loop: Triggers a Slack notification for manual review if confidence scores are low.

Tech Stack: n8n, Claude 3 (Vision), Google Sheets API, Slack API.

Business Impact: Eliminates 100% of manual data entry for accounts payable departments.

🔺 Installation Guide:
▫ Import the provided JSON in n8n.
▫ Setup your API keys (Claude/Pinecone).
▫ Activate the workflow.
