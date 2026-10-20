# Cybersecurity Development Roadmap

> **Mission:** Build practical cybersecurity skills, publish reproducible technical work, and align professional development with real-world security engineering requirements.

**Focus areas:** AI & Agent Security · Application Security · Security Engineering · Threat Intelligence / OSINT · Security Solutions Engineering

**Status:** Active learning and portfolio development  
**Current cycle:** 90-day roadmap  
**Progress updates:** Weekly

---

## How this repository works

This public repository is a record of **completed work and safe-to-share learning**. Check tasks off by changing `- [ ]` to `- [x]` in GitHub's Markdown editor and committing the change.

**Privacy boundary:** Detailed employer reconnaissance, job application records, compensation notes, personal skills assessments, private contact details, credentials, and sensitive investigation data belong in the **separate private repository**. Do not commit secrets or personal data here, including in Git history.

### Current priorities

- [X] Establish a repeatable weekly learning and research routine
- [ ] Publish the first four technical reading summaries
- [ ] Complete three job-description analyses **in the private repository**
- [ ] Identify recurring employer-requested technical skills and publish only aggregated, sanitized takeaways
- [ ] Build and document the first controlled AI-agent security lab
- [ ] Publish a reproducible security test report with findings and mitigations

---

## Weekly mission checklist

Copy this section into `progress/YYYY-WW.md` each week, then reset the boxes here for the next cycle.

### Read: 4–5 technical resources

- [ ] Read #1: AI application / agent security
- [ ] Read #2: Security engineering / detection
- [ ] Read #3: Application, API, or identity security
- [ ] Read #4: Threat intelligence / OSINT
- [ ] Read #5 (optional): Topic selected from emerging job-skill gaps
- [ ] Write at least **two** short, source-linked technical takeaways

### Recon: 3 job descriptions (private)

- [ ] Investigate job #1: AI Security Engineer / AI Red Team
- [ ] Investigate job #2: Security Engineer / Application Security
- [ ] Investigate job #3: Security Solutions Engineer
- [ ] Record tools, languages, platforms, responsibilities, and required experience
- [ ] Separate **mandatory requirements** from preferred qualifications
- [ ] Compare requirements with demonstrated skills and identify the top three gaps
- [ ] Add aggregated, non-sensitive skill trends to the public monthly summary

### Build: practical work

- [ ] Complete one hands-on lab or meaningful project milestone
- [ ] Save reproducible setup instructions and sanitized evidence
- [ ] Document one problem, the troubleshooting process, and the solution
- [ ] Commit and push reviewed, safe-to-publish changes

### Review: weekly retrospective

- [ ] Identify the most frequently requested skill from the week's job research
- [ ] Choose next week's technical learning objective
- [ ] Update project progress and note any blockers
- [ ] Archive this week's checklist under `progress/`

---

## 90-day development roadmap

### Days 1–30 | Baseline and foundations

- [ ] Establish the public/private repository boundaries
- [ ] Create the `reading/`, `labs/`, `projects/`, `progress/`, and `reports/` folders
- [ ] Review 12 job descriptions privately (3 per week)
- [ ] Read 16–20 technical resources
- [ ] Identify the five most common relevant technical requirements
- [ ] Study OWASP Top 10 for LLM Applications and OWASP Agentic AI guidance
- [ ] Review MITRE ATLAS and the NIST AI Risk Management Framework
- [ ] Define a safe, local AI-agent security test environment
- [ ] Publish one introductory lab write-up

### Days 31–60 | Build and evaluate

- [ ] Review 12 additional job descriptions privately
- [ ] Read 16–20 additional technical resources
- [ ] Implement a deliberately limited test agent using synthetic data
- [ ] Create a prompt-injection evaluation scenario
- [ ] Create an excessive-permissions / unsafe-tool-use scenario
- [ ] Implement authorization checks, tool allowlists, and approval gates
- [ ] Record baseline results and post-mitigation results
- [ ] Publish a reproducible technical walkthrough

### Days 61–90 | Validate and publish

- [ ] Review 12 additional job descriptions privately
- [ ] Read 16–20 additional technical resources
- [ ] Produce a structured security findings report
- [ ] Document test limitations, false positives, and mitigations
- [ ] Complete three public portfolio deliverables in total
- [ ] Publish a sanitized skills-demand summary based on researched roles
- [ ] Compare progress against actual employer requirements
- [ ] Set the next 90-day technical focus

---

## Featured project: Agent Security Testbench

**Goal:** Create a controlled environment for evaluating security failures in LLM-powered agents, without interacting with real accounts, production services, or third-party systems.

### Phase 1: Design

- [ ] Define scope, assumptions, threat model, and lab safety boundaries
- [ ] Select a model/runtime and document hardware requirements
- [ ] Create a mock tool interface and synthetic dataset
- [ ] Define expected authorized behavior and measurable test outcomes

### Phase 2: Test

- [ ] Test direct and indirect prompt-injection resistance
- [ ] Test whether untrusted retrieved content can influence tool actions
- [ ] Test least-privilege boundaries and unauthorized tool requests
- [ ] Test handling of sensitive-looking **synthetic** data
- [ ] Record reproducible steps and observed outcomes

### Phase 3: Harden

- [ ] Add input/output validation where appropriate
- [ ] Add explicit tool authorization and scoped permissions
- [ ] Add human approval for high-impact actions
- [ ] Add logging and security test assertions
- [ ] Re-run tests and compare results

### Phase 4: Publish

- [ ] Publish setup and usage instructions
- [ ] Publish sanitized test cases and evidence
- [ ] Publish security findings and limitations
- [ ] Link the project from this README

---

## Public deliverables

| Deliverable | Status | Link |
| --- | --- | --- |
| Technical reading summaries | ⬜ Planned | `reading/` |
| AI-agent security lab | ⬜ Planned | `projects/agent-security-testbench/` |
| Application/API security lab | ⬜ Planned | `labs/` |
| Threat intelligence / OSINT methodology write-up | ⬜ Planned | `labs/` |
| Sanitized job-market skills analysis | ⬜ Planned | `reports/` |
| 90-day progress retrospective | ⬜ Planned | `reports/` |

## Suggested repository layout

```text
.
├── README.md
├── reading/                 # Source-linked learning summaries
├── labs/                    # Safe, reproducible exercises
├── projects/
│   └── agent-security-testbench/
├── progress/                # Weekly checklist snapshots
└── reports/                 # Sanitized findings and retrospectives
```

## Research and documentation standards

- Cite original sources and record access/publication dates when available.
- Clearly distinguish observed results, assumptions, and opinions.
- Use synthetic or expressly authorized test data only.
- Avoid publishing exploit details that expose live systems or private individuals.
- Document versions, commands, expected outcomes, and known limitations.
- Do not present a completed tutorial or project as proof of professional employment experience.

## Reference starting points

- [OWASP GenAI Security Project](https://genai.owasp.org/)
- [MITRE ATLAS](https://atlas.mitre.org/)
- [NIST AI Risk Management Framework](https://www.nist.gov/itl/ai-risk-management-framework)
- [OWASP Web Security Testing Guide](https://owasp.org/www-project-web-security-testing-guide/)

---

**Guiding principle:** Read with purpose. Investigate employer needs. Build practical evidence. Publish responsibly. Repeat.
