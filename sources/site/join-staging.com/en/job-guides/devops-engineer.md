# Source: https://join-staging.com/en/job-guides/devops-engineer

[All job guides](https://join-staging.com/en/job-guides)

## At a glance

- Median salary€72,000€58,000 – €92,000
- Time to fill55–80 days
- Experience3–7 years

## How to hire a DevOps Engineer

Before you write the job posting, settle three framing questions. They decide which profile you actually need and help you avoid the most common mistakes in DevOps hiring at a German SMB.

**Question 1: DevOps Engineer, SRE or platform engineer?** The boundaries are often fluid at German SMBs, but the focus areas differ. DevOps Engineers focus on the delivery path: CI/CD, deployment automation, tooling for app teams, infrastructure-as-code. SRE profiles concentrate on reliability (SLOs, error budgets, incident response, observability, capacity planning). Platform engineers build the internal platform as a product for the development teams. At an SMB with fewer than 30 developers, a DevOps role usually takes on parts of all three profiles; a pure SRE or platform-engineering role only pays off from around 30 to 50 developers. If your team is under 5 developers and you do not yet run cloud infrastructure, a full-stack profile with DevOps affinity is often the right choice, not a dedicated DevOps role.

**Question 2: Which cloud stack do you have, and how mature is it?** A good DevOps Engineer on AWS and Terraform is not instantly productive on Azure with Pulumi; they need 3 to 6 weeks of ramp-up. For a mid-level profile, stack fit often counts more than absolute seniority. Feature your stack prominently in the posting (cloud provider, orchestration, IaC tool, CI/CD system, observability stack, secrets management); that filters out poorly matched profiles automatically. If your stack counts as legacy (classic Jenkins pipelines with shell scripts, on-prem VMware, no IaC), communicate that openly and deliberately seek profiles who enjoy modernization, instead of importing disappointed switchers.

**Question 3: What system complexity and compliance do you serve today, and what in 18 months?** A mid-level DevOps profile in a cluster with 5 services and one cloud account makes different daily decisions than in a system with 30 services, multiple cloud accounts, a multi-region setup and BaFin or KRITIS compliance. The ideal profile differs: pragmatism and tool-building in the first case, deep experience with distributed systems, observability and compliance auditability in the second. Clarify this dimension already in the posting and align the architecture discussion to your real complexity, not to a hypothetical scale.

If all three answers point to a full-time DevOps Engineer (and not to a full-stack profile or a dedicated SRE), go to the template below.

## JD template

Copy JDCopied [Download .docx](https://join-staging.com/downloads/job-guides/en/devops-engineer.docx)

### DevOps Engineer (m/w/d): platform and production ownership at an SMB

**\[Company name\]**, a B2B SMB in \[industry\] based in \[city\], **\[X\]** employees, **\[X\]** M€ ARR, is looking for a DevOps Engineer to strengthen an engineering team of **\[X\]** developers.

#### Your mission

You design, build and operate our platform (cloud infrastructure, Kubernetes clusters, CI/CD pipelines, observability, secrets management, backup and disaster recovery), independently on familiar topics and in alignment on structuring decisions. You share responsibility for production (on-call or standby depending on the organization) and enable the app teams to ship safe and observable services to production. You report to the **\[Tech Lead / CTO / technical management\]**.

#### Key responsibilities

- Design, build and operate cloud infrastructure and the Kubernetes platform as infrastructure-as-code (Terraform, Helm, Argo CD or comparable).
- Build and evolve CI/CD pipelines: reproducible builds, staged tests, safe deployments (rolling, blue-green, canary depending on risk).
- Operate and evolve the observability stack (centralized logs, metrics, distributed tracing, SLO and error-budget hygiene, sensible alerts).
- Lead or support production incidents (on-call or standby), co-write post-mortems, update runbooks, implement systemic fixes.
- Implement security and compliance requirements at the platform level (IAM, secrets manager, Network Policies, image signing, audit logs, policy-as-code).
- Build self-service workflows and templates for the app teams so developers can ship safe services to production independently.
- Document important technical decisions and non-trivial complexity zones (ADR or equivalent).
- Work with development teams, security and data-protection functions, PM and management on the platform roadmap and concrete requirements; constructively challenge unfeasible or counterproductive requests.

#### Profile

- **Required**: **\[3 to 7\]** years of professional experience in a DevOps, SRE or platform-engineering environment; solid command of at least one major cloud (AWS, GCP, Azure) including IAM, networking and compute; experience with container orchestration (Kubernetes or comparable), infrastructure-as-code (Terraform, Pulumi, CloudFormation), CI/CD pipelines and observability stacks (Prometheus, Grafana, Datadog or comparable); independent production ownership with on-call or standby experience.
- **Desired**: familiarity with our stack **\[to be completed\]**; experience with GitOps (Argo CD, Flux), service mesh, policy-as-code (OPA Gatekeeper, Kyverno) or compliance-heavy environments (BaFin, KRITIS, ISO 27001); open-source contributions or visible side projects (Terraform modules, Helm charts, kubectl plugins).
- **Disqualifying**: no experience with independent production ownership; blanket rejection of on-call or standby despite the operational requirement; blanket rejection of infrastructure-as-code or observability as bureaucracy.

#### What we offer

- Gross annual compensation: **\[58 to 92\]** k€ depending on experience. No structural variable; possibly VSOP or ESOP depending on the company’s stage. On-call pay handled separately as a standby allowance plus call-out hours.
- Model: **\[full-time, hybrid 2 to 3 days / week on-site, based in \[city\] / remote-friendly\]**.
- Benefits: **\[company pension, bike leasing, employee shares, vacation days, home-office policy, hardware budget, professional-development budget, conferences\]**.
- Stack: **\[to be completed: cloud provider, orchestration, IaC tool, CI/CD system, observability stack, secrets management, backup and DR setup\]**.

## Salary band

Base salary, gross annual

25th percentile

€58,000

Median

€72,000

75th percentile

€92,000

Gross fixed salary per year for a mid-level DevOps Engineer (3 to 7 years of experience) at a German SMB or Mittelstand company. Berlin, Munich and Hamburg in the SaaS and scale-up scene pull upward (85 to 105 k€); the classic Mittelstand and regional locations trend lower (55 to 68 k€). Kubernetes in production, AWS or GCP experience with IAM and networking depth, and Terraform module ownership pull upward; pure Jenkins or on-prem VMware profiles without cloud experience trend lower. Compliance-heavy environments (BaFin, KRITIS, insurance, health) pull noticeably upward. Engineering roles in Germany usually have no variable compensation component; scale-ups offer VSOP or ESOP on top. On-call pay is often handled separately as a standby allowance plus call-out hours.

**Sources:** [Destatis Verdiensterhebung (April 2025), Berufsgruppe 43 IKT-Berufe](https://www.destatis.de/DE/Themen/Arbeit/Verdienste/Verdienste-Branche-Berufe/_inhalt.html); [StepStone Gehaltsreport 2026, DevOps Engineer Deutschland](https://www.stepstone.de/gehalt/DevOps-Engineer.html); [Glassdoor Gehaltsdaten DevOps Engineer Deutschland 2026](https://www.glassdoor.de/Gehalt/devops-engineer-gehalt-SRCH_KO0,15.htm); [Honeypot State of Software Engineering Germany 2025](https://www.honeypot.io/state-of-european-tech)

## Where to source this role

1. 01
 
 The most important active sourcing channel for DevOps profiles in Germany. Active sourcing via Recruiter Lite plus personalized InMails clearly beats pure Job Posts: experienced DevOps Engineers rarely look actively, but are open to targeted outreach with a clear stack and scaling angle. Filter precisely on Kubernetes, Terraform, AWS or GCP, observability stacks (Prometheus, Datadog, Grafana) and on on-call plus incident-response experience before you reach out. Generic sequences land below 5 % reply rate; precise messages with a concrete stack and scaling angle reach 15 to 25 %.
 
2. 02
 
 Still relevant for DevOps profiles in the classic Mittelstand outside the Berlin startup scene, especially in NRW, Bavaria and Baden-Württemberg. Particularly for profiles aged 30 to 50 with a Linux and networking background (former SysAdmin or site-reliability roles) at insurers, Industry 4.0 or mechanical engineering firms who do not actively maintain LinkedIn. In classic industrial sectors often on par with LinkedIn or better. For pure cloud-native and Kubernetes profiles the signal is weaker than LinkedIn; for hybrid on-prem-to-cloud migrations it is the stronger signal.
 
3. 03
 
 heise jobs speaks to the classic German tech audience that reads iX and c't; high signal quality for profiles with Linux, networking and security depth, often anchored in the Mittelstand and public-sector environment. Honeypot is the DE-specific tech reverse-recruiting platform: DevOps profiles create profiles with their stack and salary expectation, companies apply to them. Works especially well for senior profiles with Kubernetes or cloud-native experience. Overall lower volume than LinkedIn and XING, but markedly higher signal quality per contact.
 
4. 04
 
 Stack Overflow Jobs delivers lower volume in Germany than LinkedIn, but profiles with visible stack engagement (high reputation in DevOps, Kubernetes or Terraform tags) are often particularly deep technically. GitHub sponsorships and visible open-source contributions add signal for senior DevOps profiles (Helm chart maintainers, Terraform module authors, kubectl plugin developers). Referrals from your own engineering team deliver the highest hit rate for DevOps roles in practice: the DACH DevOps network is small and well connected. Set up a referral bonus program of €1,500 to €3,000.
 

[Compare every board in this market →](https://join-staging.com/en/blog/german-job-sites)

## Evaluation playbook

The DevOps Engineer role reveals itself across four evaluation stages. The incident and architecture stage (stage 3) is the most predictive for this role: DevOps profiles make daily decisions on infrastructure, deployment strategy and observability that are hard to reverse later and become visible in production.

1. 01
 
 ### Stage 1: CV review
 
 Look for stack consistency (a profile on AWS and Terraform does not switch to Azure and Pulumi without 3 to 6 months of ramp-up), stability (at least 18 to 24 months on previous roles) and concrete production signals (independently operated clusters, on-call experience, a visible GitHub with IaC modules or kubectl plugins, involvement in post-mortems or runbooks). The degree counts less than the last 3 to 5 years of practice: a self-taught engineer with 5 years of on-call and Kubernetes in production often scales better than a top-university graduate with no pager experience.
 
2. 02
 
 ### Stage 2: Phone screen (30 min)
 
 Four questions only: (1) Describe the infrastructure you were last responsible for; what was your contribution?, (2) Tell me about the most recent production incident you led., (3) Which technical decision did you make recently that you still have doubts about? (humility and reflection), (4) Why are you looking for a change now? Outcome: go/no-go in a 5-minute debrief. Avoid technical gotcha questions at this stage.
 
3. 03
 
 ### Stage 3: Technical interview and architecture (90 min)
 
 Two parts: 40 to 50 min of an incident walkthrough on a real case the candidate handled (symptom, hypotheses, validation, root cause, systemic fix, what to do differently next time), followed by 30 to 40 min of an architecture discussion on a concrete case (How would you build \[a specific platform component\]? What trade-offs?). Assess the ability to think out loud, to clarify assumptions before the solution (expected volume, consistency guarantees, failover, compliance), to weigh simplicity against scalability and to flag zones of uncertainty. Avoid pure trivia questions; favor questions tied to day-to-day work.
 
4. 04
 
 ### Stage 4: References (structured check)
 
 Call two references: a former tech lead or direct manager and a former engineering peer (dev or DevOps). Ask both the same 4 questions: What is she/he strongest at? Where would you hire someone complementary? Would you hire them again tomorrow, why? An example of a difficult technical decision or a complex incident handled independently? The 4th question delivers the real autonomy and incident-response signal.
 

## Structured interview questions

1. Describe a CI/CD pipeline you designed and brought to production. What decisions did you make on build reproducibility, test stages and deployment strategy?
 
 What a strong answer surfaces
 
 Deliberate decisions rather than defaults: deterministic builds (lockfiles, container digests, no latest tags), explicit test stages (unit, integration, smoke, E2E) with a rationale for the order, a deployment strategy matched to risk (rolling, blue-green, canary, feature flag). Bonus: the candidate names decisions they would make differently today. Anyone who describes everything in Jenkins scripts with shell scripts and no reflection has rarely weighed things up seriously.
 
2. Tell me about a production incident you led to resolution. What was the symptom, how did you diagnose it and how long did it take?
 
 What a strong answer surfaces
 
 A structured debugging method: reproduction, logs, metrics, hypotheses validated by experiment. Honesty on duration (a real production incident with impact is rarely closed in under 30 min). Bonus: the candidate names the root cause and the systemic fix (post-mortem, runbook, new alert, architecture change), not just the hotfix. Answers like I restarted the cluster without any diagnosis point to weak investigation skills.
 
3. Describe a migration of a critical component you owned (e.g. on-prem to cloud, VMs to Kubernetes, a database engine migration). How did you handle downtime, rollback and data or traffic control?
 
 What a strong answer surfaces
 
 An incremental approach: parallel systems with traffic shifting (1 %, 10 %, 50 %, 100 %), an explicit rollback plan at each step, validation of data or functional consistency before each cut-over. Bonus: the candidate names a case where the migration took longer than planned and what they learned. Anyone who describes a big-bang migration without rollback shows risk blindness.
 
4. The P99 latency of your most critical API has been over SLO on 5 % of requests since the last deploy. The logs show no obvious error. How do you proceed in the next 30 minutes?
 
 What a strong answer surfaces
 
 A structured method: (1) keep the rollback option open and communicate with stakeholders, (2) correlate metrics (CPU, memory, connection pool, network, DB latency, GC pauses), (3) trace a slow request end to end from edge to DB, (4) identify a pattern (time of day, endpoint, tenant, region). Anyone who immediately jumps to it's probably the DB without investigating has a bias. Bonus: explicitly mentions starting a post-mortem document in parallel and bringing in an on-call backup.
 
5. Your team currently has no tests in the pipeline, manual deployments over SSH, no centralized logging and no alerting. You have 90 days. What is your plan?
 
 What a strong answer surfaces
 
 Diagnosis first: not trying to fix everything at once. Prioritization by risk and impact (typically: first centralized logging and basic alerting for visibility, then reproducible builds and a first automated deploy path for one service, then a test pipeline for the most critical business logic, IaC capture last). Alignment with the team and tech lead before each measure. Anyone who dives straight into a full GitOps migration with a service mesh shows a lack of pragmatism.
 
6. A developer demands production SSH access to all servers in order to debug faster. How do you react?
 
 What a strong answer surfaces
 
 Clarifying the actual need before discussing the solution (debug requirements can often be met with better logs, tracing and just-in-time access). Offering alternatives: better observability, read-only access, JIT access with an audit trail, ephemeral debug pods in Kubernetes. Answers like sure, I'll give it to him show security blindness; answers like never, that's not possible show a lack of collaboration. The right answer combines constructive pushback with a concrete alternative path.
 
7. Explain the difference between a Kubernetes Deployment, a StatefulSet and a DaemonSet. When do you use which, and what are the typical pitfalls?
 
 What a strong answer surfaces
 
 A solid understanding of the workload types: Deployment for stateless, interchangeable pods (web, API), StatefulSet for stable identity and persistent storage binding (databases, queues), DaemonSet for one pod per node (log forwarders, network plugins). Typical pitfalls: PVC loss when scaling a StatefulSet, ordering problems during rolling updates of a StatefulSet, a DaemonSet on nodes without the required resources. Bonus: mention of PodDisruptionBudgets and topology spread constraints. Anyone who cannot separate the three types builds data-loss risks into production.
 
8. What do you log, measure and alert on for a Kubernetes platform with 20 to 50 services before you declare it production-ready? Which tools do you use?
 
 What a strong answer surfaces
 
 A clear separation of logs (structured, with trace ID, centralized in Loki, Elasticsearch or a vendor), metrics (RED or USE method: rate, errors, duration; or utilization, saturation, errors) and distributed tracing (OpenTelemetry, Jaeger, Tempo). A concrete tool choice with rationale (Prometheus plus Grafana, Datadog, Sentry, Loki). Alerts only on actionable signals, with SLOs and an error budget per service. Cluster level: node health, kube-state-metrics, control-plane latency. Anyone who says log everything indiscriminately shows a lack of experience with platforms above a certain size.
 
9. What security checks do you run on a new service before it enters the production Kubernetes cluster? Which classes of attack do you concretely keep in mind?
 
 What a strong answer surfaces
 
 A clear list: container image scanning (Trivy, Grype) for CVEs and secrets, signed images (Cosign, Notary), Pod Security Standards (Restricted or Baseline), Network Policies per namespace, secrets via an external manager (Vault, AWS Secrets Manager, Sealed Secrets), least-privilege RBAC per ServiceAccount, resource limits against noisy-neighbor effects. Concrete measures: admission controllers (OPA Gatekeeper, Kyverno), active audit logs, secure egress rules. Bonus: concrete experience with an incident prevented or contained by one of these measures.
 
10. Design: we want to migrate our existing monolithic application to Kubernetes without disrupting production. How do you design it?
 
 What a strong answer surfaces
 
 Clarification before proposing (the application stack, database topology, current deploy process, acceptable risk tolerance, cloud provider, compliance requirements). A coherent migration strategy: first containerize without an architecture change, deploy in parallel in Kubernetes next to the current system, traffic shifting (1 %, 10 %, 50 %, 100 %) via the load balancer, a rollback path per step. Bonus: explicit handling of stateful components (DB, sessions, file uploads), observability before the switch, incremental build-out of platform capabilities (logging, monitoring, tracing, autoscaling) alongside the migration. Anyone who dives straight into code without clarifying shows a design weakness.
 
11. Design: we want a disaster-recovery strategy for a critical, data-intensive application on AWS. RPO 15 min, RTO 1 hour, single-region acceptable. How do you design it?
 
 What a strong answer surfaces
 
 Recognizing that RPO and RTO dictate the strategy: Multi-AZ as the baseline (synchronous, RPO near 0 for the DB), automated database snapshots every 15 min, point-in-time recovery active, tested restore procedures (not just documented). Solution space: RDS Multi-AZ or Aurora, S3 with versioning and cross-region replication for static assets, infrastructure-as-code for fast rebuild, regular DR drills. Bonus: explicit handling of application consistency (no raw volume snapshots without database quiescence), clear runbooks for the restore. Anyone who takes backups without testing the restore has no DR strategy.
 
12. Debug: in your production environment, latency for all services on one Kubernetes node rises intermittently, then recovers. Other nodes are fine. How do you proceed?
 
 What a strong answer surfaces
 
 A structured method: (1) check node metrics (CPU throttling, memory pressure, disk IO, network saturation, kubelet health), (2) look at the pod distribution on the node (noisy neighbor? a pod with high resource use and no limits?), (3) kernel logs on the node (dmesg, journalctl), (4) check hardware or the underlying EC2 instance (steal time, EBS saturation, network burst credits exhausted). Bonus: recognizing that intermittent on one node often points to a resource bottleneck, a problematic pod or hardware issues, and immediately considering a cordon plus eviction as mitigation.
 
13. How do you take a critical code review of a Terraform module or a pipeline change you were convinced was good?
 
 What a strong answer surfaces
 
 Openness: the ability to separate code from personal ego. Bonus: the candidate names a case where a review actually changed their mind (a different module structure, a different variable, a different provider configuration). Anyone who describes having only explained their logic to the reviewer instead of listening shows a coachability weakness; at an SMB with a small DevOps team that is a hard no-go signal.
 
14. Describe a situation where you helped a developer take ownership of production (e.g. a service newly entered your on-call rotation).
 
 What a strong answer surfaces
 
 An active mentoring posture: pair programming on critical paths, runbooks built jointly, on-call onboarding with a clear escalation path, sharing good practices (backoff, idempotency, safe deploys). Anyone who says I just do it myself, it's faster shows a centralizing posture that conflicts with the scaling goal of a platform function. The right answer describes enablement, not takeover.
 
15. What draws you to a DevOps role at an SMB rather than a platform-team role at a large corporation? Which aspects would you miss at an SMB?
 
 What a strong answer surfaces
 
 A realistic understanding of the trade-offs: at an SMB more autonomy, access to the whole stack, a direct link to the product, but less specialization, smaller incident complexity, fewer resources for internal tools and migrations. Bonus: the candidate names concrete aspects that fit the SMB environment at their current career point (wants to own a whole area, wants to be closer to the product). Anyone who dismisses the corporation as slow and bureaucratic without naming the advantages shows a lack of reflection.
 

## How to recognize a great hire

| Trait | Below bar | On bar | Above bar |
| --- | --- | --- | --- |
| Cloud infrastructure | Stumbles over fundamentals (IAM, network topology, VPC, container runtime, Kubernetes workload types). Searches for solutions by trial and error without a clear mental model. Hard to put on a new cloud. | Handles the current cloud stack independently (AWS, GCP or Azure, at least IAM, compute, networking, storage, Kubernetes or comparable orchestration). Can learn a second cloud in 2 to 4 weeks. Understands the fundamentals well enough to debug deeply when needed. | The reference person for the cloud platform on the team and able to switch to a different cloud within a few weeks. Anticipates classic pitfalls (IAM drift, NAT gateway costs, EBS burst credits, kubelet memory pressure, connection limits on load balancers). Builds useful, not premature abstractions (reusable Terraform modules with clear contracts). |
| Systems thinking | Jumps into the solution without clarifying the conditions. Over-architects (a service mesh for 3 services) or under-architects (everything as one VM setup with no boundaries). Struggles to weigh simplicity, consistency and scalability. | Clarifies need, load, consistency requirements and compliance before building. Pragmatic in weighing: no premature architecture for an uncertain future, but identifies zones where structure pays off (idempotency, retry strategies, clear service boundaries). Can pivot when the initial hypothesis does not hold. | Designs systems that age well: clear platform contracts between app teams and the platform, well-chosen consistency guarantees, idempotent and safe operations, minimal dependencies. Recognizes their own zones of uncertainty and proposes targeted POCs. Trains the team in systemic thinking. |
| Incident response | Helpless without logs or metrics. Reacts to incidents with a restart or with luck. No structured diagnosis. Either logs too little or logs everything as noise. Avoids on-call. | Has a clear approach to incidents (reproduction, hypotheses, validation, mitigation, then fix). Uses structured logs, sensible metrics and tracing. Writes a post-mortem after an incident that derives action items. Takes on-call without grumbling. | The reference on the team for incident response: defines SLOs, builds alert hygiene (no pager noise), develops runbooks. Finds root causes in complex distributed systems quickly. Coaches the team in debugging hygiene. Actively drives improvements from post-mortems to implementation. |
| Dev/Ops collaboration | Treats developers as ticket requesters. Defensive in reviews. Works in a silo, shares little context. Security or platform rules are enforced without explanation. Friction instead of partnership. | Sees themselves as a platform partner to the development teams: explains platform decisions in clear language, builds self-service where it makes sense, takes app-team requirements seriously. Takes reviews constructively. Shares context in team reviews and 1:1s, documents architecture decisions (ADR). | A bridge between platform and app teams. Facilitates technical debriefs, makes trade-offs understandable, negotiates the platform roadmap transparently. Active mentoring posture toward app developers on observability, safe deploys and production ownership. |
| Automation mindset | Prefers manual interventions (over SSH, clicks in the cloud console). Sees infrastructure-as-code as bureaucracy. Recurring tasks are repeatedly done by hand. ClickOps drift as the default state. | Writes infrastructure-as-code by default (Terraform, Pulumi, CloudFormation). Recurring tasks are automated via scripts or the pipeline. Deployment, provisioning and routine operations are reproducible and versioned. Drift is detected and corrected. | Drives automation standards for the whole team: reusable modules with tests, GitOps for cluster state, automated compliance checks (policy-as-code), self-service platform workflows for app teams. Builds tools that make life easier for others rather than reserving them for themselves. |
| Autonomy and resourcefulness | Blocks themselves for hours on an unfamiliar topic without asking for help, or asks at the first obstacle. No structured debugging strategy under pressure. Waits for clear instructions instead of showing initiative. | Can diagnose familiar topics independently; asks for help after prior investigation (a summary of the problem, hypotheses, what was already tried). Stays functional under incident pressure. Brings initiative for improvements. | High resourcefulness on unfamiliar topics: reads the source code of the tools, instruments the platform, isolates root causes, builds new tools when needed. Documents the findings for the team. Independently drives platform improvements from concept to delivery. |

## 30 / 60 / 90 day success plan

### By day 30

- Full setup of the local development environment, access to all cloud accounts and clusters, on-call onboarding documented and a first small IaC change validated in production
- Read and understand the platform architecture: cloud account structure, network topology, cluster setup, CI/CD pipelines, observability stack, critical runbooks
- First documented 1:1 with the tech lead on conventions, identified technical debt, escalation paths and priorities for the next 90 days
- First substantial PR (pipeline improvement, monitoring gap closed, runbook added) reviewed and merged

### By day 60

- Delivery of a complete platform improvement end to end (concept, IaC change, pipeline integration, monitoring, documentation) under independent ownership
- First independent on-call rotation handling at least one incident and contributing to the post-mortem
- First PR review of a colleague with structured feedback, not just an approve click; active involvement in at least one app-team platform request
- Documentation of a recently handled platform area or a runbook written or updated

### By day 90

- Regular delivery (1 to 2 substantial changes per week) with quality confirmed in review and a visible contribution to at least one architecture decision
- First technical decision under independent ownership on an ambiguous platform topic (tool choice, cluster topology, backup strategy, cost optimization)
- Informal mentoring of a junior or new profile, or of an app developer on observability and safe deploys
- Formal review with the tech lead: ramp validated, development plan on 1 to 2 focus areas (e.g. SRE depth, security hardening, cost engineering, platform-PM skills)

## Common hiring mistakes for this role

DevOps roles are particularly often mis-scoped at German SMBs. The following anti-patterns regularly cost 6 to 12 months of onboarding and lead to early resignation.

1. 01
 
 ### Advertising DevOps as a pure SysAdmin role
 
 A job posting with Linux server administration, SSH, backups, patch management as the main responsibilities filters out modern DevOps profiles immediately. You attract profiles that cannot work autonomously in cloud-native setups, and you deter profiles with Kubernetes, IaC and observability depth. Instead, describe the real task mix: platform engineering, pipeline ownership, observability, incident response, enablement of the app teams. If the role really is predominantly SysAdmin, advertise it as a System Engineer, not as DevOps.
 
2. 02
 
 ### Hiring on corporate pedigree instead of production ownership
 
 A top graduate of a renowned university with 2 years at a DAX corporation or a big-tech branch is not automatically more productive than a self-taught engineer with 5 years of on-call at a startup or SMB. Large structures give their platform profiles clear contracts between teams, dedicated SRE functions and solid internal tooling; at an SMB this scaffolding is usually missing, and the lack of production autonomy becomes a burden. Weight the incident-walkthrough interview and the reference check on autonomy more heavily than the pedigree on the CV.
 
3. 03
 
 ### Demanding multi-day take-home assignments
 
 A take-home assignment of 8 or more hours actually consumes 24 hours (with emotional investment), demotivates the best profiles (who have other options in parallel) and delivers no better signal than a well-run incident walkthrough of 45 min plus a 30 min architecture discussion. You want to measure the quality of the reasoning, not the completeness. If a practical exercise still seems necessary, cap it at a maximum of 2 hours with clear scoping and accept incomplete but well-reasoned solutions.
 
4. 04
 
 ### Making the on-call expectation transparent only after the contract is signed
 
 A production-owning DevOps role with no clear statement on on-call, standby model, standby pay, average pager load and escalation paths in the posting leads to early resignation within 6 to 12 months. State the model openly: standby window (e.g. 1 week every 6 weeks), pay (standby allowance plus call-out hours), realistic pager frequency, escalation option. Profiles that reject on-call on principle are often out of place in an SMB DevOps role; better to filter them out now than to lose them after 6 months.
 

## Frequently asked questions

- What does a DevOps Engineer earn at an SMB in Germany?
 
 The reference range for a mid-level DevOps Engineer (3 to 7 years of experience) at a German SMB is 58 to 92 k€ gross fixed salary per year (median around 72 k€). Berlin, Munich and Hamburg in the SaaS and scale-up scene pull upward (85 to 105 k€); the classic Mittelstand and regional locations trend lower. Kubernetes in production, AWS or GCP experience with IAM and networking depth, and Terraform module ownership pull upward; compliance-heavy environments (BaFin, KRITIS, insurance, health) pull noticeably upward. Engineering roles in Germany usually have no variable compensation component; scale-ups offer VSOP or ESOP on top. On-call pay is often handled separately as a standby allowance plus call-out hours.
 
- What is the difference between DevOps, SRE and platform engineers?
 
 The boundaries are often fluid at German SMBs, but the focus areas differ. DevOps Engineers focus on the delivery path: CI/CD pipelines, deployment automation, tooling for app teams, infrastructure-as-code. SRE profiles (site reliability engineering) concentrate more on reliability: SLOs, error budgets, incident response, observability, capacity planning. Platform engineers build the internal platform as a product for the development teams: self-service workflows, templates, golden paths. At an SMB with fewer than 30 developers, a DevOps role usually takes on parts of all three profiles; a pure SRE or platform-engineering role only pays off from around 30 to 50 developers.
 
- How long does it take to hire a DevOps Engineer in Germany?
 
 Expect 55 to 80 days between publishing the job posting and the signed contract for a mid-level DevOps profile. The German tech market remains tight in 2025-2026, especially for profiles with a modern cloud stack (AWS or GCP, Kubernetes, Terraform) and experience with observability and incident response. The timeline lengthens in late summer and around the turn of the year. Cutting below 55 days usually sacrifices the architecture stage or the reference check and noticeably reduces hiring quality.
 
- Do DevOps Engineers need a specific university degree?
 
 No. The German tech market largely accepts self-taught profiles and career changers from classic system-administration or development roles, once there are 3 to 5 years of solid production practice, ideally with on-call experience. A degree (applied-sciences computer science, university computer science, technical mathematics) is reassuring for junior profiles but loses weight after 5 years of experience. Certifications (AWS Solutions Architect, CKA for Kubernetes, HashiCorp Terraform) can help in pre-selection but do not replace production practice. Assess on the basis of the incident walkthrough, the architecture discussion and the reference check, not on academic pedigree.
 
- What legal requirements apply to DevOps job postings in Germany?
 
 Three central requirements: (1) a gender-neutral job title with (m/w/d) or colon spelling (§ 11 AGG), (2) the obligation of pay transparency in the ad or before the first interview (EU Pay Transparency Directive 2023/970, implementation by 7 June 2026), (3) transparency about the use of AI tools for pre-selection and guaranteed human oversight (EU AI Act, from 2 August 2026). In addition: for on-call standby, observe the Working Hours Act (ArbZG); Rufbereitschaft (on-call standby) and Arbeitsbereitschaft (standby on site) differ in how they are recorded and in rest-period treatment. When engaging via freelance or temporary agency work, keep a clean separation from permanent employment to avoid bogus self-employment.
 
- Is a technical test worthwhile for every DevOps hire?
 
 Yes, combined with an architecture discussion. For DevOps profiles, the incident walkthrough (40 to 50 min, a real case the candidate handled) plus an architecture discussion on a concrete platform case is by far the most predictive step: poor decisions on cluster topology, backup strategy or observability setup only surface after months and are expensive to repair. A written exercise (e.g. a Terraform module for a typical use case) should be short (maximum 2 hours), realistic and aligned to your stack. Avoid pure trivia questions with no link to day-to-day work. Cap the expected time explicitly and accept incomplete but well-reasoned solutions.
 

## Related job guides

- [**Backend Engineer**\\ \\ €62,000·50–80 days](https://join-staging.com/en/job-guides/backend-engineer)
- [**Data Analyst**\\ \\ €53,000·45–75 days](https://join-staging.com/en/job-guides/data-analyst)
- [**Frontend Engineer**\\ \\ €58,000·50–80 days](https://join-staging.com/en/job-guides/frontend-engineer)