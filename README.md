# SmartCert Multi-page UI Prototype

A responsive, multi-view SmartCert frontend built with plain HTML, CSS, and JavaScript.

## Run locally
1. Extract the ZIP.
2. Open a terminal in the extracted folder.
3. Run:
   ```bash
   npx --yes serve . -l 5501
   ```
4. Open http://localhost:5501

Internet is required for jsPDF, QRCode, and Google Fonts CDN resources.

## Views
- Dashboard: stats, recent activity, quick actions, recent batches
- Generate Certificates: CSV upload, preview, settings, PDF export, QR codes
- Participants: search, add/edit/delete, validation, CSV import/export sample
- Templates: select between four certificate themes
- Batch History: local export metadata and search
- Settings: organization, certificate defaults, preferences, local data backup/reset

## Important limitations
This is a frontend prototype. Data is stored in browser localStorage. There is no backend, authentication, cloud synchronization, email delivery, or public certificate verification endpoint. QR codes contain certificate IDs only. Generated PDFs are downloaded to the user's device.
