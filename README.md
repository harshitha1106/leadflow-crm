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

##output:
<img width="322" height="446" alt="image" src="https://github.com/user-attachments/assets/9ef00411-b7ba-49d7-93dd-e4117d9e6cf5" />
<img width="1044" height="312" alt="image" src="https://github.com/user-attachments/assets/0246f028-c99c-456d-b72c-2e2080ffc31f" />
<img width="1751" height="700" alt="image" src="https://github.com/user-attachments/assets/a5f3e5b4-91d4-4024-a580-cb4f63f357a4" />


## What I learned

Setting up OAuth for Google APIs, connecting multiple services in one workflow, and building conditional logic for lead scoring.
