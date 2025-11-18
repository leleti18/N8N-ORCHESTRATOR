# n8n QA Orchestrator — Automated Test Execution Pipeline  
Created by **Leticia Santos**

This repository contains an **n8n workflow** that orchestrates automated Cypress executions **on-demand**, using webhooks, shell commands, and optional notifications.  
It demonstrates how QA Automation can integrate orchestration tools to create dynamic, scalable, CI-ready testing pipelines.

This is one of the strongest differentiators in my QA portfolio — since orchestrators like n8n, Airflow or Temporal are increasingly used in modern engineering teams.

---

## 🚀 What This Workflow Does

### When triggered via **webhook**, it:

1. **Clones a Cypress repository**  
2. **Installs dependencies (npm ci)**  
3. **Executes the Cypress test suite**  
4. **Packages artifacts** (videos, screenshots)  
5. **Sends notifications** (Slack/webhook/HTTP endpoint)  
6. **Returns JSON response** with execution metadata  

This simulates a real QA automation pipeline that can be executed:

- on-demand  
- scheduled  
- per environment  
- integrated with CI/CD  
- triggered by external systems  

---

## 📁 Project Structure

