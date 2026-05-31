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

## 📸 System Previews

**1. The Automation Canvas (n8n)**
![n8n Workflow](https://github.com/user-attachments/assets/078714b2-dadf-4fe3-92cb-0600720dc639)

**2. Real-Time VIP Sales Alert (Slack)**
![Slack Alert](https://github.com/user-attachments/assets/2caa777e-0f50-4460-b5e1-b9be49671402)

**3. Automated Custom HTML Email**
![Welcome Email](https://github.com/user-attachments/assets/057ecea8-c42c-4543-9f09-42e3ed98cefe)

**4. Internal Team Routing (Email Alert)**
Beyond Slack, the system simultaneously dispatches a structured internal email to the sales and operations team. This ensures that even if a team member is away from Slack, the high-priority VIP lead data (Name, Budget, Lead Score, and Customer Message) is securely waiting in their inbox for immediate action.
![Internal Team Email](https://github.com/user-attachments/assets/5a983a02-afa4-477e-811d-0038ab1991ec)

**5. Custom Scripting (JavaScript & Python Integration)**
Relying solely on native drag-and-drop automation nodes limits scalability. This pipeline is engineered with custom code blocks to handle complex data parsing and advanced logic:

* **JavaScript (Node.js):** Executes the primary array iterations, sanitizes incoming JSON payloads, and calculates the exact `lead_score` dynamically using custom mathematical logic based on financial parameters and keyword intent.
* **Python (AI-Ready Architecture):** The system architecture is designed to seamlessly integrate Python scripts for future AI/Machine Learning expansions - such as running Natural Language Processing (NLP) on the user's message to predict customer sentiment before the sales team even reads the inquiry.

**5. Custom Scripting (JavaScript & Python Integration)**
Relying solely on native drag-and-drop automation nodes limits scalability. This pipeline is engineered with custom code blocks to handle complex data parsing and advanced logic:

* **JavaScript (Node.js):** Executes the primary array iterations, sanitizes incoming JSON payloads, and calculates the exact `lead_score` dynamically using custom mathematical logic based on financial parameters and keyword intent.
![Custom JavaScript Logic](https://github.com/user-attachments/assets/<img width="1899" height="860" alt="PROJ2JS" src="https://github.com/user-attachments/assets/0ab0a600-b104-433b-a184-804f050b07da" />)

* **Python (AI-Ready Architecture):** The system architecture is designed to seamlessly integrate Python scripts for future AI/Machine Learning expansions—such as running Natural Language Processing (NLP) on the user's message to predict customer sentiment before the sales team even reads the inquiry.
![Custom Python Logic](https://github.com/user-attachments/assets/<img width="1889" height="847" alt="proj2Python" src="https://github.com/user-attachments/assets/e5b04516-9571-4414-ac2c-bb64b3f9f113" />)
