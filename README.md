# 🤖🇦🇮👾 AI-Powered Lead Scoring & Routing Pipeline

A high-performance, custom-coded backend automation engine built to instantly evaluate, score, and route e-commerce or B2B leads. This system bridges the gap between frontend web forms and backend sales operations using conditional logic, custom scripting, and real-time APIs.

## 🧠 Core Features & Logic
Unlike basic "trigger-action" automations, this pipeline utilizes **Custom JavaScript & Python-ready architecture** to perform complex data manipulation on the fly:
* **Custom JS Lead Scoring Engine:** Reads incoming JSON payloads and applies mathematical scoring algorithms based on the prospect's budget and keyword intent (e.g., "commercial", "ASAP").
* **VIP Classification:** Automatically segregates leads into "VIP" or "Standard" tiers dynamically using `If/Else` boolean logic.
* **Zero-Delay Routing:** Pings internal sales teams instantly via the **Slack API** with heavily formatted, actionable data.
* **Automated Client Onboarding:** Injects personalized data into a custom HTML/CSS email template and executes immediate delivery via SMTP.

## 🛠️ Tech Stack
* **Core Automation:** n8n (Node-based Workflow Engine)
* **Custom Scripting:** JavaScript (ES6+), Python (Adaptable for predictive ML routing)
* **Data Handling:** RESTful APIs, Webhooks, JSON Parsing, Data Sanitization
* **Integrations:** Slack API, SMTP/Email Services, Frontend Forms (WordPress/Shopify)

## 🏗️ System Architecture
1. **Webhook Ingestion:** Listens continuously for `POST` requests from the live frontend.
2. **Data Parser (JS Code Node):** Extracts array objects, calculates the `lead_score`, and flags `is_vip_lead = true/false`.
3. **Router:** Directs VIP leads to the Slack channel and sends a customized, brand-aligned HTML welcome email to the prospect simultaneously.

## 💼 Business Value (ROI)
* **Drops response time to absolute zero**, preventing high-ticket lead leakage.
* Eliminates manual inbox filtering for the sales team.
* Delivers a highly professional, instant brand experience to the customer while the team prepares the pitch.

---
*Created for robust, scalable backend operations. Feel free to import the `.json` file into your n8n instance to test the logic.*
