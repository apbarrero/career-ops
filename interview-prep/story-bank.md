# Story Bank — Master STAR+R Stories

This file accumulates your best interview stories over time. Each evaluation (Block F) adds new stories here. Instead of memorizing 100 answers, maintain 5-10 deep stories that you can bend to answer almost any behavioral question.

## How it works

1. Every time `/career-ops oferta` generates Block F (Interview Plan), new STAR+R stories get appended here
2. Before your next interview, review this file — your stories are already organized by theme
3. The "Big Three" questions can be answered with stories from this bank:
   - "Tell me about yourself" → combine 2-3 stories into a narrative
   - "Tell me about your most impactful project" → pick your highest-impact story
   - "Tell me about a conflict you resolved" → find a story with a Reflection

## Stories

<!-- Stories will be added here as you evaluate offers -->
<!-- Format:
### [Theme] Story Title
**Source:** Report #NNN — Company — Role
**S (Situation):** ...
**T (Task):** ...
**A (Action):** ...
**R (Result):** ...
**Reflection:** What I learned / what I'd do differently
**Best for questions about:** [list of question types this story answers]
-->

### [Platform Architecture] Building frontend architecture for a data visualization product at scale
**Source:** Report #008 — Phantom — Staff Engineer, Full Stack (Wallet Platform)
**S (Situation):** Devo needed a scalable, maintainable frontend for a data visualization web app used by enterprise customers. The existing codebase had legacy jQuery components and no clear architecture.
**T (Task):** Design and implement the frontend architecture from scratch, transitioning to modern tooling (React, Webpack, Jest) while supporting rapid product expansion.
**A (Action):** Designed the component architecture, introduced modern tooling and testing patterns, and built interactive UIs that could scale with new product features. Later promoted to lead two squads and led modularization initiatives across the whole frontend.
**R (Result):** Product expanded significantly on top of the architecture. Was promoted twice (SSE → Staff → Platform Lead) in part based on this ownership.
**Reflection:** Starting with clear boundaries between UI components and data layer made the modularization phase much smoother later. I'd have pushed for stronger typing (TypeScript) earlier — we paid that debt down later.
**Best for questions about:** "Tell me about a system you designed from scratch", "How do you approach technical architecture?", "Tell me about a time you led a major technical initiative"

### [Security-Critical Engineering] Delivering a Common Criteria-certified product
**Source:** Report #008 — Phantom — Staff Engineer, Full Stack (Wallet Platform)
**S (Situation):** At Autek Ingeniería, the team was building a product that needed to achieve Common Criteria (CC) certification — a rigorous international security evaluation standard.
**T (Task):** Contribute to a multi-threaded, cross-platform application in a high-security context, while owning version control and release processes across multiple projects.
**A (Action):** Developed the application adhering to strict security requirements and process documentation. Owned release processes to ensure traceability and compliance across the full lifecycle.
**R (Result):** Product achieved Common Criteria certification. Release and version control practices became the baseline for subsequent projects.
**Reflection:** Working in a CC environment taught me that security isn't a feature you add — it's a constraint that shapes every design decision from day one. I carry that mindset into any security-adjacent work.
**Best for questions about:** "Tell me about experience with security-critical systems", "How do you approach quality and compliance?", "Tell me about a high-stakes delivery"

### [Org Design / People Leadership] Post-reorg recovery — redesigning team topology under pressure
**Source:** Report #010 — Pleo — Engineering Manager, Core Product Engineering
**S (Situation):** Devo went through a major restructuring and staff reduction, leaving 4+ squads with unclear ownership, dropped morale, and a product org that had lost confidence in engineering timelines.
**T (Task):** Merge teams, redefine ownership boundaries, and maintain delivery velocity — all while keeping the remaining engineers engaged and not looking for exits.
**A (Action):** Ran team topology redesign workshops with leads, re-established clear ownership per squad, set up cross-team dependency tracking, and rebuilt weekly alignment rituals with product managers. Was explicit with engineers about what was changing and why.
**R (Result):** Delivery velocity maintained through the restructuring period. No additional attrition. Product team confidence rebuilt within one quarter.
**Reflection:** I'd have run the topology workshops sooner — I waited for the dust to settle, but earlier clarity would have reduced anxiety. Ambiguity is more damaging than imperfect answers.
**Best for questions about:** "Tell me about managing through a difficult organizational change", "How do you handle team restructuring?", "Tell me about a time you maintained team morale under pressure"

