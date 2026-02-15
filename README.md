# SHA Provider Portal Update - Training Registration Dashboard

A live dashboard that tracks healthcare training registrations for Kenya's Digital Health Transformation Initiative. It pulls data directly from Google Sheets (form responses) and displays real-time analytics.

## Live URL
🔗 [https://trainininglivedata.netlify.app](https://trainininglivedata.netlify.app)

## Features
- **Live data** — Auto-refreshes every 30 seconds with manual refresh button
- **Filters** — Quick date filters, custom date range, facility ownership, and facility name search
- **Charts** — Daily registrations trend, role distribution, county breakdown, facility level, and ownership distribution
- **Data table** — Sortable recent registrations with configurable row limits
- **Export** — One-click Excel export of filtered data
- **Data normalization** — Cleans messy ownership values into 3 standard categories

## Data Source
The dashboard reads from a published Google Sheets CSV:
- Google Form: SHA Provider Portal Update Trainings
- Columns: Timestamp, Email, Name, Facility Name, County, Facility Ownership, Facility Level, Phone Number, Role

## How to Edit
1. Clone this repo
2. Edit `index.html` 
3. Push changes
4. Deploy to Netlify (drag-and-drop the project folder)

## Deployment (Netlify)
1. Go to [Netlify](https://app.netlify.com)
2. Open the **trainininglivedata** project
3. Go to **Deploys** tab
4. Drag and drop this project folder onto the deploy area

Alternatively, connect this GitHub repo to Netlify for automatic deployments on every push.

## Tech Stack
- Vanilla HTML/CSS/JavaScript (single file, no build step)
- [Chart.js](https://www.chartjs.org/) — Charts and visualizations
- [PapaParse](https://www.papaparse.com/) — CSV parsing
- [SheetJS](https://sheetjs.com/) — Excel export
