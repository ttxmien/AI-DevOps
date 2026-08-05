# DOCUMENTATION

AI DevOps Engineer Learning Roadmap

Target Audience:
- Software Engineers
- Embedded Engineers
- Automotive Engineers
- Developers transitioning toward DevOps and AI

Goals:
- Build strong DevOps fundamentals
- Master CI/CD automation
- Learn Cloud and Infrastructure as Code
- Apply AI to software delivery workflows
- Learn AIOps and LLMOps concepts
- Build AI-powered engineering assistants

---

# PHASE 1: DEVOPS FOUNDATIONS [Week 1-2]

## Objective

Understand how modern software is developed, delivered and operated.

| Lesson | Resource | Link | Notes |
|----------|----------|----------|----------|
| 01-DevOps-Fundamentals.md | Microsoft Learn: Introduction to DevOps | https://learn.microsoft.com/en-us/training/modules/introduction-to-devops/ | Core DevOps concepts |
| 02-Git-Advanced.md | Pro Git Book | https://git-scm.com/book/en/v2 | Branching, Rebase, PR Workflow |
| 03-Linux-Basics.md | Linux Journey | https://linuxjourney.com | Linux fundamentals |
| 04-Networking-Fundamentals.md | Cloudflare Learning Center | https://www.cloudflare.com/learning/ddos/glossary/tcp-ip/ | TCP/IP fundamentals |
| 05-System-Design-Basics.md | ByteByteGo | https://bytebytego.com | Service architecture |

### Deliverables

- Linux development environment
- Git branching workflow
- Personal GitHub repository
- Basic software delivery workflow

---

# PHASE 2: CONTAINERS & CLOUD [Week 3-4]

## Objective

Learn how modern applications are packaged and deployed.

| Lesson | Resource | Link | Notes |
|----------|----------|----------|----------|
| 01-Docker-Basics.md | Docker Getting Started | https://docs.docker.com/get-started/ | Learn Docker from scratch |
| 02-Docker-Compose.md | Docker 101 Tutorial | https://www.docker.com/101-tutorial/ | Containers, Networks, Volumes, Compose |
| 03-Kubernetes-Introduction.md | Learn Kubernetes Basics | https://kubernetes.io/docs/tutorials/kubernetes-basics/ | Official Kubernetes tutorial |
| 04-Azure-Fundamentals.md | Microsoft Learn AZ-900 | https://learn.microsoft.com/en-us/training/paths/microsoft-azure-fundamentals-describe-cloud-concepts/ | Cloud basics |
| 05-Terraform-Introduction.md | Terraform Tutorials | https://developer.hashicorp.com/terraform/tutorials | Infrastructure as Code hands-on |

### Labs

- Run applications in Docker
- Build custom Docker images
- Deploy multi-container application
- Deploy to Azure Free Tier

### Deliverables

- Dockerized application
- First cloud deployment
- Terraform sample project

---

# PHASE 3: CI/CD ENGINEERING [Week 5-6]

## Objective

Automate build, test and deployment pipelines.

| Lesson | Resource | Link | Notes |
|----------|----------|----------|----------|
| 01-CI-CD-Fundamentals.md | GitHub Skills | https://learn.github.com/skills | Interactive hands-on learning |
| 02-GitHub-Actions.md | Getting Started with GitHub Actions | https://learn.github.com/learning/gettingStartedwithGitHubActions | Workflow automation |
| 03-Jenkins-Fundamentals.md | Jenkins User Handbook | https://www.jenkins.io/doc/book/ | Traditional CI/CD |
| 04-Build-Automation.md | Modern CMake Guide | https://cliutils.gitlab.io/modern-cmake | Practical CMake |
| 05-Artifact-Management.md | JFrog Academy | https://academy.jfrog.com | Artifact lifecycle |

### Labs

- Build pipeline
- Run automated tests
- Upload artifacts
- Release tagged version automatically

### Deliverables

- Complete CI pipeline
- Automated releases
- Build dashboard

---

# PHASE 4: TESTING & QUALITY ENGINEERING [Week 7]

## Objective

Ensure software quality through automation.

| Lesson | Resource | Link | Notes |
|----------|----------|----------|----------|
| 01-Testing-Pyramid.md | Martin Fowler Test Pyramid | https://martinfowler.com/articles/practical-test-pyramid.html | Testing strategy |
| 02-GoogleTest.md | GoogleTest Quick Start | https://google.github.io/googletest/quickstart-cmake.html | Unit testing |
| 03-PyTest.md | PyTest Getting Started | https://docs.pytest.org/en/stable/getting-started.html | Python testing |
| 04-SonarQube.md | SonarQube Getting Started | https://docs.sonarsource.com/sonarqube/latest/try-out-sonarqube/ | Code quality |
| 05-OWASP-Basics.md | OWASP Top 10 | https://owasp.org/www-project-top-ten/ | Security basics |

### Labs

- Build Unit Tests
- Generate Coverage Report
- Integrate SonarQube
- Security Scan Pipeline

### Deliverables

