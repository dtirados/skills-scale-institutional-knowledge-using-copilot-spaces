# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Participation model for additional personas

These personas are added based on project size, complexity, and risk. Developers, Product Managers, and Project Managers remain the core delivery roles. The personas below clarify ownership for specialized decisions, artifacts, and handoffs when the work needs them.

- **Typically required for medium-to-high complexity work:** Technical Lead or Architect, QA/Test Lead
- **Required when business approval, funding, or escalations are material:** Executive Sponsor
- **Required when requirements, workflows, or stakeholder inputs need structured discovery:** Business Analyst
- **Required when usability, accessibility, or user research meaningfully affect outcomes:** UX/UI Designer or Researcher
- **Required when release coordination, environments, deployment automation, or operational readiness are non-trivial:** Release Manager or DevOps/Platform Engineer
- **Required when security, privacy, compliance, or sensitive data risks are present:** Security/Privacy Representative
- **Required when customer impact, support readiness, service operations, or post-release monitoring are important to success:** Customer/Support or Operations Representative
- **Optional for small, low-risk efforts:** Some responsibilities may be combined into existing PM, PdM, or Developer roles if ownership remains explicit in the project one-pager, backlog, risk register, and release plan

---

## Executive Sponsor

### Role Summary
The Executive Sponsor provides strategic direction, confirms business priority, and makes high-impact scope, funding, and go/no-go decisions when the team needs executive alignment.

### Responsibilities & Decision Rights
- Approve the project one-pager when business goals, success metrics, and priority are clear
- Confirm major scope changes, funding decisions, and timeline trade-offs that affect business commitments
- Resolve escalations that cannot be solved within the delivery team or weekly PM/PdM sync
- Provide direction on stakeholder expectations for major milestones, launch readiness, or incident response

### Goals
- Keep the initiative aligned with business outcomes
- Remove high-level blockers quickly
- Make timely go/no-go decisions for planning, release, or recovery actions

### Key Deliverables / Artifacts
- Sponsor approval or decision notes
- Escalation outcomes for scope, funding, or priority changes
- Major milestone or release go/no-go decisions

### Interactions with Existing Roles
- Partners with the Product Manager on business outcomes and priority
- Works with the Project Manager on escalations, milestone risk, and stakeholder communication
- Engages Developers indirectly through the Technical Lead or Project Manager when business-impacting technical trade-offs need approval

### Typical Communication & Lifecycle Touchpoints
- Initiation review of the project one-pager and stakeholder alignment
- Planning approval for major milestones or resource changes
- Execution escalations for business-impacting blockers
- Release or incident communications when sponsor-level visibility is needed

---

## Business Analyst

### Role Summary
The Business Analyst translates stakeholder needs into clear requirements, process impacts, and acceptance details so the backlog is ready for planning and execution.

### Responsibilities & Decision Rights
- Elicit business needs, constraints, and process impacts from stakeholders
- Draft or refine backlog items, workflows, and acceptance criteria with the Product Manager
- Clarify edge cases, dependencies, and non-technical assumptions before work enters execution
- Recommend requirement changes when new information affects scope or success criteria

### Goals
- Reduce ambiguity in backlog items
- Improve requirement traceability from business need to acceptance criteria
- Minimize rework caused by missing process or stakeholder inputs

### Key Deliverables / Artifacts
- Requirement notes and workflow clarifications
- Refined backlog items with clearer acceptance criteria
- Process maps or lightweight business rules when needed
- Updated stakeholder inputs for the project one-pager or risk register

### Interactions with Existing Roles
- Works with the Product Manager to refine scope and acceptance criteria
- Supports the Project Manager by surfacing dependencies, assumptions, and stakeholder decisions
- Collaborates with Developers to answer requirement questions before and during implementation

### Typical Communication & Lifecycle Touchpoints
- Initiation discovery for problem definition and stakeholder inputs
- Planning workshops to refine backlog, acceptance criteria, and dependencies
- Execution support for requirement clarifications and change impacts
- Retrospective input on requirement quality and handoff gaps

