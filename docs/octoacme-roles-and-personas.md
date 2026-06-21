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

## Engineering Lead

### Role Summary
Engineering Leads provide technical ownership and strategic guidance for a project or area. They mentor developers, make architecture decisions, and ensure code quality and test coverage standards are met.

### Responsibilities
- Own technical architecture and design decisions
- Mentor and coordinate engineering work
- Ensure code quality and test coverage standards
- Identify and escalate technical risks
- Collaborate on capacity planning and resource allocation
- Review technical documentation and design proposals

### Goals
- Deliver scalable, maintainable technical solutions
- Build and mentor high-performing engineering teams
- Reduce technical debt and improve system reliability
- Accelerate time-to-market for features

### Typical Communication
- Technical design reviews and architecture discussions
- Code review guidance and mentoring
- Weekly sync with PM/PdM on scope and priorities
- Risk escalation to Project Manager
- Cross-team technical coordination

### Key Interactions
- **With Project Manager & Product Manager**: Aligns on scope, priorities, and technical feasibility
- **With Developers**: Provides technical guidance, code reviews, and mentoring
- **With QA/Testing**: Defines quality standards and test strategies
- **With Release Engineer**: Coordinates deployment strategies and infrastructure needs
- **With Security Liaison**: Ensures security best practices are integrated into design

---

## UX Lead

### Role Summary
UX Leads drive user-centered design and ensure products are intuitive, accessible, and delightful. They conduct research, create designs, and validate solutions with users and stakeholders.

### Responsibilities
- Conduct user research and gather requirements
- Create wireframes, prototypes, and design specifications
- Ensure accessibility standards and usability best practices
- Validate designs through user testing and feedback
- Guide developers and QA on design intent and edge cases
- Maintain design systems and style guides

### Goals
- Create products that meet user needs and exceed expectations
- Reduce support burden through intuitive design
- Build strong, consistent brand experiences
- Improve conversion and user satisfaction metrics

### Typical Communication
- Design reviews with product and engineering
- User research findings and recommendations
- Design specifications and interaction guidelines
- Accessibility compliance documentation

### Key Interactions
- **With Product Manager**: Aligns on user needs and feature priorities
- **With Developers**: Provides design specs and reviews implementations
- **With QA/Testing**: Defines acceptance criteria for usability and accessibility
- **With Support Lead**: Gathers feedback on user pain points and documentation needs

---

## Release Engineer / DevOps

### Role Summary
Release Engineers / DevOps specialists manage CI/CD pipelines, automate deployment processes, and maintain infrastructure for reliable, repeatable releases. They own runbooks, rollback strategies, and deployment observability.

### Responsibilities
- Design, build, and maintain CI/CD pipelines
- Automate testing, building, and deployment processes
- Manage staging and production environments
- Create and maintain deployment runbooks
- Plan and execute rollback strategies
- Monitor deployment health and post-deploy metrics
- Collaborate on infrastructure scaling and reliability

### Goals
- Enable fast, safe, and reliable deployments
- Minimize deployment-related incidents and rollbacks
- Reduce manual effort and human error in releases
- Improve observability and incident response

### Typical Communication
- Deployment runbooks and procedures
- Infrastructure and capacity planning
- Incident response coordination
- CI/CD configuration and optimization guidance

### Key Interactions
- **With Engineering Lead**: Coordinates technical infrastructure needs and deployment strategies
- **With QA/Testing**: Ensures automated tests are integrated into CI/CD pipeline
- **With Security Liaison**: Implements security scanning and compliance checks in pipelines
- **With Support Lead**: Coordinates rollback and incident response procedures
- **With Project Manager**: Tracks deployment schedule and blockers

---

## Security Liaison

### Role Summary
Security Liaisons embed security practices into project workflows. They identify security requirements, conduct threat modeling, ensure compliance, and help teams follow security best practices.

### Responsibilities
- Identify security requirements early in planning
- Conduct threat modeling and security design reviews
- Coordinate security scanning and penetration testing
- Ensure compliance with organizational and regulatory standards
- Mentor teams on secure coding and configuration practices
- Flag security risks and escalate to Risk Register
- Participate in incident response for security events

