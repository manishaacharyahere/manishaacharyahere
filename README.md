## Manisha Acharya

**Platform and cloud engineer.** I build the guardrails that let teams ship
infrastructure quickly without breaking production: reusable Terraform,
policy as code, and Kubernetes platform tooling.

At Broadridge Financial Solutions I own reusable Terraform modules and the
backend of an internal IaaS platform that turns a drag-and-drop design into
Terraform and a deployed AWS stack. My cost-optimisation work has saved
**$300K+**.

---

### What I work on

- **Platform engineering:** self-service infrastructure, golden-path Terraform modules, internal developer platforms
- **Cloud governance:** policy as code (OPA/Rego), compliance evidence, drift detection, FinOps
- **Kubernetes:** operators and controllers, sandboxed workloads, testing controllers against failure
- **Reliability by design:** idempotent APIs, transactional outboxes, audit trails you can verify

### Featured projects

| | |
| --- | --- |
| **[Aegis](https://github.com/manishaacharyahere/aegis-cloud-governance)**<br>Cloud governance control plane | Links cloud inventory, Terraform checks, compliance (NIST CSF, CIS AWS), drift, risk scoring, FinOps and approval-gated remediation in one self-hosted system. Go, PostgreSQL, OPA, NATS JetStream, React. Tested against real dependencies (81.7% coverage) and to 10,000 resources. [Demo](https://github.com/manishaacharyahere/aegis-cloud-governance/releases/download/v1.1.0/aegis-demo.webm) · [Docs](https://manishaacharyahere.github.io/aegis-cloud-governance/) |
| **[Ripple](https://github.com/manishaacharyahere/ripple)**<br>Safe rollouts for shared Terraform modules | Checks what a module release does to every team that uses it, plans each consumer's upgrade in a sandboxed Kubernetes Job, and rolls out in waves through an operator that halts on harm. Found 37 breaking changes shipped under minor or patch tags across 956 releases of popular AWS modules. Fault-injection tested after OSDI '22 and SOSP '23. |

### Impact at work · Broadridge Financial Solutions, 2025 to present

- **$300K+ saved** through Cloud Custodian cost optimisation: tag-based scheduling and elimination of zombie resources
- **Own the UI/UX and backend workflows** (Go, PostgreSQL) of a widely adopted internal IaaS platform that generates Terraform and deploys full AWS stacks
- **Created and own reusable Terraform modules;** onboarded RDS clusters, ECS, API Gateway, Lambda and EKS to the platform
- **1,200+ manual hours saved in 2025** through automation: EOS/EOL alerting, compliance reporting, policy checks and executive reporting

### Toolbox

**Languages** Go · Python · TypeScript · Java<br>
**Cloud & IaC** AWS · Terraform · Cloud Custodian<br>
**Platform** Kubernetes · Docker · Helm · controller-runtime<br>
**Data & messaging** PostgreSQL · NATS JetStream<br>
**Policy & security** OPA/Rego · Trivy · Checkov<br>
**Observability** OpenTelemetry · Prometheus · Grafana<br>
**Delivery** GitHub Actions · CI/CD

### Currently exploring

- Reliability testing for Kubernetes controllers: stale caches, crashes mid-reconcile, oracle-based testing
- Release safety for infrastructure code: catching breaking changes before teams upgrade
- Evidence-grounded AI for operations: models that explain, never decide

---

[LinkedIn](https://www.linkedin.com/in/manisha-acharya-here) · B.Tech in Computer Science, ITER, SOA University (CGPA 9.3) · Hyderabad, India