---

## UX/UI Designer or Researcher

### Role Summary
The UX/UI Designer or Researcher represents user needs through research, workflows, content, interaction design, and accessibility guidance.

### Responsibilities & Decision Rights
- Plan or synthesize user research needed to validate assumptions
- Define user flows, wireframes, prototypes, or content guidance for backlog items
- Recommend usability and accessibility improvements before build and before release
- Advise on experience trade-offs when scope or technical constraints affect the user journey

### Goals
- Ensure the solution is usable, accessible, and aligned to customer value
- Reduce rework caused by unclear user flows or late usability findings
- Validate that acceptance criteria reflect the intended user experience

### Key Deliverables / Artifacts
- Research notes or findings summaries
- Wireframes, prototypes, mockups, or journey maps
- Accessibility or usability recommendations
- Updated acceptance details for user-facing work

### Interactions with Existing Roles
- Partners with the Product Manager on customer value and success metrics
- Works with Developers to clarify feasible UX patterns and implementation constraints
- Supports the Project Manager by identifying design dependencies or review checkpoints

### Typical Communication & Lifecycle Touchpoints
- Initiation input on user problem framing
- Planning reviews for designs, content, and accessibility expectations
- Execution collaboration during demos, PR reviews for UI behavior, and acceptance checks
- Post-release feedback review with Product Manager and Support/Ops

---

## Technical Lead or Architect

### Role Summary
The Technical Lead or Architect owns technical direction, non-functional expectations, and architecture decisions that shape safe, maintainable delivery.

### Responsibilities & Decision Rights
- Define architecture direction, integration approach, and technical constraints
- Approve significant technical design decisions, especially those affecting scalability, reliability, security, or maintainability
- Identify technical risks, dependencies, and Definition of Done impacts during planning
- Guide implementation trade-offs, code review expectations, and observability needs during execution and release

### Goals
- Maintain architectural coherence across increments
- Reduce technical risk and operational surprises
- Ensure the solution meets quality, performance, and reliability expectations

### Key Deliverables / Artifacts
- Technical design notes or architecture decisions
- Non-functional requirements and integration guidance
- Technical risk inputs for the risk register
- Readiness guidance for observability, rollout, and rollback

### Interactions with Existing Roles
- Works with Developers on design reviews, implementation approach, and code quality
- Partners with the Product Manager on scope trade-offs influenced by technical complexity
- Supports the Project Manager with risk visibility, dependency management, and milestone feasibility

### Typical Communication & Lifecycle Touchpoints
- Initiation feasibility input for the proposed team and rough effort estimate
- Planning design reviews, dependency mapping, and Definition of Done alignment
- Execution support through standups, design reviews, and blocker triage
- Release readiness checks with QA, Security, and Release/DevOps

---

## QA/Test Lead

### Role Summary
The QA/Test Lead defines the test strategy and coordinates validation so the team can prove acceptance criteria, quality expectations, and Definition of Done have been met.

### Responsibilities & Decision Rights
- Define the initial test plan / QA approach and recommend quality gates
- Coordinate validation coverage across unit, integration, manual QA, and smoke tests as applicable
- Report quality risks, defects, and exit criteria status before release
- Recommend whether a feature is ready to move from QA to Done or needs additional fixes

### Goals
- Make quality risks visible early
- Ensure acceptance criteria and critical flows are testable and verified
- Reduce escaped defects and release instability

### Key Deliverables / Artifacts
- Initial test plan / QA approach
- Test cases, validation notes, or defect summaries
- QA readiness and exit criteria updates
- Inputs to release readiness and retrospective action items

### Interactions with Existing Roles
- Works with Developers to make features testable and to triage defects efficiently
- Aligns with the Product Manager on acceptance validation and Definition of Done expectations
- Keeps the Project Manager informed on quality risk, blockers, and testing progress

