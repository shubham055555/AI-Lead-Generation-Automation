# AI Lead Generation & Outreach Automation

## Overview

This project is an AI-powered lead generation and outreach automation system built using n8n, Ollama, and Google Sheets.

It automatically:

* Fetches leads from Google Sheets
* Scores leads using AI (Ollama)
* Filters high-quality leads
* Sends personalized emails
* Stores data in Airtable and Google Sheets

## Workflow

1. Schedule Trigger
2. Google Sheets (Fetch Leads)
3. Normalize Data
4. AI Scoring (Ollama)
5. Merge Data
6. Parse AI Response
7. IF Condition (Lead Qualification)
8. Airtable (CRM Storage)
9. Email Automation (SMTP)
10. Google Sheets (Backup)

## Tech Stack

* n8n (Automation)
* Ollama (Local AI)
* Google Sheets
* Airtable
* SMTP (Email Automation)

## How to Use

1. Import the JSON workflow into n8n
2. Configure credentials:

   * Google Sheets
   * Airtable
   * SMTP
3. Run the workflow

## Features

* AI lead scoring
* Automated email outreach
* CRM integration
* Fully automated pipeline

## Author

Shubham
