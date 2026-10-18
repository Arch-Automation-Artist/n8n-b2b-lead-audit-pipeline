# Automated B2B Lead-Audit Pipeline

An automated, local-first workflow built with **n8n**, **Gemini AI**, and **Airtable** designed to eliminate manual pre-call research for boutique web agencies.

---

## 🏗️ Architecture & Flow
1. **HTTP Request Node:** Scrapes target agency or prospect web assets.
2. **HTML Clean-Up Node:** Strips unnecessary scripts, styles, and layout noise.
3. **JavaScript Normalization Node:** Sanitizes text payload for LLM processing.
4. **Gemini AI Node:** Analyzes digital footprint and identifies specific operational bottlenecks & value pitches.
5. **Airtable Node:** Instantly populates a structured executive dashboard with actionable client insights.

---

## 🚀 Key Features
* **Zero Manual Prep:** Automatically audits inbound prospects before discovery calls.
* **Structured Output:** Splits operational bottlenecks and value pitches cleanly into distinct fields.
* **Executive Logging:** Pre-formats data in Airtable for immediate sales team review.

---

## 🛠️ Setup & Deployment
1. Import `My workflow.json` into your n8n instance.
2. Connect your **Google Gemini API** credentials to the model node.
3. Link your **Airtable Personal Access Token** and set table field mappings.
4. Trigger manually or wire to an inbound HTTP webhook.
