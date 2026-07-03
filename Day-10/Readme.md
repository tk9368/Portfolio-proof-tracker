\# 🚀 Day 10: 90 Days of DevOps Challenge



\## 📌 Overview

Today marked a significant shift from just running commands to understanding core system architecture. Deep dived into the underlying mechanics of \*\*Docker and Containerization Ecosystems\*\*, while simultaneously developing two production-grade \*\*Shell Scripting Automation Utilities\*\* for backup and log analysis.



\---



\## 🛠️ Technical Accomplishments \& Deep Dives



\### 1️⃣ Core Infrastructure: Demystifying Docker Architecture 🐳

Shifted from the buzzwords to understanding the architectural blueprint of Docker.

\* \*\*Concept vs Tool:\*\* Established that \*Containerization\* is the architectural paradigm, while \*Docker\* is the runtime platform that implements it.

\* \*\*The "Works on My Machine" Resolution:\*\* Understood how Docker solves environment drift by packaging code, runtime, system tools, and libraries into an immutable container.

\* \*\*Architectural Components Unpacked:\*\*

&#x20; \* \*\*Docker Host:\*\* The physical or virtual machine running the Docker environment.

&#x20; \* \*\*Docker Daemon (`dockerd`):\*\* The background service managing core objects like containers, images, networks, and storage volumes.

&#x20; \* \*\*Docker Registries (e.g., Docker Hub):\*\* The centralized repositories used to store, version, and distribute container images.



> 💡 \\\*Special acknowledgment to Abhishek Veeramalla's content for making the architectural deep dive seamless and highly intuitive.\\\*



\### 2️⃣ Advanced Linux \& Shell Scripting Challenges 💻

Successfully engineered two automation scripts designed for real-world DevOps workflows:



\#### 📂 Challenge 1: Directory Backup with Rotation Strategy

\* Built a robust backup script that automates directory archiving while implementing a retention/rotation policy to prevent disk space exhaustion.



\#### 📊 Challenge 2: Enterprise Log Analyzer \& Report Generator

\* Developed a log parsing script that processes raw system logs and outputs a structured analytical report featuring:

&#x20; \* Timestamp of Analysis \& Source File Target

&#x20; \* Quantitative Metrics (Total lines processed \& total error counts)

&#x20; \* Statistical Analytics (Top 5 recurring errors with frequency counts)

&#x20; \* Security/System Audit (Critical events mapped with precise line numbers)



\#### 🧠 Linux Discovery of the Day: `cat << EOF`

\* Discovered that `cat` isn't just for reading files. Mastered the usage of \*\*Heredocs (`<<EOF`)\*\* to programmatically generate and write multiline configuration data into files inside automated bash scripts.



\---



\### 3️⃣ Security \& System Exploitation: OverTheWire (Bandit Level 21)

\* \*\*Status:\*\* Attempted Level 21. Faced complexities with the automated crontab permissions/logic. Rolling this over to Day 11's priority debugging queue.



\---



\## 💡 Executive Key Takeaway

> \\\*"In DevOps, understanding the architecture behind a tool is far more valuable than just memorizing its commands."\\\* 

Syntax can be looked up in seconds; architectural understanding is what allows you to troubleshoot production outages and scale infrastructure efficiently.



\---



\## 📅 Next Milestones (Day 11)

\* Crack the automated cronjob exploitation in Bandit Level 21.

\* Move from Docker theoretical architecture to writing Dockerfiles and optimizing image layers.

\* Resolve the pending Jenkins setup roadblock from Day 9.



\---

\*Connect with me as I engineer my way through the #90DaysOfDevOps challenge!\*

