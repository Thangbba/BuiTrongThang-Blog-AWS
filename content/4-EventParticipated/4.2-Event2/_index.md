---
title: "Event 2"
date: 2026-07-09
weight: 2
chapter: false
pre: " <b> 4.3. </b> "
---


# FCJ Community Day - Knowledge Sharing Session

### Event Objectives

- Understand how to apply Cloud Computing (AWS), Containerization (Docker), and Artificial Intelligence (Machine Learning, GraphRAG) to solve real-world problems such as cybersecurity, game development, and data management.
- Gain practical perspectives on career development paths in the IT industry, progressing from an IT Helpdesk role to Cloud Computing and DevOps.
- Learn methodologies to optimize teamwork efficiency and implement digital tools into technology project development workflows.
- Gain inspiration and motivation to cultivate a hands-on mindset, build personal Labs, and develop portfolios rather than focusing solely on theory or certifications.

### Keynote Speakers

- **Mr. Le Hoang Gia Dai** - Final-year student at HUTECH University, member of AWS G3
- **Mr. Nguyen Quoc Bao** - Guest speaker specialized in Cloud Multiplayer
- **Mr. Viet Phat** - AI Engineering student at Swinburne University of Technology
- **Mr. Bao Huynh** - Junior Cloud Native Developer at Endava Vietnam & Founder of ITea Lab
- **Mr. Truong Huy Phuoc** - Guest speaker specialized in Soft Skills
- **Mr. Tran Trung Vinh** - System Administrator at Central Retail Group

### Key Content

### 1. Speaker Le Hoang Gia Dai – AWS G3 Team (HUTECH University)

**Topic:** *Machine Learning-based Network Intrusion Detection System (NIDS) on AWS (WAF + ML for Cyber Attack Detection)*

Speaker Le Hoang Gia Dai presented an optimized security solution by combining a traditional AWS WAF (which relies on predefined rule-sets and is susceptible to being bypassed by Zero-day attacks or novel anomalies) with an ML-based NIDS.

The core content focused on the data processing workflow utilizing the CSE-CIC-IDS2018 dataset, training machine learning models such as Random Forest, LightGBM, and XGBoost to detect sophisticated attacks (SQLi, XSS, DoS, Botnet, etc.). The architecture was fully deployed on the AWS cloud ecosystem using core services such as VPC, EC2, ALB, S3, Kinesis Data Firehose, Lambda, and Security Hub to enable real-time monitoring and alerting via an intuitive Dashboard.

**Key Takeaways & Value Gained:**
The presentation enhanced my awareness of the critical importance of combining proactive security solutions (ML-based NIDS) alongside traditional firewalls. I learned practical data preparation workflows (handling class imbalance), how to evaluate models via a Confusion Matrix, and the architecture required for automated operations on the AWS Cloud ecosystem.

---

### 2. Speaker Nguyen Quoc Bao – Cloud Multiplayer Specialist

**Topic:** *Multiplayer in the Cloud: Connecting Godot Clients with AWS WebSockets*

Mr. Nguyen Quoc Bao delivered an in-depth analysis of network architectures in multiplayer game development, comparing UDP/ENet, HTTP Polling, and WebSockets. The session highlighted a solution using WebSockets integrated with AWS to build real-time Lobby systems, Chat, and Matchmaking mechanisms for turn-based games.

The deployed architecture leveraged API Gateway WebSocket as the connection entry point, routing traffic through AWS Stateless Lambda functions, and logging/managing game states (`finding_match`, `choice`, `result`) in a DynamoDB database. On the client side, it was implemented directly in the Godot 4 Game Engine by controlling the network loop through the `poll()` function and handling data transmission via JSON strings.

**Key Takeaways & Value Gained:**
Through this presentation, I understood how to design a serverless backend infrastructure capable of supporting full-duplex, two-way communication. Additionally, I recognized real-world challenges such as cleaning up stale connections, managing DynamoDB scan costs, and the architectural path to upgrading to AWS GameLift when dedicated game servers are required for high-frequency synchronization in FPS or Racing games.

---

### 3. Speaker Viet Phat – Swinburne University of Technology

**Topic:** *GraphRAG: Build GraphRAG applications using Amazon Bedrock and Amazon Neptune*

