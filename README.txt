FRIGATE TECHNICAL CAPABILITY DASHBOARD — MULTI-PAGE VERSION

FILES
- index.html: Overview
- skills.html: Skills & competency
- qualifications.html: Experience & certifications
- projects.html: Project experience
- directory.html: Employee profiles
- explorer.html: Skills data explorer
- styles.css: Shared styling
- app.js: Workbook processing, charts, tables and profile interactions

INSTALL ON GITHUB PAGES
1. Download and extract this ZIP.
2. Open the extracted folder. The six HTML files, styles.css and app.js should be together at the top level.
3. In your GitHub repository, upload these files to the repository ROOT (not inside another folder).
4. Replace the existing index.html, app.js and styles.css when GitHub asks.
5. Commit the changes and wait for GitHub Pages to publish.

USING THE DASHBOARD
- Open the website and upload the original survey workbook once.
- The workbook is stored in that browser's localStorage so it can be restored while moving between the dashboard pages in the same browser.
- The workbook is processed locally in the browser; it is not uploaded to GitHub or sent to a server.
- If browser storage is cleared, or you use a different browser/device, upload the workbook again.
- Internet access is required for the SheetJS and Chart.js libraries loaded from their CDNs.

PRIVACY
The dashboard continues to omit contact addresses, phone numbers, email addresses and other excluded contact details from the displayed/exported profile data. Do not commit the Excel workbook to the public GitHub repository.
