An automated scheduling and reporting pipeline that aggregates progress metrics from Google Sheets, processes data using Python logic, and sends periodic HTML performance summary emails.

### Business Problem

Manually tracking daily performance and preparing reports requires employees or managers to repeatedly collect, calculate, and review data.

This can lead to:

* Time spent preparing recurring reports.
* Limited visibility into daily performance.
* Delayed identification of performance issues.
* Dependence on manually prepared reports.
* Difficulty tracking performance trends over time.

### Solution

An automated n8n tracking and reporting workflow collects performance data from Google Sheets, calculates key metrics, and automatically sends a structured performance summary by email.

### Business Outcome

* Reduce time spent preparing daily reports.
* Provide regular performance summaries.
* Improve visibility into operational performance.
* Identify performance issues earlier.
* Support data-driven management decisions.
* Turn raw operational data into actionable reports automatically.

##  Workflow Architecture
![Daily Routine](Daily%20Routine_n8n.png)

![Daily Routine Report send to Gmail](./Daily%20Routine%20Report%20send%20to%20Gmail.png)

##  Tech Stack & Tools
* **n8n**
* **Google Sheets API**


---
