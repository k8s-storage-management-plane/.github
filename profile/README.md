# Kubernetes Storage Management Plane PoC

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->

## Project Overview
TBD CHANGE ME This project is a proof of concept Participant Management API built with Java 25 and Spring Boot. It serves as a showcase for modern backend architecture, demonstrating how to build a scalable, secure, and portable microservice. The application is specifically designed to run on WebSphere Liberty and is fully containerized with Docker, featuring an environment-aware configuration that transitions seamlessly between local development and cloud deployments.

## Tech Stack
* **git:** 2.53.0
* **OS** WSL2 / Ubuntu xxx
* **IDE:** Intellij Community Edition 2025.3.2 (Java / Node.js / JavaScript
* **Languages/Technologies:**
  * **storage-frontend**
    * JavaScript xxx
    * jQuery xxx
    * React xxx
    * HTTP5/CSS3/cj3
    * Bootstrap
    * WebSockets xxx
  * **storage-management-plane**
    * Node.js xxx
  * **storage-operator**
    * Longhorn xxx
    * Go xxx
  * MiniKube xxx
  * Helm xxx
  * Python 3
  * bash
* **Containerization:** Docker Desktop 2.6.3
* **Build Tool:** Maven 3.9+
* **Postman:** 11.83.2

## Architecture and Design Patterns


storage-frontend
Language: JavaScript (React)

Contains:
React app
Bootstrap
c3 charts
WebSocket client
API client logic
Dockerfile
README (component-level)

This is a standalone UI microservice.



storage-management-plane
Language: Node.js (Express)

Contains:
REST API
WebSocket server
Kubernetes API interaction
CRD creation logic
Reconciliation logic (if in Node)
PVC orchestration logic
Dockerfile
README (component-level)

This is the management backend.



storage-operator
This is the fork of Longhorn.

Contains:
Upstream code
Your modification(s)
Clear commit(s) showing your changes
Possibly a branch specifically for your demo feature
README explaining:
  What you changed
  Why
  Where in code
  How it affects operator/CSI lifecycle

This is the “operator + CSI maintenance proof.”

Do NOT rename internal Longhorn directories.
Keep it recognizable as a real fork.




.github
Inside:

.github/
└── profile/
    └── README.md


This README becomes your system overview page.

It should contain:
Architecture diagram
High-level flow
Component descriptions
Links to each repo
Explanation of Longhorn fork modification
Storage lifecycle explanation
Screenshots




















