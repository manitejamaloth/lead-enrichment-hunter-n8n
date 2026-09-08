# Lead Enrichment Workflow (Hunter.io Integration)

An n8n automation that enriches new leads in real time using the Hunter.io API, automatically delivering verified contact and company data without manual research.

## 🎯 Problem

Sales teams spend significant time manually researching and verifying contact details for new leads before outreach — slowing down the sales pipeline.

## ⚙️ How It Works

1. **Trigger**: New lead data enters the workflow (e.g., from a form, spreadsheet, or CRM).
2. **Enrichment**: The workflow calls the Hunter.io API to verify and enrich the lead's contact and company information.
3. **Data Delivery**: Enriched data (verified email, company details) is automatically saved back into the sales pipeline (e.g., CRM or Google Sheets).

## 🛠️ Tools Used

- **n8n** — workflow orchestration
- **Hunter.io API** — email verification and lead enrichment
- **Google Sheets / CRM integration** — data storage

## 📸 Workflow Screenshot

*(Add screenshot of your n8n canvas here)*

## 📄 Workflow Export

Full workflow JSON available in this repo — see `workflow.json`.

## 💡 Impact

Removes manual research from the sales process by delivering verified lead data automatically and in real time, speeding up outreach readiness.
