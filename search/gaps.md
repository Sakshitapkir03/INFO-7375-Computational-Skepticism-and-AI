# Gap Analysis

Target role: Entry-level Software Engineer focused on backend, full-stack, and AI-enabled application development.

| Gap | Evidence the target demands it | What I have | Plan to close it |
|---|---|---|---|
| Production-scale cloud deployment evidence | O*NET lists software developer work as designing, developing, modifying software systems, determining performance standards, and planning system installation or modification. BLS also says software developers design how application pieces work together and ensure programs keep functioning through maintenance and testing. | I have Docker, GitHub Actions, AWS S3/EC2, CI/CD, and project-level deployment evidence in resume.json. | Deploy Eventopia or Document Parser to AWS using Docker, GitHub Actions, logging, environment configuration, and a public architecture README. Gap closes when the deployed app, repo, CI workflow, and deployment documentation are published. |
| Distributed systems and asynchronous backend design | Backend postings commonly ask for Java, Spring Boot, AWS, Kubernetes, microservices, REST APIs, and related infrastructure. O*NET also includes determining performance standards and designing/modifying systems as core software developer work. | I have REST APIs, Redis, Kafka listed as a skill, and backend service experience, but limited public evidence of a distributed system project. | Build a small distributed job-processing system using FastAPI or Spring Boot, Redis/Kafka queueing, Docker Compose, and worker services. Gap closes when the GitHub repo includes tests, architecture diagram, load test results, and failure-handling documentation. |
| Stronger system design communication | BLS states that software developers design each piece of an application or system and plan how the pieces work together. | I can build APIs and full-stack projects, but my public portfolio does not yet show enough architecture tradeoff writing. | Publish three system design case studies: Eventopia checkout flow, Document Parser RAG pipeline, and inventory/order tracking service. Gap closes when each case study explains requirements, data model, API design, scaling decisions, tradeoffs, and testing strategy. |
| Visa and sponsorship filtering discipline | profile.yml marks future sponsorship as a gate. A company without sponsorship history may be high-risk even if the technical fit is strong. | I know I require future sponsorship, but this is not yet encoded into a repeatable search checklist beyond profile.yml. | Create a job-screening checklist that records sponsorship signal, OPT compatibility, H-1B history, role fit, and location fit before applying. Gap closes when the checklist is used on at least 10 job postings and saved as evidence in the repo or private tracking sheet. |
| Testing depth beyond project claims | BLS says software developers ensure programs continue functioning through maintenance and testing, and BLS/OES describes QA testers as developing and executing tests to identify software problems. | I have JUnit, unit testing, integration testing, Pytest, and 74 pytest tests for Document Parser, but the testing strategy is not fully explained in portfolio documentation. | Add a testing README to Document Parser and Eventopia explaining unit tests, integration tests, mocked services, CI checks, and failure cases. Gap closes when the repos include test documentation and passing CI badges. |

## Killed row

Deleted gap: Machine learning model training from scratch.

Reason: The target role is entry-level backend/full-stack/AI application engineering, not research ML engineering. My current target values applied AI/RAG integration, APIs, data workflows, and production software evidence more than training original ML models from scratch.

## Rewritten row in my own words

The most important gap for me is distributed systems evidence. I can build REST APIs, full-stack applications, and RAG services, but my resume does not yet prove that I can design services that communicate asynchronously, recover from failures, and handle background processing. To close this, I will build a distributed job-processing project using a backend API, Kafka or Redis queues, worker services, Docker Compose, tests, and load-test results. I will consider this gap closed only when the project is public, documented, tested, and explainable in an interview.

## Evidence sources used

- O*NET Software Developers profile: https://www.onetonline.org/link/summary/15-1252.00
- BLS Occupational Outlook Handbook for Software Developers, Quality Assurance Analysts, and Testers: https://www.bls.gov/ooh/computer-and-information-technology/software-developers.htm
- BLS OES Software Quality Assurance Analysts and Testers: https://www.bls.gov/oes/2023/may/oes151253.htm
- Example backend posting pattern using Java, Spring Boot, Kubernetes, and AWS: https://fico.wd1.myworkdayjobs.com/en-US/External/job/Software-Engineer---Java-AWS-IAM-Security_30847
