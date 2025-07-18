[![Header](https://github.com/Tuhin-SnapD/Tuhin-SnapD/blob/main/header.jpg? "Header")](https://github.com/Tuhin-SnapD/Tuhin-SnapD/blob/main/header_picture.jpg)

<p align='center'>  
      <img alt="c++" height="30px" src="https://api.iconify.design/logos:c.svg" />
      <img alt="pyhton" height="30px" src="https://api.iconify.design/logos:python.svg" />
      <img alt="java" height="30px" src="https://api.iconify.design/logos:java.svg" />
      <img alt="javascript" height="30px" src="https://api.iconify.design/logos:javascript.svg" />
      <img alt="react" height="30px" src="https://api.iconify.design/logos:react.svg" />
      <img alt="node" height="30px" src="https://api.iconify.design/logos:nodejs.svg" />
      <img alt="django" height="30px" src="https://api.iconify.design/logos:django.svg" />


  

 
# 👋 Hey there, I’m Tuhin “TC” Chakrabarty!

> **Full-Stack Software Engineer**  
> Passionate about solving real-world problems with clean architecture & automation—especially in the financial world!

---

## 🚀 Quick Facts

- 🎓 **Education:** B.Tech in CSE, VIT Vellore (2019–2023)  
- 💼 **Current Role:** Software Engineer @ Bank of America (2022–Present)  
- 💡 **Superpowers:**  
  - Building mission-critical trading & automation systems  
  - Designing clean, scalable architectures  
  - Bridging gaps between complex tech and user needs

---

## 🛠 What I Work With


<summary><strong>Languages & Frameworks</strong></summary>

| 💻 Languages      | ⚙️ Frameworks            | ☁️ Cloud & Tools       |
|-------------------|--------------------------|------------------------|
| Python 🐍         | Django & Flask           | AWS                    |
| C++ ⚙️            | React & TypeScript       | Docker & Kubernetes    |
| Java & JavaScript | Tornado & Node.js        | Jenkins & Ansible      |
| SQL & NoSQL       | Rasa (NLP)               | Git                    |


<summary><strong>Concepts & Practices</strong></summary>

- System Design & Clean Architecture  
- OOP & Design Patterns  
- DevOps & CI/CD  
- Agile & TDD  
- Real-time Monitoring & Alerting  


---

## 🏆 Key Achievements

- 🚀 **Apex/Martini Trading Platform**  
  Contributed high-frequency transaction workflows for Fonance Systems.  
- 🤖 **Chatbot Integration**  
  Slashed license costs by 25% with Rasa-powered assistants.  
- ⚙️ **Automation Interfaces**  
  Boosted operational efficiency by 40% via custom tooling.  
- 🔒 **Security Compliance**  
  Helped remediate vulnerabilities in real-time systems.  


---

## 📫 Let’s Chat!

- 📧 **Email:** [tuhinchakrabarty14@gmail.com](mailto:tuhinchakrabarty14@gmail.com)  
- 🔗 **LinkedIn:** [linkedin.com](https://www.linkedin.com/in/tuhin-chakrabarty-1074aa19b/)
- 💼 **Download My CV:** [PDF Version →](https://drive.google.com/file/d/1PcatIk7bcTgXGHV5365H819ApdzaDJ1n/view?usp=sharing)  

Or drop a 💌 below!

---

*“Code is like humor. When you have to explain it, it’s bad.”* — Cory House

© 2025 Tuhin Chakrabarty. All rights reserved.  




---

✅ 1. Flowchart Maker using Mermaid

🛠️ Problem:

Large codebases lack visual documentation. New engineers and even senior developers struggle to understand module interactions, especially in legacy systems.

💡 Solution:

Automatically parse code (functions, classes, service boundaries, API calls) to generate Mermaid diagrams:

flowchart

sequenceDiagram

classDiagram


GitHub Copilot assists in generating the diagram syntax intelligently.

🎯 Benefits:

Faster onboarding for new developers

Better design reviews and audits

Continuous documentation (evolves with code)



---

📊 2. Auto-Generated Risk Dashboards from Code

🛠️ Problem:

Risk exposure embedded in code logic is invisible to stakeholders unless manually flagged or reviewed. No centralized view exists across services.

💡 Solution:

Analyze code for:

Thresholds (position limits, timeouts)

Exception flows

“Hardcoded risk” logic

Logging & alerts


Aggregate these into dashboards: service-wise, module-wise, risk-surface area.

🎯 Benefits:

Real-time visibility into risk controls

Better control self-assessments (CSAs)

Accelerates risk audit readiness



---

🧠 3. Codememory Agent

> “What happened to this file over time?”



🛠️ Problem:

Understanding the evolution of a code file/function is tedious:

You must read through commits, JIRA tickets, and context-switch constantly.


💡 Solution:

A Codememory Agent that:

Parses Git commit history + diffs + issue links

Builds a chronological narrative:

“Refactored to support XYZ”

“Deprecated ABC logic in Mar 2023”

“Changed due to PROD outage in Sprint 18”



🎯 Benefits:

Boosts institutional memory

Helps reviewers and new joiners understand the "why", not just the "what"

Surfaces hidden tech debt



---

📜 4. Acceptance Criteria Generator

🛠️ Problem:

JIRA stories often lack clear, testable acceptance criteria, leading to misalignment between devs, QA, and PMs.

💡 Solution:

Copilot-powered tool that:

Takes in JIRA title + description

Outputs 3–5 bullet point ACs

Optional: Gherkin .feature file or JSON schema


🎯 Benefits:

Faster story grooming

Increased testability & alignment

Reduces back-and-forth during QA/UAT



---

⏱️ 5. JIRA Sprint Listener / Sprint Police

🛠️ Problem:

Sprint hygiene often breaks:

Stories stagnate

No movement between stages

Missed commitments


💡 Solution:

A bot that:

Monitors JIRA board in real-time

Sends alerts (Slack/Email) if:

Ticket hasn’t moved in X days

QA is idle

Definition of Done isn’t met



🎯 Benefits:

Keeps sprints on track

Managers get real-time signals

Encourages agile discipline without micromanagement



---

🔍 6. Trade Surveillance Log Interpreter

🛠️ Problem:

Trading system logs (e.g., FIX, proprietary logs) are cryptic. Parsing them for investigations or root cause analysis is manual, error-prone, and slow.

💡 Solution:

A log parser that:

Converts logs into a human-readable narrative

Highlights anomalies (e.g., late orders, broken chains, risk override)

Visualizes flow using sequenceDiagram in Mermaid


🎯 Benefits:

Fast RCA (root cause analysis)

Useful for compliance & investigations

Improves transparency of black-box systems



---

🧪 7. Bitbucket Unit Test Case Generator

🛠️ Problem:

Test coverage is often inconsistent or missing. Developers struggle to write high-quality, parameterized, edge-covering unit tests from scratch.

💡 Solution:

Bitbucket-integrated Copilot agent that:

Generates unit tests for changed files in a PR

Uses function signature + context + past tests

Supports frameworks like Pytest, JUnit, etc.


🎯 Benefits:

Better test coverage with minimal effort

Encourages TDD/BDD

Reduces code-to-prod bugs and improves confidence