### [Talent Development / Career Growth] Engineering career framework rollout
**Source:** Report #010 — Pleo — Engineering Manager, Core Product Engineering
**S (Situation):** No clear progression criteria at Devo — engineers didn't know what "senior" meant, causing ambiguity in 1:1s, inconsistent promotions, and quiet retention risk.
**T (Task):** Design and roll out a career ladder that was meaningful and usable, not just a document filed away.
**A (Action):** Collaborated with EMs and senior engineers to define levels grounded in real examples, not vague traits. Built manager coaching into the process. Made explicit that the framework was a tool for hard conversations, not a bureaucratic checklist.
**R (Result):** Framework adopted org-wide. Several ICs promoted using it within 6 months. EMs reported it gave them language and structure for conversations they'd been avoiding.
**Reflection:** The hardest part wasn't the framework itself — it was getting managers to have the direct conversations they'd been avoiding. I'd build manager coaching into the rollout from day one next time.
**Best for questions about:** "How do you develop engineers on your team?", "Tell me about a time you improved engineering culture", "How do you handle career conversations?"

### [Cross-Team Technical Leadership] DSL autocomplete — complex product feature spanning multiple teams
**Source:** Report #011 — Aircall — Staff Engineer
**S (Situation):** Devo needed a custom autocomplete feature for its domain-specific language code editor — a product-critical capability with no prior art in the codebase.
**T (Task):** Co-design and ship the feature across frontend and backend teams, with product alignment and user feedback built in.
**A (Action):** Collaborated with product and backend engineers to define the problem scope, designed the tokenizer and suggestion engine, iterated with real users during development.
**R (Result):** Feature shipped and used daily by all Devo users; became a reference for how complex cross-team features should be approached.
**Reflection:** I'd push for a lightweight proof-of-concept with users before investing in the full implementation — we over-engineered the first iteration. Speed of feedback matters more than completeness of the first design.
**Best for questions about:** "Tell me about leading a complex technical project end-to-end", "How do you collaborate across teams on hard technical problems?", "Tell me about a feature you designed from scratch"

### [Quality & DevOps Standards] CI/CD migration across an entire engineering org
**Source:** Report #011 — Aircall — Staff Engineer
**S (Situation):** Devo ran self-hosted CI/CD causing operational overhead and inconsistent practices across 4+ squads.
**T (Task):** Migrate the entire engineering org to SaaS-based tooling while maintaining delivery cadence and establishing new shared standards.
**A (Action):** Evaluated platforms, designed the migration plan, coordinated phased rollout with squad leads, enforced new standards via PR review and onboarding documentation.
**R (Result):** Developer experience improved, operational overhead reduced, new CI/CD practices adopted org-wide within one quarter.
**Reflection:** Migrating tooling is the easy part — migrating habits is the real work. Pair any tooling change with explicit new norms and live examples, or you end up with the same patterns in a new system.
**Best for questions about:** "Tell me about driving adoption of engineering best practices", "How do you improve DevOps maturity across teams?", "Tell me about a cross-team technical initiative you drove"

### [Incident Response / Quality] Formalizing incident response and RCA workflows at Devo
**Source:** Report #345 — Barbara Tech — VP of Engineering
**S (Situation):** Devo had recurring production issues with no systematic follow-through — no formal incident process, no RCA culture, no ownership over vulnerability patching.
**T (Task):** Establish incident response workflows, RCA processes, and vulnerability patching playbooks across engineering and operations.
**A (Action):** Designed the process from scratch, ran the first 5 RCAs personally to model the behavior, documented playbooks, and got EM buy-in through visible involvement rather than top-down mandate.
**R (Result):** Systematic RCA adopted org-wide, repeat incident rate reduced significantly.
**Reflection:** Culture change requires the manager layer to visibly do the behavior first. Issuing a policy is not enough — you have to model it publicly before people follow.
**Best for questions about:** "How do you build engineering quality culture?", "Tell me about a time you improved operational maturity", "How do you handle incidents and post-mortems?", "What does ownership mean to you as an engineering leader?"

### [Embedded Systems / Security] Delivering a Common Criteria-certified product in C++
**Source:** Report #345 — Barbara Tech — VP of Engineering
**S (Situation):** At Autek Ingeniería, the team was building a product that needed to achieve Common Criteria (CC) certification — one of the most rigorous international security evaluation standards — in a cross-platform embedded C++ context.
**T (Task):** Contribute to a multi-threaded, cross-platform application under strict security constraints while owning version control and release processes across all projects.
**A (Action):** Developed the application following strict security design requirements, ensured full process documentation for the audit trail, and owned release lifecycle for traceability and compliance.
**R (Result):** Product achieved Common Criteria certification. Release and VC practices became the baseline for subsequent projects at the company.
**Reflection:** Security is not a feature you add at the end — it is a constraint that shapes every design decision from day one. I carry that mindset into any security-adjacent or compliance-sensitive product.
**Best for questions about:** "Tell me about experience in security-critical or compliance-constrained environments", "How do you approach embedded systems or edge engineering?", "Tell me about a high-stakes delivery with external certification requirements"

