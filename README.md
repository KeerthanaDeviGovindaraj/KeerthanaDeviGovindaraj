<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=F3EDE3&height=140&section=header&text=Keerthana%20Devi%20Govindaraj&fontColor=2B2622&fontSize=38&fontAlign=50&fontAlignY=50" alt="Keerthana Devi Govindaraj"/>

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=20&pause=1200&color=B9502F&center=true&vCenter=true&width=720&lines=Full+stack+engineer;Software+that+shows+its+work;Open+to+full-time+SWE+roles" alt="Full stack engineer. Software that shows its work. Open to full-time SWE roles."/>

M.S. Software Engineering Systems @ Northeastern University, Boston

[![Portfolio](https://img.shields.io/badge/Portfolio-2B2622?style=for-the-badge&logo=netlify&logoColor=F3EDE3)](https://keerthanadevigportfolio.netlify.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-2B2622?style=for-the-badge&logo=linkedin&logoColor=F3EDE3)](https://www.linkedin.com/in/keerthanadevig28062002/)
[![Resume](https://img.shields.io/badge/Resume-2B2622?style=for-the-badge&logo=readme&logoColor=F3EDE3)](https://keerthanadevigportfolio.netlify.app/Keerthana_Devi_Govindaraj_Resume-SDE.pdf)
[![Email](https://img.shields.io/badge/Email-2B2622?style=for-the-badge&logo=gmail&logoColor=F3EDE3)](mailto:govindaraj.ke@northeastern.edu)

![Open to full-time SWE roles](https://img.shields.io/badge/Open%20to-Full--time%20SWE%20roles-B9502F?style=flat-square&labelColor=2B2622)

</div>

---

## About

**I like software that shows its work.**

I started in electronics and computer engineering at SRM, then found machine learning through an internship classifying support tickets and a research project on eye-tracking that ended up published. From there I moved into full stack engineering at FITA Academy, where I shipped a student management system for 500+ students. Now I'm doing my master's in Software Engineering Systems at Northeastern and working at Linedata.

The thread through my recent projects is trust. AI tools are easy to build and hard to believe, so I try to make ones that check themselves and say plainly what they don't know.

- **Show the work.** [SchemaLens](https://github.com/KeerthanaDeviGovindaraj/schemalens) cross-checks every AI explanation against static analysis. [Dry Run](https://github.com/KeerthanaDeviGovindaraj/Dry-Run) tags each claim as given, benchmark, or assumption.
- **Say what it doesn't know.** [IntentTrace](https://github.com/KeerthanaDeviGovindaraj/intenttrace) labels its synthetic results as pipeline tests, not accuracy. [HeatSink](https://github.com/KeerthanaDeviGovindaraj/HeatSink) calls itself a screening tool, not a permit decision.
- **Test how it breaks.** Property-based tests in HeatSink and IntentTrace, and a hand-labeled accuracy benchmark that runs in CI for SchemaLens.

**Currently:** Product Analyst at Linedata, master's student at Northeastern, and shipping AI-systems side projects. The latest is IntentTrace.

---

## Featured projects

### [SchemaLens](https://github.com/KeerthanaDeviGovindaraj/schemalens)
Point it at a legacy PostgreSQL database and it becomes readable again. Searchable docs for every table and function, a read/write lineage map parsed straight from the PL/pgSQL, plain-English explanations cross-checked against static analysis, and an MCP server so AI assistants write correct SQL against your schema. Accuracy is scored against a hand-labeled benchmark in CI.

`Python` `TypeScript` `React` `PostgreSQL` `PL/pgSQL` `MCP`

[Live demo](https://web-sigma-six-99.vercel.app) · [Code](https://github.com/KeerthanaDeviGovindaraj/schemalens)

### [IntentTrace](https://github.com/KeerthanaDeviGovindaraj/intenttrace)
When an AI agent gets tricked into buying something, who pays? A pre-payment gate blocks suspicious carts, and an investigator replays the purchase without the suspicious text to decide whether it was legitimate, out of scope, tampered with, or manipulated by prompt injection. Decisions land in a signed, tamper-evident log. Scored on a 300-case synthetic benchmark, and upfront that this tests the pipeline, not real-world accuracy.

`Python` `FastAPI` `React` `TypeScript` `MCP` `Docker`

[Live demo](https://intenttrace.onrender.com) (free tier, the first load can take about a minute) · [Code](https://github.com/KeerthanaDeviGovindaraj/intenttrace)

### [HeatSink](https://github.com/KeerthanaDeviGovindaraj/HeatSink)
A screening tool that answers one question: if you cooled an AI data center with seawater, where would its heat do the least harm to the ocean? It maps coastal temperatures, models the thermal plume, and gives planners a plain-English read. Covered by unit and property-based tests. Built with a teammate.

`TypeScript` `React` `Vite` `Vitest`

[Live demo](https://keerthanadevigovindaraj.github.io/HeatSink/) · [Video](https://youtu.be/4AGqKQUWBaI) · [Code](https://github.com/KeerthanaDeviGovindaraj/HeatSink)

### Cloud-Native Serverless App
Production-style AWS infrastructure in 3,000+ lines of Terraform (VPCs, EC2 Auto Scaling, RDS Multi-AZ, ALB, Route53), plus an SNS to Lambda to DynamoDB verification pipeline and secure-by-default IAM, KMS, and Secrets Manager.

`Python` `FastAPI` `Terraform` `AWS` `Packer` `GitHub Actions`

[Infrastructure](https://github.com/KeerthanaDeviGovindaraj/tf-infra-fork) · [App](https://github.com/KeerthanaDeviGovindaraj/webapp-FORK)

### [Dry Run](https://github.com/KeerthanaDeviGovindaraj/Dry-Run)
Rehearse a product decision before it's real. Seven AI stakeholders (engineering, marketing, risk, a devil's advocate and more) pressure-test the call, then a decision lead writes a brief with the case against it and an assumptions register. You can ground the panel in your own CSV so it argues from real numbers instead of inventing them.

`Python` `CrewAI` `Streamlit` `OpenAI` `Docker`

[Code](https://github.com/KeerthanaDeviGovindaraj/Dry-Run)

**Earlier work:** [GLIMPSE](https://github.com/KeerthanaDeviGovindaraj/GLIMPSE) (AI sports commentary on the Gemini API, team of 4, [live](https://glimpse-kappa.vercel.app/)) · [InboxTriage](https://github.com/KeerthanaDeviGovindaraj/inboxtriage) (AI email triage for accounting firms) · [Eye-tracking ASD diagnosis](https://github.com/KeerthanaDeviGovindaraj/Autism_Eye) (CNN research, published)

---

## Stack

<div align="center">
<img src="https://skillicons.dev/icons?i=py,ts,js,java,react,nextjs,redux,fastapi,spring,nodejs,aws,terraform,docker,postgres,mongodb,githubactions,vite,tailwind,tensorflow,opencv,git&perline=11&theme=light" alt="Python, TypeScript, JavaScript, Java, React, Next.js, Redux, FastAPI, Spring Boot, Node.js, AWS, Terraform, Docker, PostgreSQL, MongoDB, GitHub Actions, Vite, Tailwind CSS, TensorFlow, OpenCV, Git"/>
</div>

Each item points to where I've actually used it.

- **Languages:** Python (SchemaLens, IntentTrace, Dry Run, Cloud-Native, ASD research), TypeScript (HeatSink, SchemaLens, IntentTrace, InboxTriage), Java (Spring Boot at FITA Academy), SQL and PL/pgSQL (SchemaLens), JavaScript (GLIMPSE)
- **Frontend:** React (HeatSink, SchemaLens, IntentTrace, GLIMPSE, FITA Academy), Next.js (InboxTriage), Redux (GLIMPSE), Tailwind CSS (IntentTrace, InboxTriage), Vite (HeatSink, SchemaLens, IntentTrace)
- **Backend:** FastAPI (SchemaLens, IntentTrace, Cloud-Native), Spring Boot (20+ REST APIs with JWT and RBAC at FITA Academy), Node.js (GLIMPSE)
- **Cloud and DevOps:** AWS (Cloud-Native: EC2 Auto Scaling, RDS Multi-AZ, ALB, Route53, Lambda, SNS, DynamoDB, IAM, KMS, Secrets Manager), Terraform, Packer, Docker (IntentTrace, Dry Run, Aican Automate), GitHub Actions (CI for SchemaLens, IntentTrace, Cloud-Native; deploys for HeatSink)
- **Data:** PostgreSQL (SchemaLens, Cloud-Native), MongoDB (FITA Academy, GLIMPSE), DynamoDB (Cloud-Native)
- **AI and ML:** OpenAI (InboxTriage, Dry Run), Gemini (GLIMPSE), multi-agent with CrewAI (Dry Run), MCP servers (SchemaLens, IntentTrace), TensorFlow and OpenCV (ASD research), NLP (ticket classifier at Aican Automate)
- **Testing and tools:** pytest, Vitest, property-based testing (fast-check in HeatSink, Hypothesis in IntentTrace), labeled benchmarks, Kiro for spec-driven development (IntentTrace, HeatSink)

Also worked with: Angular, Material-UI, Django, Express, MySQL, SQLAlchemy, PyTorch.

---

## Let's talk

Open to full-time Software Engineering, Full Stack, and Cloud roles. If you're hiring, or you just want to talk shop, say hi.

[Portfolio](https://keerthanadevigportfolio.netlify.app) · [LinkedIn](https://www.linkedin.com/in/keerthanadevig28062002/) · [Email](mailto:govindaraj.ke@northeastern.edu)
