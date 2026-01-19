# Invoice Approval Automation using UiPath Studio Web & Automation Cloud

## Overview
This project demonstrates an end-to-end **invoice approval automation** built using **UiPath Studio Web and Automation Cloud**.  
The automation monitors a Google Drive folder for new invoice PDF files, extracts key invoice data using **Document Understanding**, evaluates the data using an **AI Decision Agent**, and routes invoices through automated or human approval workflows.

This project highlights the core concepts of **agentic automation**, combining AI, RPA, cloud triggers, and human-in-the-loop decision making.

---

## Features
- Automatically watches a Google Drive folder for new PDF invoices  
- Downloads invoice files for processing  
- Extracts invoice details using Document Understanding  
- Uses an AI Decision Agent to determine approval status  
- Automatically approves invoices that meet predefined criteria  
- Routes invoices for human review using Action App tasks when required  
- Moves invoices to Approved or Rejected folders based on final decision  
- Publishes and monitors workflows in UiPath Orchestrator  

---

## Automation Flow
1. Google Drive trigger detects a new invoice PDF  
2. Invoice file is downloaded  
3. Document Understanding extracts key fields:
   - Invoice Vendor Name  
   - Invoice Number  
   - Invoice Date  
   - Invoice Amount  
4. Extracted data is sent to an AI Decision Agent  
5. Decision gateway routes the workflow:
   - Auto-approve invoices that meet criteria  
   - Send invoices for human review if required  
6. Final decision moves invoice to Approved or Rejected folder  

---

## Technologies Used
- UiPath Studio Web  
- UiPath Automation Cloud  
- UiPath Orchestrator  
- Document Understanding  
- AI Decision Agent  
- Google Drive Connector  
- Action Apps  
- RPA Workflows  

---

## Project Structure
Solution
├── Agent
├── Agentic Process
├── RPA Workflow
├── SimpleApprovalApp
└── resources


---

## How to Run
1. Open the project in UiPath Studio Web or UiPath Studio Desktop  
2. Configure Google Drive connection  
3. Define approval rules in the AI Decision Agent  
4. Publish the automation to UiPath Orchestrator  
5. Upload an invoice PDF to the monitored Google Drive folder  
6. Monitor execution and results in Orchestrator  

---

## Learning Outcomes
- Building cloud-based triggers and workflows  
- Implementing Document Understanding pipelines  
- Applying AI-driven decision making  
- Designing agentic automation architectures  
- Integrating human-in-the-loop approval steps  
- Publishing and monitoring automations in Orchestrator  

---

## Author
Sri Santhoshi