### [Security-First Engineering] Building for security as a design constraint, not a checklist
**Source:** Report #011 — Aircall — Staff Engineer
**S (Situation):** Two contexts: (1) Autek Ingeniería: Common Criteria-certified product with strict audit trails; (2) TandemTrace: AI-driven SOC analysis where a false negative has real-world security impact.
**T (Task):** Deliver production software where security is a first-class constraint shaping every design decision.
**A (Action):** At Autek: owned version control and release traceability processes required for CC certification; at TandemTrace: designed the AI agent architecture with threat-modeling built into design reviews, not post-hoc.
**R (Result):** Autek product achieved Common Criteria certification; TandemTrace architecture included security review gates from day one.
**Reflection:** Security debt compounds faster than tech debt. The CC experience taught me to think about the audit trail before writing the first line of code. I now include threat model review as a standard step in architecture design, not a phase after implementation.
**Best for questions about:** "How do you build security into your engineering process?", "Tell me about experience with security-critical systems", "What does 'security-first mindset' mean to you?"

### [Data-Driven Engineering] Building engineering observability and BI instrumentation at Devo
**Source:** Report #013 — Santander — SW Engineering Excellence Director
**S (Situation):** Engineering and product at Devo had no shared view of delivery health. Issues were discovered late, post-incident forensics were slow, and cross-team coordination happened through Slack threads rather than shared data.
**T (Task):** Give cross-functional teams real-time visibility into production data and delivery metrics, without building a dedicated analytics team.
**A (Action):** Connected production databases to Metabase. Created dashboards for engineering, product, and ops. Worked with each team to define the metrics they actually cared about — not what I thought they should track.
**R (Result):** Faster issue detection and shared context across teams. Fewer "surprise" production issues. Teams started referencing data in planning conversations instead of gut feeling.
**Reflection:** Observability is a cultural change, not a technical one. The dashboard adoption required as much change management as the technical setup. The teams that used it most were the ones that helped design it.
**Best for questions about:** "How do you make engineering decisions data-driven?", "Tell me about building shared visibility across teams", "How do you measure engineering performance?", "What's your approach to DORA metrics?"

### [Engineering Enablement] Incident response formalization across engineering and ops
**Source:** Report #013 — Santander — SW Engineering Excellence Director
**S (Situation):** Incident response at Devo post-reorg was ad hoc. RCA quality was inconsistent — sometimes thorough, often superficial. Vulnerability patching had no standard playbook. Engineering and ops were often surprised by each other during incidents.
**T (Task):** Formalize incident response, RCA workflows, and vulnerability patching across engineering and operations without adding bureaucracy.
**A (Action):** Wrote playbooks in collaboration with both teams (not by decree). Ran training sessions. Built the RCA review cadence into the sprint rhythm — not as a one-off workshop but as a recurring practice. Started with 2-3 high-severity incidents as worked examples.
**R (Result):** Consistent incident handling across teams. Measurable improvement in MTTR. Engineering and ops aligned on roles and responsibilities during incidents. Fewer repeated root causes.
**Reflection:** Standards without enforcement mechanisms fail. The playbooks only stuck when we embedded the review cadence into existing rituals. Adoption is a design problem — design it to succeed, don't just publish the document.
**Best for questions about:** "How do you drive adoption of engineering standards across teams?", "Tell me about improving operational maturity", "How do you enable teams without mandating from the top?"

### [Early-Stage Architecture] Founding tech lead on an AI-driven security product
**Source:** Report #018 — Filigran — Staff / Tech Lead Software Engineer - OpenGRC
**S (Situation):** TandemTrace was building an AI agent-driven SOC analysis and threat-hunting product from scratch. No prior architecture, no established standards, fast-changing business requirements.
**T (Task):** Own the entire architecture, development standards, and quality gates as the founding technical lead and primary contributor.
**A (Action):** Designed event-driven backend architecture for AI agent orchestration and threat intelligence pipelines. Established dev standards and quality gates. Continuously aligned engineering priorities with product in an ambiguity-heavy environment.
**R (Result):** Architecture became the stable foundation for all product decisions. Engineering was aligned with business goals throughout rapid pivots.
**Reflection:** I'd have documented architectural decisions in ADRs from day one. Tribal knowledge is a liability in founding-stage companies where the team will grow quickly.
**Best for questions about:** "Tell me about designing a system from scratch", "How do you handle early-stage technical ambiguity?", "Tell me about a time you owned architecture end-to-end"

### [Security Domain Engineering] Building AI-driven threat intelligence systems
**Source:** Report #018 — Filigran — Staff / Tech Lead Software Engineer - OpenGRC
**S (Situation):** TandemTrace needed to build AI agents that could analyze SOC data, correlate threat signals, and support analyst workflows in real time.
**T (Task):** Design the architecture for a system where incorrect AI outputs have real security consequences — threat detection can't be wrong without cost.
**A (Action):** Built threat modeling into the architecture review process from day one. Designed quality gates that treated security signal accuracy as a first-class product metric, not an afterthought.
**R (Result):** Architecture included security review gates from the start; product maintained analyst trust through the early iterations.
**Reflection:** In security products, the cost of false negatives is asymmetric — one missed threat matters more than ten correctly caught. Design your quality gates around the worst-case outcome, not average-case performance.
**Best for questions about:** "What's your experience in the security domain?", "How do you build quality into AI systems?", "How do you approach building for security-critical use cases?"

