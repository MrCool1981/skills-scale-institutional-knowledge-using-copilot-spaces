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

## Release Manager

### Role Summary
Coordinates release planning and execution, ensuring deployments are scheduled, communicated, and validated across teams.

### Responsibilities
- Plan and coordinate release windows and cutoffs
- Maintain release calendar and stakeholder notifications
- Verify release readiness (PRs, CI, feature flags)
- Coordinate rollbacks and mitigation plans if needed
- Lead post-release verification and retrospectives

### Goals
- Reduce deployment risk and incidents
- Ensure reliable, predictable releases
- Improve cross-team coordination for releases

### Typical Communication
- Weekly release-planning syncs and pre-release check-ins
- Release announcements and post-release summaries

### Interactions
- With PM/PdM: align release scope and timeline; confirm business priorities
- With Developers/Platform: ensure migrations and pipeline readiness
- With QA: confirm test coverage and regression sign-off
- With Support/Stakeholders: coordinate communications and support plans

---

## User Experience (UX) Lead

### Role Summary
Drives UX strategy, ensures usability and accessibility, and integrates user feedback into design and product decisions.

### Responsibilities
- Lead UX design, research, and usability testing
- Define UX acceptance criteria and design tokens/patterns
- Maintain design system assets and guidelines
- Conduct design reviews and provide feedback to engineering
- Champion accessibility and user-centered design

### Goals
- Improve product usability and user satisfaction
- Reduce rework due to UX issues
- Ensure consistent product experience

### Typical Communication
- Design reviews, research reports, and design system updates

### Interactions
- With PdM: translate product goals into UX outcomes and priorities
- With Developers: hand off designs, clarify interactions, and review implementations
- With QA: validate UX acceptance criteria and test cases
- With Stakeholders: present user research and usability trade-offs

---

## Technical Writer

### Role Summary
Owns documentation quality for product and process artifacts, ensuring accurate, discoverable, and versioned documentation.

### Responsibilities
- Maintain process and product documentation in docs/
- Create release notes, onboarding guides, and runbooks
- Review docs PRs for clarity, consistency, and required metadata
- Coordinate documentation reviews and copy edits
- Support onboarding with focused learning materials

### Goals
- Make knowledge discoverable and reduce single-person dependence
- Keep docs current and actionable
- Increase new-hire ramp speed and reduce support friction

### Typical Communication
- Doc review requests, content sprints, and release-note coordination

### Interactions
- With PM/PdM: clarify feature intent and acceptance criteria for docs
- With Developers: gather implementation details and verify technical accuracy
- With QA: include test steps and verification docs where relevant
- With Support: align on FAQs, troubleshooting steps, and escalation paths

---

## QA Automation Engineer

### Role Summary
Designs and maintains automated test frameworks and suites to improve product quality and provide faster feedback loops.

### Responsibilities
- Build and maintain CI test suites and regression automation
- Define test coverage goals and flaky-test remediation
- Integrate tests into the release pipeline and PR checks
- Collaborate on test data and environment management
- Support root-cause analysis of test failures and production issues

### Goals
- Increase confidence in releases through automation
- Reduce manual regression effort
- Provide fast feedback to developers via CI

### Typical Communication
- Test reports, CI status, and regression summaries

### Interactions
- With Developers: co-design testability and create maintainable tests
- With Release Manager: provide pre-release regression status
- With PM/PdM: help define acceptance criteria that are testable
- With Platform/DevOps: coordinate test environment availability

---

## Customer Support Liaison

### Role Summary
Acts as the bridge between customer support and the product/delivery teams, ensuring customer-reported issues and trends inform product decisions.

### Responsibilities
- Triage and document customer-reported issues and patterns
- Prepare support playbooks and escalation notes for releases
- Communicate priority issues back to PM/PdM and engineering
- Maintain support-facing KB and runbooks for new features
- Participate in post-release monitoring and debriefs

### Goals
- Reduce time-to-resolution for customer issues
- Improve product decisions through frontline insights
- Ensure support readiness for releases

### Typical Communication
- Support incident summaries, KB updates, and escalation alerts

### Interactions
- With PM/PdM: relay customer impact and feature requests
- With Developers: provide reproduction details and logs
- With Technical Writer: update KB and public docs
- With Release Manager: ensure support staffing and communication plans

---

## Platform / DevOps Engineer

### Role Summary
Maintains the platform, CI/CD pipelines, and operational infrastructure to support reliable delivery and observability.

### Responsibilities
- Maintain CI/CD pipelines and deployment automation
- Manage infrastructure and runbooks for platform services
- Instrument monitoring and alerting for production systems
- Support platform-related incident response and postmortems
- Collaborate on performance, scalability, and security improvements

### Goals
- Ensure platform stability and fast, safe deploys
- Automate repetitive operational tasks
- Provide clear observability and incident context

### Typical Communication
- Operational runbooks, incident posts, and platform change notes

### Interactions
- With Developers: enable self-service deployment, advise on platform constraints
- With Release Manager: confirm pipeline readiness and rollback options
- With QA Automation: provide test environments and CI resources
- With PM/PdM: advise on operational impacts of scope decisions

---

## How to use these personas
- Use these persona definitions to frame scenarios and sample interactions across OctoAcme projects and the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference this document from project charters or planning docs to clarify who owns what on a given engagement.

