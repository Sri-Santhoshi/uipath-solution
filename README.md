📄 Invoice Approval Automation using UiPath Studio Web & Automation Cloud
📌 Project Overview

This project demonstrates how to build a complete end-to-end invoice approval automation using UiPath Studio Web and Automation Cloud.
The automation monitors a Google Drive folder for new invoice PDFs, extracts key invoice details using Document Understanding, evaluates them with an AI Decision Agent, and routes invoices through automated or human approval workflows.

The project showcases agentic automation by combining AI, RPA, cloud triggers, and human-in-the-loop decision-making.

🚀 Key Features

📂 Monitors a Google Drive folder for new PDF invoices

📥 Automatically downloads new invoice files

📑 Extracts invoice fields using Document Understanding

🤖 Sends extracted data to an AI Decision Agent

✅ Automatically approves invoices that meet defined criteria

👤 Routes invoices for human review using an Action App task when required

📁 Moves invoices to Approved or Rejected folders based on final decision

📊 Publishes, runs, and monitors workflows using UiPath Orchestrator

🧩 Workflow Architecture

Trigger

Google Drive trigger detects new PDF invoices

File Handling

Invoice is downloaded and stored for processing

Document Understanding

Extracts key fields such as:

Invoice Vendor Name

Invoice Number

Invoice Date

Invoice Amount

AI Decision Agent

Evaluates extracted data against predefined business rules

Returns approval or review decision

Decision Gateway

Routes workflow based on AI output

Human-in-the-Loop Review

Action App task assigned for manual review (if required)

Final Routing

Invoice moved to Approved or Rejected folder

🛠️ Technologies Used

UiPath Studio Web

UiPath Automation Cloud

UiPath Orchestrator

Document Understanding

AI Decision Agent

Google Drive Connector

Action Apps

RPA Workflows

📁 Project Structure
Solution
├── Agent
├── Agentic Process
├── RPA Workflow
├── SimpleApprovalApp
└── resources

▶️ How to Run the Automation

Open the project in UiPath Studio Web or Studio Desktop

Configure Google Drive connection

Set invoice approval rules in the AI agent

Publish the automation to UiPath Orchestrator

Upload a PDF invoice to the monitored Google Drive folder

Monitor execution and outcomes in Orchestrator

📈 What You’ll Learn

By completing this project, you will understand:

Cloud-based triggers and connectors

Document Understanding pipelines

AI-powered decision making

Agentic automation patterns

Human-in-the-loop approvals

Publishing and monitoring automations in Orchestrator

📌 Use Cases

Finance invoice processing

Accounts payable automation

Approval workflows with AI validation

Document-driven business processes

👤 Author

Sri Santhoshi
