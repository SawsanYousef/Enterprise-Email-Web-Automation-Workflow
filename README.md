# Enterprise End-to-End Email & Web Process Automation ⚙️📧
**RPA Internship Capstone Project | Awarded: 38.5 / 40**

### Project Overview
This repository features a fully automated, scalable enterprise workflow developed using **Blue Prism**. The system design automates the complete data lifecycle—from communication retrieval to web processing and reporting—by integrating Outlook, Excel, queuing mechanisms, and web browser automation.

### core Workflow Architecture (End-to-End)
1. **Email Integration:** Automatically monitors and retrieves incoming data payloads (Excel attachments) from MS Outlook.
2. **Data Ingestion & Queuing:** Parses the Excel file and securely uploads transaction items into the **Blue Prism Work Queue** for robust, centralized transaction management.
3. **Web Automation:** Launches Google Chrome, logs into the target system, and processes each row sequentially using strict data-entry rules.
4. **Exception Handling & Validation:** Implemented structured system and business exception handling to manage invalid rows, dropouts, or application freezes.
5. **Reporting & Feedback:** Compiles processing results back into a consolidated Excel report and automatically dispatches it to stakeholders via Outlook.

### Technologies & Platforms Used
- **RPA Tool:** Blue Prism (Enterprise Architecture)
- **Languages & Concepts:** Process Studio, Object Studio, Queue Management
- **Integrations:** MS Excel VBO, MS Outlook Email VBO, Browser Automation (Chrome Extension)

### Project Achievements
- **High Evaluation:** Scored **38.5 / 40** by senior enterprise reviewers for structural logic clean design.
- **Robustness:** Achieved 100% stability through dynamic wait stages and transaction retry logic.
