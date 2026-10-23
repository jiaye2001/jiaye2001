# Hi, I'm Jiaye Lee 👋

I'm a software engineer and M.S. Information Systems student at **Northeastern University**, based in Boston. I build full-stack applications, connect APIs and cloud services, and turn product ideas into working software.

At **ShoreUp Retirement Solutions**, I lead development and deployment of retirement-planning applications. My background in security operations also shapes how I approach access control, data handling, and automation.

I'm seeking **full-time software engineering opportunities** in full-stack, backend, or cloud development.

## What I'm building

### 🏦 ShoreUp Retirement Solutions
**Data Science & Full-Stack Engineering Intern · Feb. 2026–Present**

Turned existing financial models and calculation APIs into **3 user-facing retirement-planning applications**, leading React/TypeScript development, AWS integration, and automated frontend deployment.

- Automated account provisioning, cancellation, and reactivation through **Stripe webhooks, AWS Lambda, and Cognito**, keeping access aligned with subscription status.
- Built an **Amazon Bedrock assistant with 8 calculation workflows**, routing questions to retrieved reference material or calculation APIs for explanations and personalized estimates.
- Implemented **SSA XML earnings-history imports**, normalizing records for calculation APIs and eliminating year-by-year manual entry for imported data.
- Documented architecture decisions and discussed technical tradeoffs with the founder to guide implementation.

*Company repositories are private.*

### 🏝️ Code Ahoy — 3D Coding Practice Platform
**Personal project · Oct. 2026**

Independently developed a browser-based coding game with Claude Code assistance. Its public beta attracted **3,800+ visitors**, and the platform offers **75 algorithm problems** across themed learning worlds.

- Runs **Python and JavaScript in Web Workers**, with timeout controls that terminate stalled runs without freezing the interface.
- Uses **Cloudflare Workers, D1 (SQLite), and Firebase Authentication** for accounts and cloud saves, with revision-based conflict detection to prevent silent overwrites across devices.
- Includes visual lessons, progress-based island development, and English/Traditional Chinese interfaces.

**Stack:** React · TypeScript · Three.js · Web Workers · Pyodide/WebAssembly · Cloudflare Workers · SQLite · Firebase

[Website — full release in preparation](https://codeahoy.app)

### ☁️ Cloud-Native Webapp
**Academic project · Oct. 2025**

Built a **Java/Spring Boot product-management service** backed by PostgreSQL and S3, with resource ownership checks and AWS security controls.

- Provisioned reusable AWS infrastructure with **Terraform**, distributing application traffic across **3 availability zones** through load balancing and Auto Scaling.
- Protected AWS resources and credentials with **IAM roles, KMS, and Secrets Manager**.
- Built **GitHub Actions and Packer** pipelines for cross-account AMI deployment and zero-downtime rolling EC2 instance refresh.
- Implemented **SNS-triggered Java Lambda email verification** and CloudWatch metrics for API, database, and S3 operations.

## Let's connect

[Email](mailto:lee.jiay@northeastern.edu) · [LinkedIn](https://www.linkedin.com/in/jiayelee) · [GitHub](https://github.com/Jiaye2001)
