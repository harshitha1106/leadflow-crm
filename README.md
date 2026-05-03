# LeadFlow CRM

I built this as my first automation project. It's a simple but complete lead management system that runs on its own once set up.

## What it does

When someone fills out the contact form, three things happen automatically:
- Their details get saved to a Google Sheet
- They get scored as a High or Low quality lead based on their email
- They receive a thank you email instantly

No manual work needed at all.

## Why I built it

Most tutorials just show you how to connect a form to a spreadsheet. I wanted to take it further and build something that actually works like a real CRM — with scoring and email automation included.

## Tech I used

- n8n for workflow automation
- Google Sheets to store leads
- Gmail API to send emails
- Plain HTML and JavaScript for the form

## How to run it

1. Install n8n with `npm install -g n8n`
2. Run n8n and go to `http://localhost:5678`
3. Import the workflow JSON from this repo
4. Add your Google credentials
5. Open `form.html` in your browser and test it

## What I learned

Setting up OAuth for Google APIs, connecting multiple services in one workflow, and building conditional logic for lead scoring.