Mr. Viet Phat introduced an advanced perspective on RAG (Retrieval-Augmented Generation) – a method that injects external knowledge into prompts to improve the response accuracy of Large Language Models (LLMs). The speaker pointed out the inherent limitations of traditional RAG when addressing complex, multi-hop reasoning questions across various data entities.

The proposed solution was GraphRAG, which leverages a Knowledge Graph structure to explicitly map relationships via nodes and edges. The presentation outlined two deployment paths on AWS: a Fully Managed Route combining Amazon Bedrock Knowledge Bases with Amazon Neptune Analytics; and a Custom Route using LlamaIndex for entity extraction and storing data into the Amazon Neptune graph database to execute Cypher Queries.

**Key Takeaways & Value Gained:**
I gained a deeper understanding of the latest trends in Generative AI (GenAI) and learned how to mitigate LLM "hallucinations" when dealing with complex data streams. Knowledge of graph-based data relationships expands my mindset for designing intelligent knowledge management systems for enterprises.

---

### 4. Speaker Bao Huynh – Endava Vietnam & ITea Lab

**Topic:** *Docker – A containerization technology*

Speaker Bao Huynh delivered a highly practical and intuitive session on virtualization and containerization. He explained why traditional Virtual Machine (VM) architectures are often heavy and resource-intensive due to each VM requiring its own dedicated Guest Operating System (Guest OS).

Docker addresses this as a lightweight alternative, allowing developers to package an application along with all its dependent libraries and configurations into a single container. These containers share the host machine's OS kernel (Host OS), enabling them to spin up within milliseconds, save memory, and guarantee consistency—meaning the app "runs smoothly across any environment," from a local machine to the cloud. The presentation also covered the structure of a standard Dockerfile, image layer caching mechanisms, and commonly used CLI commands to manage containers, networks, and volumes.

**Key Takeaways & Value Gained:**
I firmly grasped the core principles of Docker and the fundamental differences between VMs and containers. Consequently, I now know how to apply Docker to software development workflows, design microservices architectures, and optimally integrate them into automated CI/CD pipelines.

---

### 5. Speaker Truong Huy Phuoc – Teamwork Expert

**Topic:** *The Art of Effective Teamwork*

Mr. Truong Huy Phuoc shared insights into core soft skills essential for boosting collective productivity. The content emphasized that effective teamwork isn't just about gathering people together; it requires adhering to **The 4 Golden Rules**: Clear & Shared Goals; Right Person, Right Place; Open Communication & Active Listening; and Personal Accountability.

In addition to collaborative mindsets, the speaker introduced various digital tools that help optimize modern workflows, including project tracking platforms (Trello, ClickUp), shared documentation workspaces (Google Workspace), and fast-paced internal communication platforms (Slack, Discord).

**Key Takeaways & Value Gained:**
I became more aware of each individual's role within a collective and learned methodologies for conflict management and proper task delegation. Applying tools like Trello and Discord effectively will help me manage university group projects in a far more professional and organized manner.

---

### 6. Speaker Tran Trung Vinh – Senior System Administrator at Central Retail Group

**Topic:** *From IT Helpdesk to Senior Sysadmin: A practical career journey*

Mr. Tran Trung Vinh delivered a highly inspiring real-life story tailored for students and young developers. Starting out from an IT Helpdesk position with few initial advantages, he capitalized on the environment to sharpen his troubleshooting skills under high pressure, hone end-user communication, and grasp the fundamentals of IT infrastructure operations.

The major turning point came when he decided to dive deep into Linux operating systems, networking, and building self-hosted homelabs to pivot into a Sysadmin infrastructure-management role. As industry trends shifted, he successfully transformed his technical mindset from physical, on-premise infrastructure to a Cloud Mindset utilizing AWS, automating infrastructure through code (IaC with Terraform), and embracing DevOps culture (CI/CD, Docker). The speaker also shared his interview experiences at Central Retail Group and reminded everyone of a golden, lifesaver rule for system engineers: "Never test directly on the Production environment".

**Key Takeaways & Value Gained:**
The session clearly defined a career roadmap for my personal growth. I deeply appreciated his advice: master 1 or 2 core technologies, focus on building real-world projects/labs to create an impressive portfolio instead of chasing a high volume of certifications, and above all, "Your starting point does not define everything—your continuous forward journey is the ultimate answer".
