# Anfrage Luftbildauswertung – Prototyp

Demo of an automated customer inquiry for aerial image analysis (Kampfmittelvorerkundung), built with n8n.

- `index.html` – customer form: contact details, service, location on a map (point + radius or drawn area), project details. Returns a price range, project number, processing time and call slots.
- `dashboard.html` – company view of all inquiries (totals, map, table).
- `n8n-workflow.json` – n8n workflow: webhook → calculate offer → save to Google Sheets → answer the page; second chain feeds the dashboard.
- `sheet-kopfzeile.csv` – header row for the Google Sheet.

Prices and call slots are example values. Not a real offer and not affiliated with any company. Test data only.