- Quality Gate Pipeline
- Coverage Dashboard

---

# PHASE 5: OBSERVABILITY & SRE [Week 8-9]

## Objective

Monitor distributed systems and troubleshoot incidents.

| Lesson | Resource | Link | Notes |
|----------|----------|----------|----------|
| 01-Logging.md | OpenTelemetry Introduction | https://opentelemetry.io/docs/what-is-opentelemetry/ | Logs, Metrics, Traces |
| 02-Metrics.md | Prometheus Getting Started | https://prometheus.io/docs/prometheus/latest/getting_started/ | Hands-on tutorial |
| 03-Grafana.md | Grafana Fundamentals | https://grafana.com/tutorials/grafana-fundamentals/ | Dashboards & Monitoring |
| 04-Tracing.md | Jaeger Architecture | https://www.jaegertracing.io/docs/latest/architecture/ | Distributed tracing |
| 05-SRE-Basics.md | Google SRE Book | https://sre.google/sre-book/table-of-contents/ | Reliability engineering |

### Labs

- Create Dashboard
- Add Application Metrics
- Configure Alerts
- Incident RCA

### Deliverables

- Monitoring Dashboard
- Alert Rules
- Incident Template

---

# PHASE 6: AI FOR SOFTWARE ENGINEERING [Week 10]

## Objective

Use AI effectively in day-to-day engineering work.

| Lesson | Resource | Link | Notes |
|----------|----------|----------|----------|
| 01-GitHub-Copilot.md | GitHub Skills: Copilot | https://learn.github.com/skills | Interactive Copilot course |
| 02-Cursor.md | Cursor Documentation | https://cursor.com/docs | AI IDE |
| 03-Prompt-Engineering.md | Learn Prompting | https://learnprompting.org | Prompt fundamentals |
| 04-AI-Code-Review.md | GitHub Copilot Features | https://github.com/features/copilot | AI review workflow |
| 05-AI-Documentation.md | Docusaurus Tutorial | https://docusaurus.io/docs | Docs automation |

### Labs

- Generate code
- Generate unit tests
- Generate CI/CD
- Generate documentation

### Deliverables

- Prompt Library
- AI Workflow Handbook

---

# PHASE 7: AI FOR DEVOPS [Week 11]

## Objective

Apply AI to DevOps activities and operations.

| Lesson | Resource | Link | Notes |
|----------|----------|----------|----------|
| 01-AI-for-CI-CD.md | GitHub Skills + Copilot | https://learn.github.com/skills | AI-assisted pipeline generation |
| 02-AI-for-Troubleshooting.md | OpenTelemetry | https://opentelemetry.io/docs/what-is-opentelemetry/ | RCA assistance |
| 03-AI-for-Release.md | GitHub Releases | https://docs.github.com/en/repositories/releasing-projects-on-github | Release automation |
| 04-AI-for-Incident-Management.md | Google SRE Workbook | https://sre.google/books/ | Incident response |
| 05-Auto-Documentation.md | MkDocs Getting Started | https://www.mkdocs.org/getting-started/ | Documentation generation |

### Labs

- Pipeline Generator
- AI Release Notes
- AI RCA Generator
- AI Incident Summary

### Deliverables

- AI DevOps Toolkit
- Incident Assistant

---

# PHASE 8: AIOPS & LLMOPS [Week 12]

## Objective

Understand how AI systems are operated at scale.

| Lesson | Resource | Link | Notes |
|----------|----------|----------|----------|
| 01-AIOps-Basics.md | IBM AIOps | https://www.ibm.com/cloud/learn/aiops | AIOps overview |
| 02-LLMOps-Basics.md | Microsoft Learn Generative AI | https://learn.microsoft.com/en-us/training/paths/get-started-with-artificial-intelligence-on-azure/ | AI lifecycle |
| 03-RAG-Fundamentals.md | LangChain RAG Tutorial | https://python.langchain.com/docs/tutorials/rag/ | Retrieval systems |
| 04-Model-Monitoring.md | MLflow Tracking | https://mlflow.org/docs/latest/tracking.html | Model monitoring |
| 05-Vector-Databases.md | Pinecone Learn | https://www.pinecone.io/learn/ | Embeddings and retrieval |

---

# PHASE 9: AI AGENTS FOR DEVOPS [Week 13-14]

## Objective

Build AI assistants that automate engineering workflows.

| Lesson | Resource | Link | Notes |
|----------|----------|----------|----------|
| 01-Ollama.md | Ollama Docs | https://ollama.com/docs | Local LLM |
| 02-MCP.md | MCP Getting Started | https://modelcontextprotocol.io/docs/getting-started/intro | Tool integration |
| 03-LangChain.md | LangChain Tutorials | https://python.langchain.com/docs/tutorials/ | Agent framework |
| 04-LangGraph.md | LangGraph Getting Started | https://langchain-ai.github.io/langgraph/ | Agent workflow |
| 05-Agent-Patterns.md | Anthropic Engineering Docs | https://docs.anthropic.com | Agent patterns |