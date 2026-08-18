# NEPSE News Intelligence

An n8n-powered AI automation that collects recent Nepal Stock Exchange (NEPSE) company news, analyzes it with Google Gemini, and delivers a structured financial-news intelligence report by email.

##  Features

- Company-specific NEPSE news search
- Google News RSS ingestion
- Duplicate article removal
- AI-powered news classification
- Direct company, sector, and broader market analysis
- Relevance scoring: High / Medium / Low
- Source attribution
- Structured JSON output
- Automatically generated HTML email report
- Gmail delivery

##  Workflow

Form Submission
→ Google News RSS
→ Deduplication
→ Article Normalization
→ News Aggregation
→ Gemini AI Analysis
→ Structured Output
→ HTML Email Generation
→ Gmail

##  Tech Stack

- n8n
- Google Gemini
- Google News RSS
- Gmail
- JavaScript
- HTML/CSS

##  Setup

1. Install n8n.
2. Import the workflow JSON from `workflow/`.
3. Configure the required n8n credentials:
   - Google Gemini
   - Gmail
4. Activate the workflow.
5. Submit a company and email through the form.

##  Security

Credentials are not included in this repository.

Configure API keys and OAuth credentials directly through n8n's credential manager.

Never commit `.env` files, API keys, OAuth secrets, access tokens, or private credentials.

##  Disclaimer

This project provides automated news aggregation and analysis for informational purposes only. It does not provide financial advice, investment recommendations, or buy/sell/hold signals.


   <img width="1107" height="517" alt="NEPSE_newsletter wokflow" src="https://github.com/user-attachments/assets/ab97303b-f804-4b93-9b26-d4c34feb3cf3" />