### [AI Product UX] Translating AI agent output into a web interface users trust
**Source:** Report #026 — [Stealth AI Strategy Games] — Web App Engineering Manager
**S (Situation):** TandemTrace's SOC analyst product needed to surface AI agent reasoning, evidence trails, and recommendations in a way analysts could trust and act on under time pressure.
**T (Task):** Own the architecture of the web surface end-to-end — make model output legible, auditable, and actionable for expert users.
**A (Action):** Shipped early-stage web UI rendering agent chains and evidence trails; partnered with product to iterate on trust signals; treated "explain the reasoning" as a first-class product feature, not an afterthought.
**R (Result):** Product reached design-partner use; architecture held through multiple iteration cycles without rewrites.
**Reflection:** AI product UX is mostly about making uncertainty legible. Analysts (and experts generally) don't want the "what" — they want the "why". Next time I'd start with the explanation layer and work backward to the output layer.
**Best for questions about:** "Tell me about translating AI output into a user interface", "How do you build user trust in AI products?", "What's the hardest part of AI-enabled web applications?"

### [Engineering Culture] Rolling out an engineering career framework at Devo
**Source:** Report #026 — [Stealth AI Strategy Games] — Web App Engineering Manager
**S (Situation):** Engineers at Devo wanted clearer career progression; EMs wanted a shared language for leveling and performance conversations.
**T (Task):** Roll out a company-wide engineering career framework and embed it into 1:1s, performance reviews, and hiring.
**A (Action):** Partnered with HR and EM peers to define levels; ran calibration sessions; mentored engineers through their first level assignment; made the framework the default structure for 1:1s.
**R (Result):** 20+ engineers calibrated; EMs adopted the framework as a standard tool; two engineers promoted in the first cycle using the new criteria.
**Reflection:** Frameworks are scaffolding, not rules. The real value isn't the rubric — it's the manager conversations the rubric unlocks. Don't over-engineer the framework; over-invest in training managers to use it.
**Best for questions about:** "How do you grow engineers?", "Tell me about a culture change you led", "How do you run performance reviews?", "How do you mentor other EMs?"

### [Founder Partnership] Aligning engineering with fast-moving founder priorities at TandemTrace
**Source:** Report #119 — Pipekit — Head of Engineering
**S (Situation):** TandemTrace had a founding team with strong technical and product opinions. Business priorities shifted fast — what was "must-ship this sprint" could become "deprioritised" within a week.
**T (Task):** Keep engineering decisions coherent and architecture sound while remaining responsive to founder direction in a high-ambiguity, high-trust environment.
**A (Action):** Set up a lightweight decision alignment sync with the founders. Created a visible "build vs defer" log so trade-offs were explicit — not absorbed silently by engineering. Framed architectural choices as cost/benefit options, not technical preferences.
**R (Result):** Architecture stayed coherent through multiple pivots. Founders trusted engineering judgement because they could see the reasoning. No major rework from late direction changes.
**Reflection:** The key is making trade-offs visible rather than absorbing them silently. Founders can make better decisions when they see the cost of reversing direction. Protect the architecture by narrating it, not defending it.
**Best for questions about:** "How do you work with a founding team?", "Tell me about operating with high ambiguity", "How do you maintain technical direction while staying flexible?", "Tell me about working closely with a technical co-founder"

### [Developer Experience] Migrating self-hosted CI/CD to SaaS at Devo
**Source:** Report #026 — [Stealth AI Strategy Games] — Web App Engineering Manager
**S (Situation):** Devo's self-hosted CI was brittle, slow, and consumed SRE time — a constant bottleneck on rapid iteration across all squads.
**T (Task):** Migrate the whole engineering org to a SaaS CI/CD platform without disrupting release cadence.
**A (Action):** Scoped migration path; ran phased rollout squad by squad; over-invested in enablement (docs, office hours, paired migrations) rather than mandates.
**R (Result):** Migration completed across all squads; reduced SRE load; improved developer experience metrics (build times, pipeline reliability); freed SRE capacity for platform work.
**Reflection:** Migrating a shared pipeline is mostly change management. The tech work is small; getting every squad to actually switch is the real project. Next time I'd run the enablement phase even longer before flipping the default.
**Best for questions about:** "Tell me about a CI/CD modernisation", "How do you drive adoption of new tooling?", "Tell me about a cross-team infrastructure change"