### Typical Communication & Lifecycle Touchpoints
- Planning definition of test strategy and acceptance validation
- Execution handoff into QA, defect triage, and demo readiness
- Release smoke test readiness and post-deploy verification input
- Retrospective discussion of defect trends and test coverage gaps

---

## Release Manager or DevOps/Platform Engineer

### Role Summary
The Release Manager or DevOps/Platform Engineer coordinates release readiness, deployment automation, environment health, observability, and rollback planning.

### Responsibilities & Decision Rights
- Define or confirm release steps, deployment windows, and environment requirements
- Recommend readiness for staging and production deployment based on CI, automation, and operational checks
- Maintain or advise on deployment automation, observability, and rollback / mitigation planning
- Coordinate post-deploy verifications and release announcements with stakeholders and support teams

### Goals
- Reduce deployment risk and manual coordination gaps
- Improve repeatability, observability, and rollback readiness
- Ensure releases are operationally supportable

### Key Deliverables / Artifacts
- Release plan inputs and deployment checklist updates
- Deployment automation or environment readiness guidance
- Rollback / mitigation plan
- Release notes contributions and post-deploy verification results

### Interactions with Existing Roles
- Works with Developers and the Technical Lead on deployment requirements, observability, and environment dependencies
- Coordinates with the Project Manager on release milestones and stakeholder timing
- Aligns with the Product Manager on release scope and communications expectations

### Typical Communication & Lifecycle Touchpoints
- Planning release timeline and milestone map input
- Execution updates for CI, environments, and operational blockers
- Release coordination for staging, production, smoke tests, and stakeholder announcements
- Post-release review of telemetry, incidents, or rollback learnings

---

## Security/Privacy Representative

### Role Summary
The Security/Privacy Representative advises on security, privacy, compliance, and sensitive data risks so controls are addressed before release.

### Responsibilities & Decision Rights
- Review architecture, data handling, and workflow changes for security or privacy risk
- Recommend required controls, scans, approvals, or mitigations based on project risk
- Escalate unresolved security or privacy concerns that could block release or require incident handling
- Advise on compliance-sensitive decisions such as data access, retention, or audit needs

### Goals
- Reduce security and privacy exposure
- Ensure identified risks have owners and mitigation plans
- Prevent late-stage security surprises during release

### Key Deliverables / Artifacts
- Security or privacy review notes
- Control recommendations and mitigation actions
- Risk register updates for security-sensitive items
- Release sign-off guidance or open-risk decisions when needed

### Interactions with Existing Roles
- Partners with the Technical Lead and Developers on secure design and implementation constraints
- Supports the Project Manager with risk escalation and communication needs
- Aligns with the Product Manager when compliance or privacy constraints affect scope or timeline

### Typical Communication & Lifecycle Touchpoints
- Initiation screening for sensitive data or compliance exposure
- Planning review of risks, controls, and required approvals
- Execution follow-up on findings, test evidence, or incident concerns
- Release checkpoint for open risks, security scans, and mitigation status

---

## Customer/Support or Operations Representative

### Role Summary
The Customer/Support or Operations Representative brings frontline operational context into planning, validates support readiness, and helps monitor customer impact after release.

### Responsibilities & Decision Rights
- Provide recurring customer pain points, operational constraints, and service readiness needs
- Recommend support documentation, training, runbooks, or operational checklists needed before release
- Surface adoption, incident, or usability signals after deployment
- Advise on customer communication timing when releases affect workflows, service quality, or support volume

### Goals
- Improve launch readiness for the people who support or operate the solution
- Reduce avoidable support escalations and operational friction
- Feed customer and production insights back into prioritization and retrospectives

### Key Deliverables / Artifacts
- Support readiness notes or operational checklists
- Runbook, FAQ, or training content inputs
- Post-release feedback summaries and operational observations
- Incident or adoption insights for backlog refinement

