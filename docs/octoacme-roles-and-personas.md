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

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Additional Personas

The following personas are commonly involved in cross-functional delivery. Add concise entries here to clarify responsibilities, ownership, and handoffs.

### Technical Program Manager (TPM)

Role summary
- Owns cross-team technical coordination for complex initiatives, dependency tracking, and technical roadmap alignment.

Responsibilities
- Coordinate cross-team schedules and integration points
- Track and communicate technical dependencies and risks
- Drive end-to-end technical delivery plans for multi-team work
- Facilitate architecture and design discussions where needed

Typical interactions
- Works closely with Product Managers to align on timelines and priorities
- Partners with Developers and Engineering Leads to decompose work
- Collaborates with Project Managers on scheduling and risk mitigation
- Coordinates with Release Engineers on deployment sequencing

Example artifacts
- Cross-team dependency map, integration checklist, technical program roadmap

---

### UX Researcher / Designer Representative

Role summary
- Ensures user research, usability, and accessibility are represented in product decisions and acceptance criteria.

Responsibilities
- Conduct or synthesize user research and usability testing
- Define UX acceptance criteria and accessibility requirements
- Provide design guidance and review implementation for fidelity

Typical interactions
- Works with Product Managers to translate user insights into requirements
- Partners with Developers and QA to validate UX and accessibility in implementation
- Advises Project Managers on user-facing rollout considerations

Example artifacts
- Research summaries, usability test reports, accessibility checklists, design specs

---

### Security / Privacy Engineer

Role summary
- Reviews designs and implementations for security and privacy risks and ensures compliance with relevant policies.

Responsibilities
- Perform threat modeling and security reviews for features
- Define security acceptance criteria and review PRs for compliance
- Coordinate security scanning and remediation efforts
- Advise on data handling, retention, and privacy requirements

Typical interactions
- Collaborates with Product Leads on risk and compliance trade-offs
- Works with Developers to remediate security findings
- Escalates critical issues to Security on-call or leadership as needed

Example artifacts
- Threat models, security review notes, vulnerability triage tickets, privacy impact assessments

---

### Release Engineer / Platform Lead

Role summary
- Manages CI/CD, deployment automation, and platform reliability to enable safe, repeatable releases.

Responsibilities
- Maintain and improve CI/CD pipelines and release automation
- Define rollback strategies and release playbooks
- Coordinate deployment windows and post-deploy verification
- Monitor platform health and respond to release-related incidents

Typical interactions
- Coordinates with Developers and QA for release readiness
- Works with Project Managers to schedule releases and communicate constraints
- Partners with TPMs for complex multi-service releases

Example artifacts
- Release playbooks, CI pipeline configs, rollback runbooks, deployment checklists

---

### Data Engineer / Analyst

Role summary
- Ensures telemetry, analytics, and data quality are in place so features can be measured and improved.

Responsibilities
- Define and validate instrumentation for success metrics
- Ensure data pipelines and reports provide accurate insights
- Support metric definition and analysis for experiments and releases

Typical interactions
- Works with Product Managers to define success metrics
- Collaborates with Developers to implement telemetry
- Provides analysis to PMs and stakeholders after release

Example artifacts
- Metric definitions, instrumentation specs, dashboards, analytics reports

---

### Support / Operations Lead

Role summary
- First-line owner for customer-facing issues and operational runbooks; coordinates incident response and remediation.

Responsibilities
- Triage customer-reported incidents and perform initial diagnostics
- Maintain runbooks and playbooks for common issues
- Provide feedback from support to product and engineering for improvements

Typical interactions
- Engages with Developers and Project Managers during incident triage
- Coordinates with Product Managers on customer communications and priorities
- Informs Release Engineers of operational concerns that affect rollouts

Example artifacts
- Runbooks, incident reports, support playbooks, post-incident summaries

---

### Compliance / Legal Liaison

Role summary
- Reviews changes for regulatory, contractual, and legal risk and advises product teams accordingly.

Responsibilities
- Assess features for regulatory or contractual impact
- Provide guidance on data protection, consent, and contractual obligations
- Coordinate legal reviews for launches that have compliance implications

Typical interactions
- Works with Product Leads and Security to review high-risk features
- Advises PMs on compliance-driven requirements and constraints
- Escalates findings to leadership when needed

Example artifacts
- Compliance checklists, legal review notes, contractual impact assessments

---

### Product Operations / Release Coordinator

Role summary
- Manages release communications, rollout coordination, and operational readiness tasks that support a smooth launch.

Responsibilities
- Draft and publish release notes and stakeholder communications
- Maintain release checklists and rollout plans
- Coordinate cross-functional readiness (support, docs, marketing)

Typical interactions
- Works with Product Managers and Release Engineers to schedule and announce releases
- Coordinates with Support and Ops on readiness and monitoring expectations
- Partners with Project Managers for stakeholder updates

Example artifacts
- Release notes, rollout checklists, stakeholder communication templates

---

