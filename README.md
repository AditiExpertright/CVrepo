# ExpertRight — CV Vendor Tracker

A standalone web app to upload CVs, extract candidate details using AI, track vendors, log interview feedback, and export everything to Google Sheets.

## How to deploy on Vercel

1. Push this repository to GitHub (both files: `index.html` and `vercel.json`)
2. Go to [vercel.com](https://vercel.com) → New Project → Import this GitHub repo
3. Leave all settings as default → click **Deploy**
4. Your app will be live at `https://your-project.vercel.app`

## How to use

1. Open the deployed URL in Chrome
2. Enter your Anthropic API key (get it at [console.anthropic.com](https://console.anthropic.com))
3. Add vendors, upload CVs, extract data, log interviews, export to Google Sheets

## Files

| File | Purpose |
|------|---------|
| `index.html` | The complete app (all-in-one HTML file) |
| `vercel.json` | Vercel deployment configuration |

## Features

- Vendor master list with duplicate detection
- Single and bulk CV upload with per-CV rates
- AI extraction: candidate name, email, phone, skills, experience, tech stack
- Primary and secondary skills separation
- Purchase rate and sale rate per profile
- Remarks / notes per CV
- Interview tracker with round-by-round feedback and history
- Export to Google Sheets via Apps Script
- Download CSV for CV data and interview logs
