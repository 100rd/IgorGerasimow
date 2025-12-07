Experienced DevOps/Platform engineer with a bias toward automation, simplicity, and trust.
I don’t believe in hero culture or over-engineering. My work is driven by laziness in its best form: building things once, making them reliable, and letting them run with minimal babysitting.

I’ve worked across clouds, clusters, and continents. I enjoy fixing messes others avoid — legacy Terraform states, forgotten Helm releases, half-migrated secrets, and everything in-between.
Think of me as the platform janitor: I come in quietly, clean things up, set up self-healing systems, and leave things better than I found them.

What I value:
 • Automation > repetition
 • Processes that trust people, not gate them
 • Stable systems over shiny ones
 • Honest communication, low ego, high ownership

# Engineering Philosophy & Principles

> A principles-based guide for DevOps, SRE, and Platform Engineering excellence.

---

## Core Beliefs

| Principle | Description |
|-----------|-------------|
| **Perfect pipelines don't exist** | Chase continuous improvement, not perfection |
| **Every tool is a trade-off** | Nothing is free — understand what you gain and sacrifice |
| **Untested = broken** | Code without tests is technical debt in waiting |
| **Communication beats pure skill** | Alignment and clarity outperform raw technical ability |
| **Boring tech wins** | Maturity and discipline matter more than novelty |
| **Small batches are non-negotiable** | Speed without discipline backfires |
| **Stability of priorities matters more than you think** | Priority churn directly causes burnout |

> *"DevOps isn't about tools. It's about discipline, empathy, and connecting people with systems that actually work."*

---

## The Three Disciplines

| Discipline | Core Question |
|------------|---------------|
| **DevOps** | How do we remove friction between dev and ops? |
| **SRE** | How do we run production sustainably at scale? |
| **Platform Engineering** | How do we make the right thing the easy thing? |

---

## Core Capabilities

### Infrastructure as Code — `MUST`

All infrastructure defined in version-controlled, reviewable, testable code. No manual provisioning, no snowflake servers, no "click ops."

**If it's not in git, it doesn't exist.**

### Observability — `MUST`

Systems emit signals (logs, metrics, traces) that answer "why is this broken?" without deploying new code. You can understand internal state from external outputs.

**Debugging in production is possible, not heroic.**

### Automation — `MUST`

Repeatable tasks executed by machines, not humans. Deployments, tests, scaling, remediation — if you do it twice, automate it.

**Humans make decisions, machines execute them.**

### Incident Response — `MUST`

Defined process for detecting, triaging, mitigating, and learning from failures. Clear escalation paths, runbooks exist, postmortems are blameless.

**Time-to-recovery is measured and improved.**

### Capacity Planning — `MUST`

Proactive understanding of resource needs before demand hits. Load testing, traffic modeling, cost forecasting.

**Scaling decisions are data-driven, not reactive panic.**

---

## Definition of Done

Across DevOps, SRE, and Platform Engineering — "done" means:

- [ ] **It works in production** — not "it works on my machine," not "it passed staging"
- [ ] **It's observable** — you know when it breaks, you know why, you can trace it
- [ ] **It's documented** — runbooks exist, onboarding is possible, knowledge isn't tribal
- [ ] **It's operable by others** — the person who built it can go on vacation
- [ ] **It degrades gracefully** — failure modes are understood, blast radius is contained
- [ ] **It can be changed safely** — rollback works, feature flags exist, small batches possible
- [ ] **The user can self-serve**

### Self-Service by Discipline

| Discipline | Self-Service Goal |
|------------|-------------------|
| **DevOps** | Developers can deploy without ops tickets |
| **SRE** | Teams can manage their own error budgets |
| **Platform** | Teams can provision infrastructure without platform team involvement |

---

## References

- [DORA Research](https://dora.dev)
- [DORA 2024 Accelerate State of DevOps Report](https://dora.dev/research/2024/dora-report/)

---

*This is a living document. Principles evolve as understanding deepens.*
