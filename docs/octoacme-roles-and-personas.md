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

## UX/UI Designer

### Role Summary
UX/UI Designers define the user experience and visual interface, ensuring the product is intuitive, accessible, and delightful to use. They collaborate with Product Managers, Developers, and stakeholders to translate requirements into user-centered designs.

### Responsibilities
- Create wireframes, mockups, and interactive prototypes
- Conduct user research and usability testing
- Define information architecture and user flows
- Establish and maintain design systems and style guides
- Validate designs against accessibility standards (WCAG, etc.)

### Goals
- Deliver intuitive, accessible user experiences
- Reduce user friction and support tasks
- Ensure design consistency across features

### Typical Communication
- Design reviews with Product Managers and Developers
- Weekly syncs during planning and execution phases
- Prototypes and annotated mockups in design tools
- Usability test findings and recommendations

### Collaboration
- **Developers**: Provide implementation-ready specs, review UI code, support responsive/accessibility testing
- **Product Managers**: Align on user needs, validate designs against acceptance criteria
- **Project Managers**: Flag design dependencies early, clarify timelines for design iterations

---

## Technical Writer

### Role Summary
Technical Writers create and maintain clear, accurate documentation for users, developers, and internal teams. They ensure documentation is up-to-date, discoverable, and aligned with product releases.

### Responsibilities
- Write user guides, API docs, and onboarding materials
- Maintain knowledge bases and help content
- Collaborate with engineering to document features and changes
- Ensure documentation adheres to style guides and standards
- Gather feedback to improve doc quality and coverage

### Goals
- Make features discoverable and easy to understand
- Reduce support burden through self-service documentation
- Keep docs accurate and consistent with product changes

### Typical Communication
- Docs review meetings with Developers and Product Managers
- Release planning to align doc updates with deployments
- Feedback loops with support and customer success teams
- Style guide updates and doc tooling discussions

### Collaboration
- **Developers**: Gather technical details, validate accuracy, coordinate doc reviews
- **Product Managers**: Understand feature goals and user stories, prioritize doc work
- **Project Managers**: Track doc milestones, flag docs as release dependencies

---

## DevOps/Release Engineer

### Role Summary
DevOps/Release Engineers build and maintain CI/CD pipelines, deployment automation, and release processes. They enable fast, reliable, and safe delivery of software to production.

### Responsibilities
- Design and maintain build, test, and deployment pipelines
- Manage release schedules and coordinate deployments
- Monitor system health, performance, and rollback procedures
- Ensure infrastructure security and compliance
- Support developers with tooling and environment issues

### Goals
- Minimize deployment risk and downtime
- Reduce cycle time from commit to production
- Maintain high availability and reliability

### Typical Communication
- Release planning and go/no-go meetings
- Incident reviews and post-mortems
- Standups for release coordination during critical windows
- Infrastructure and tooling discussions with Developers

### Collaboration
- **Developers**: Provide CI/CD support, review deployment configs, troubleshoot builds
- **Product Managers**: Align on release timing and rollout strategy
- **Project Managers**: Report on release readiness, flag dependencies and risks

---

## Support Lead / Customer Success

### Role Summary
Support Leads and Customer Success professionals are the voice of the customer. They handle escalations, track recurring issues, and advocate for improvements based on customer feedback and usage patterns.

### Responsibilities
- Manage customer inquiries, bug reports, and escalations
- Track and triage recurring issues or feature requests
- Provide feedback to Product and Engineering on usability gaps
- Coordinate customer onboarding and success planning
- Document support workflows and runbooks

### Goals
- Improve customer satisfaction and retention
- Reduce time-to-resolution for issues
- Surface actionable product insights from support trends

### Typical Communication
- Weekly triage meetings with Product Managers and Developers
- Escalation handoffs and incident coordination
- Monthly trend reports on top customer issues
- Runbook and knowledge base contributions

### Collaboration
- **Developers**: Escalate bugs with repro steps, validate fixes in staging
- **Product Managers**: Provide customer feedback, prioritize pain points
- **Project Managers**: Identify support dependencies for releases, coordinate communication plans

---

## When to Involve These Roles

Engaging the right roles at the right time reduces rework, improves quality, and prevents costly late-stage surprises. Use this checklist to identify when to involve each role:

### Initiation & Planning
- **UX/UI Designer**: Involve early for user research and wireframes before engineering estimates
- **Technical Writer**: Bring in during planning to identify doc scope and align on release notes
- **DevOps/Release Engineer**: Engage to review infrastructure needs, deployment strategy, and rollback plans
- **Support Lead**: Include in planning to surface known customer pain points and set support readiness expectations

### Execution
- **UX/UI Designer**: Conduct design reviews before and during implementation; validate prototypes with users
- **Technical Writer**: Draft docs in parallel with code to ensure accuracy and completeness
- **DevOps/Release Engineer**: Support CI/CD setup, deployment testing, and environment configuration
- **Support Lead**: Review upcoming changes that may generate inquiries; prepare runbooks

### Release & Deployment
- **UX/UI Designer**: Validate final UI against designs; flag accessibility or UX issues pre-launch
- **Technical Writer**: Publish updated docs; ensure help content is live before release
- **DevOps/Release Engineer**: Execute and monitor deployment; coordinate rollback if needed
- **Support Lead**: Brief support team on changes; monitor initial feedback and escalations

### Retrospective
- **All roles**: Participate in retrospectives to capture cross-functional learnings and improve handoffs

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See `octoacme-role-engagement-checklist.md` for a lightweight template to ensure timely role engagement across project phases.