### Goals
- Prevent security vulnerabilities and data breaches
- Embed security as a core project value
- Maintain compliance with regulatory and organizational standards
- Reduce security incident response time

### Typical Communication
- Security requirements and threat models
- Compliance and audit documentation
- Security scanning results and remediation guidance
- Risk escalation and incident notifications

### Key Interactions
- **With Engineering Lead**: Integrates security into technical design and code reviews
- **With Release Engineer**: Ensures security scanning in CI/CD pipelines
- **With Project Manager**: Escalates security risks and dependencies
- **With Developers**: Provides secure coding guidance and code review feedback
- **With Support Lead**: Handles security-related incidents and post-incident reviews

---

## Support Lead / On-call Coordinator

### Role Summary
Support Leads manage production incidents, triage escalations, and maintain operational runbooks. They coordinate incident response, capture post-incident learnings, and improve system observability and documentation.

### Responsibilities
- Triage and escalate production issues
- Coordinate incident response and communication
- Manage on-call rotations and escalation paths
- Create and maintain incident runbooks
- Capture incident details for post-incident reviews
- Identify systemic issues and feed back to product/engineering
- Improve alerting, monitoring, and documentation

### Goals
- Minimize incident impact and time-to-resolution
- Reduce repeat incidents through root cause analysis
- Improve system observability and runbook clarity
- Build customer trust through responsive support

### Typical Communication
- Incident notifications and status updates
- Post-incident reports and action items
- On-call procedures and escalation paths
- Support documentation and FAQs

### Key Interactions
- **With Developers & Engineering Lead**: Debugs issues, coordinates fixes
- **With Release Engineer**: Coordinates rollbacks and emergency deployments
- **With Project Manager**: Escalates systemic issues and blockers
- **With Technical Writer**: Updates runbooks and documentation
- **With Data Analyst**: Tracks incident metrics and trends

---

## Data Analyst

### Role Summary
Data Analysts define success metrics, build dashboards, and provide data-driven insights. They work with product and project teams to validate decisions and measure business and technical impact.

### Responsibilities
- Define and track success metrics aligned with business goals
- Build dashboards and reporting tools for key signals
- Validate data quality and integrity
- Analyze product and technical performance
- Identify trends and opportunities for improvement
- Create insights and recommendations for decision-making
- Establish baselines and track progress toward goals

### Goals
- Enable data-driven decision-making across teams
- Measure and demonstrate project impact
- Identify performance bottlenecks and opportunities
- Support continuous improvement through evidence

### Typical Communication
- Dashboards and metric definitions
- Data analysis reports and insights
- Weekly metrics reviews and trend discussions
- Success metric validation and reporting

### Key Interactions
- **With Product Manager**: Defines success metrics and measures feature impact
- **With Project Manager**: Tracks project KPIs and business metrics
- **With Developers**: Ensures proper instrumentation and logging
- **With Release Engineer**: Monitors deployment and system health metrics
- **With Support Lead**: Analyzes incident trends and customer impact

---

## Technical Writer

### Role Summary
Technical Writers maintain process documentation, create release notes, and produce onboarding materials. They ensure knowledge is discoverable, current, and accessible to all team members.

### Responsibilities
- Write and maintain process documentation in `docs/`
- Create and update release notes and changelog entries
- Develop onboarding guides and runbooks
- Ensure documentation accuracy and completeness
- Coordinate with teams to capture decisions and rationale
- Version and archive documentation for historical reference
- Improve documentation discoverability and search

### Goals
- Reduce onboarding time and tribal knowledge dependency
- Enable consistent, repeatable processes
- Improve knowledge accessibility and retention
- Accelerate problem-solving through clear documentation

### Typical Communication
- Process documentation and templates
- Release notes and announcements
- Onboarding guides and runbooks
- Documentation updates and change logs

### Key Interactions
- **With Project Manager**: Captures project decisions and risk logs
- **With Engineering Lead & Developers**: Documents technical architecture and design decisions
- **With Product Manager**: Captures feature specs and acceptance criteria
- **With Support Lead**: Documents incident runbooks and FAQs
- **With All Roles**: Gathers inputs for role-specific guidance and best practices

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference role responsibilities when assigning tasks or clarifying ownership in project work.
- Use interactions to understand dependencies and coordination points across the team.
