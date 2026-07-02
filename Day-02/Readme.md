\# 🚀 Day 2: 90 Days of DevOps Challenge



\## 📌 Overview

Transitioned from executing isolated CLI commands to scripting end-to-end automation pipelines and auditing system security boundaries. Today's labs focused on \*\*Linux Architecture, Core Automation, Networking Foundations\*\*, and implementing critical safeguard barriers to manage data destruction edge cases in production.



\---



\## 🛠️ Technical Accomplishments \& Deep Dives



\### 1️⃣ Security \& Privilege Escalation: OverTheWire (Bandit Labs)

Successfully audited and compromised \*\*6 consecutive levels\*\* of the gamified Bandit security infrastructure.

\* \*\*Privilege Drift \& Controls:\*\* Leveraged `setuid` binary vulnerabilities and analyzed privilege escalation vectors to extract protected tokens.

\* \*\*Git Tracking Exploration:\*\* Interrogated local target environments by tracking internal Git `HEAD` pointers and decoding obscured password stores.



\### 2️⃣ Operational Safeguards: Overwrite Mitigation via `noclobber`

Encountered and mitigated a classic infrastructure hazard—accidentally overwriting a critical configurations payload using the stdout redirection operator (`>`).

\* \*\*The Solution:\*\* Engineered a systemic failure-prevention rail inside the shell environment runtime by invoking:

&#x20; ```bash

&#x20; set -o noclobber

&#x20; ```

\* \*\*Impact:\*\* Configured the Zsh/Bash subsystem to actively reject structural file overrides, abstracting human error risks by raising a deterministic `"file exists"` exception.



\### 3️⃣ Systems Automation: Cron Scheduling \& Fail-Safe Architectures

Developed a resilient backup engine to handle local system states and abstract routine human execution dependencies.



\* \*\*Bash Script Deployment:\*\* Engineered a shell utility designed to generate dynamic file archives utilizing explicit system timestamps. Enforced strict execution vectors using explicit access modification:

&#x20; ```bash

&#x20; chmod +x backup\_script.sh

&#x20; ./backup\_script.sh

&#x20; ```

\* \*\*Cron Orchestration:\*\* Wired the runtime execution into the native Linux scheduler engine (`crontab`). Configured a production-style nightly backup cycle matching the standard midnight cron execution string:

&#x20; ```cron

&#x20; 0 0 \* \* \* /path/to/backup\_script.sh

&#x20; ```



\---



\## 🧠 Real-World Architectural Thinking: Downtime Engineering

Investigated a critical production edge case: \*"What happens if a node undergoes abrupt power failure or downtime precisely at the scheduled midnight backup window?"\*



\* \*\*`anacron` Integration:\*\* Explored the mechanics of `anacron` to guarantee asynchronous job execution, ensuring missed tasks fire immediately upon target node reboot.

\* \*\*Cloud Infrastructure Paradigm:\*\* Evaluated why modern mission-critical enterprise microservices reject local host execution dependencies in favor of 24/7 highly available Cloud Compute nodes hosted on providers like \*\*AWS\*\* or \*\*DigitalOcean\*\*.



\---



\## 💡 Executive Key Takeaway

> \*"Tutorials show you the map, but breaking files in live environments, crushing security labs, and scripting your way out of trouble builds actual muscle memory."\* 

DevOps isn't about memorizing syntax; it's about engineering resilient systems, setting up failure-safes, and knowing exactly how to script your way through architectural anomalies.



\---



\## 📅 Next Milestones (Day 3)

\* Deep dive into Advanced Text Processing tools (`grep`, `awk`, `sed`) for infrastructure log parsing.

\* Expand Bandit security auditing to master intermediate networking configurations.

\* Explore Git source control branching strategies.



\---

\*Follow my repository as I document technical depth and systems engineering updates throughout this #90DaysOfDevOps journey!\*



