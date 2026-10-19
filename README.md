Automated B2B Lead-Audit Pipeline

An automated, local-first workflow built with n8n, Gemini AI, and Airtable designed to eliminate manual pre-call research for boutique web agencies.

📺 Live Proof of Work
[Watch the 15-Second Live Execution Demo]

https://drive.google.com/file/d/1WvCBkE7_JfcSl8S151Nk9LnS4JjQg8Jl/view?usp=drive_link

---

🏗️ Architecture & Flow

HTTP Request Node: Scrapes target agency or prospect web assets.
HTML Clean-Up Node: Strips unnecessary scripts, styles, and layout noise.
JavaScript Normalization Node: Sanitizes text payload for LLM processing.
Gemini AI Node: Analyzes digital footprint and identifies specific operational bottlenecks & value pitches.
Airtable Node: Instantly populates a structured executive dashboard with actionable client insights.

---

🚀 Key Features

Zero Manual Prep: Automatically audits inbound prospects before discovery calls.
Structured Output: Splits operational bottlenecks and value pitches cleanly into distinct fields.
Executive Logging: Pre-formats data in Airtable for immediate sales team review.

---

🛠️ Setup & Deployment

Import My workflow.json into your n8n instance.
Connect your Google Gemini API credentials to the model node.
Link your Airtable Personal Access Token and set table field mappings.
Trigger manually or wire to an inbound HTTP webhook.

Thanks for visiting us . Please Support us. 😄
