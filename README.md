# AI Lead Intake and Email Draft Automation

A personal demo workflow built with n8n. It collects project inquiries through a form, checks the submitted budget, and uses an AI model to draft a tailored reply for qualifying inquiries. The reply is saved in Gmail Drafts for review; the workflow does not send it automatically.

## How it works

1. A person submits the project inquiry form.
2. The workflow checks the budget against a threshold set in the workflow.
3. If the inquiry qualifies, the AI model prepares a reply using the submitted project details.
4. n8n saves the reply as a Gmail draft for a person to review and edit.

## Tools used

- n8n
- Docker Desktop
- DeepSeek API
- Gmail API and Google OAuth

## Run it

1. Install Docker Desktop and run n8n locally.
2. Import the workflow JSON file from this repository into n8n.
3. Add your own DeepSeek and Gmail credentials in n8n.
4. Review the form and budget condition, then test with sample information.

You need your own API access and credentials. AI API usage may incur charges. Never add API keys, OAuth client secrets, or real customer information to this repository.

## Project status

This is a locally tested portfolio demo, not a hosted service. The workflow creates a Gmail draft for human review.