### Interactions with Existing Roles
- Partners with the Product Manager on customer feedback and release messaging
- Works with the Project Manager on stakeholder communication and readiness checkpoints
- Collaborates with Developers when supportability, monitoring, or operational constraints affect implementation choices

### Typical Communication & Lifecycle Touchpoints
- Initiation or planning input when service impacts are expected
- Execution readiness reviews for documentation, training, and known issues
- Release communications and post-deploy verification support
- Retrospective feedback on customer impact, incidents, and improvement opportunities

---

## Lifecycle handoffs and collaboration points

- **Initiation -> Planning:** Executive Sponsor confirms priority when needed; Product Manager and Business Analyst refine the problem statement, success metrics, and stakeholder inputs into a project one-pager; Technical Lead adds feasibility and rough effort guidance; Project Manager turns the approved one-pager into kickoff, timeline, and initial risk list.
- **Planning -> Execution:** Product Manager, Business Analyst, and UX/UI finalize backlog items and acceptance criteria; Technical Lead clarifies design and dependencies; QA/Test Lead defines the initial test plan / QA approach; Project Manager records milestones, owners, and risks before work moves into the board workflow.
- **Execution -> QA:** Developers hand off features with tests, acceptance context, and known constraints; QA/Test Lead validates against the Definition of Done; Technical Lead and Security/Privacy Representative resolve defects or control gaps that affect release readiness.
- **QA -> Release:** QA/Test Lead reports exit status and critical defects; Release Manager or DevOps/Platform Engineer confirms CI, environments, smoke tests, observability, and rollback / mitigation plans; Project Manager coordinates the final go/no-go discussion with Product Manager and Executive Sponsor when the release is high impact.
- **Release -> Retrospective:** Release, Support/Ops, Product Manager, and Project Manager share post-deploy verification, incident, adoption, and stakeholder feedback; the team converts findings into retrospective action items, backlog updates, and risk register improvements.

## Collaboration matrix

| Lifecycle area | Lead / decision roles | Key collaborators | Primary artifacts / handoff |
| --- | --- | --- | --- |
| Initiation | Product Manager, Project Manager, Executive Sponsor (when needed) | Business Analyst, Technical Lead, Support/Ops | Project one-pager, stakeholder list & communication plan, initial risk list |
| Planning | Product Manager, Project Manager, Technical Lead | Business Analyst, UX/UI, QA/Test Lead, Security/Privacy, Release/DevOps | Prioritized backlog, acceptance criteria, Definition of Done, release timeline, risk register |
| Execution | Developers, Technical Lead | Product Manager, Project Manager, Business Analyst, UX/UI | Project board updates, PRs, design clarifications, weekly status updates |
| Quality / Testing | QA/Test Lead | Developers, Product Manager, Technical Lead, Security/Privacy | Initial test plan / QA approach, defect triage, acceptance validation, exit status |
| Release | Release Manager or DevOps/Platform Engineer, Project Manager | QA/Test Lead, Developers, Technical Lead, Product Manager, Security/Privacy, Support/Ops, Executive Sponsor (for high-impact go/no-go) | Deployment checklist, release notes, rollback / mitigation plan, post-deploy verifications |
| Risk management | Project Manager, Technical Lead, Security/Privacy | Product Manager, QA/Test Lead, Executive Sponsor | Risk register, mitigation plans, escalation notes |
| Stakeholder communication | Project Manager, Product Manager, Executive Sponsor (for major escalations) | Support/Ops, Business Analyst, Release/DevOps | Weekly status template, milestone updates, release announcements, incident communication |
| Retrospectives / continuous improvement | Project Manager, Product Manager | Developers, QA/Test Lead, Support/Ops, Technical Lead, Release/DevOps | Retrospective notes, action items, backlog follow-up, process improvements |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Tailor participation to the smallest role set that still covers business, delivery, quality, release, security, and operational risk for the project.
