# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Core Roles

### Developers

#### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

#### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

#### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

#### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

#### Interaction Points
- **Technical Lead:** Receive technical guidance and design reviews
- **QA Lead:** Respond to defect reports and collaborate on test automation
- **Project Manager:** Provide estimates and flag blockers
- **Product Manager:** Clarify requirements and acceptance criteria

---

### Product Managers

#### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

#### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

#### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

#### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

#### Interaction Points
- **Project Manager:** Weekly sync on priorities and timeline
- **Stakeholders:** Align on strategy and validate success metrics
- **QA Lead:** Define acceptance criteria and quality standards
- **UX Specialist:** Collaborate on user experience and design direction

---

### Project Managers

#### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

#### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

#### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

#### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

#### Interaction Points
- **Product Manager:** Weekly sync on priorities and scope
- **Technical Lead:** Coordinate technical risks and dependencies
- **Stakeholders:** Provide status updates and escalations
- **DevOps Engineer:** Coordinate release and deployment planning

---

## Extended Roles

### QA/Testing Lead

#### Role Summary
QA/Testing Leads own the quality strategy and execution for a project. They define testing approaches, establish acceptance criteria validation processes, and ensure features meet quality standards before release.

#### Responsibilities
- Define test strategy and acceptance criteria validation approach
- Plan and execute unit, integration, and end-to-end testing
- Collaborate with developers on test automation and CI/CD integration
- Conduct manual QA and acceptance testing before release
- Triage and report quality issues with severity and impact assessment
- Participate in release planning and post-deployment verification
- Mentor team on testing best practices and quality mindset

#### Goals
- Deliver high-quality features that meet user expectations
- Identify defects early to reduce production incidents
- Maintain test coverage and automation efficiency
- Enable continuous quality improvement

#### Typical Communication
- Sprint planning and backlog refinement (quality questions)
- Daily standups (test status, blockers)
- Pre-release quality sign-off
- Post-incident retrospectives and defect reviews

#### Interaction Points
- **Developers:** Review test requirements, collaborate on automation, respond to defect reports
- **Product Manager:** Validate acceptance criteria interpretation, prioritize quality issues
- **Project Manager:** Report test status, flag quality risks, coordinate QA resources
- **Technical Lead:** Advise on test architecture and automation strategy

---

### Technical Lead/Architect

#### Role Summary
Technical Leads shape the technical direction and design of projects. They mentor engineers, conduct architecture reviews, and ensure technical decisions align with long-term strategy and quality standards.

#### Responsibilities
- Define technical architecture and design patterns
- Conduct code and design reviews
- Mentor junior engineers and coach on best practices
- Assess technical risks and propose mitigations
- Make trade-off decisions between speed, scalability, and maintainability
- Support capacity planning and technology selection
- Identify and address technical debt

#### Goals
- Deliver scalable, maintainable, and secure software
- Build and develop engineering capability across the team
- Reduce technical debt and future rework
- Enable long-term platform sustainability

#### Typical Communication
- Design reviews and architecture discussions
- Technical spike estimations and planning
- Code review comments and PR feedback
- Risk and dependency escalations

#### Interaction Points
- **Developers:** Provide technical guidance, review designs and code, remove technical blockers
- **Project Manager:** Advise on technical risks and dependencies, estimate technical complexity
- **Product Manager:** Discuss feasibility of features, inform on technical debt impact
- **DevOps Engineer:** Collaborate on infrastructure requirements and deployment strategy
- **Security Officer:** Review security implications of technical decisions

---

### Stakeholder/Sponsor

#### Role Summary
Stakeholders and Sponsors provide business context, funding, and strategic priority. They are accountable for business outcomes and have authority to make trade-off decisions and authorize scope changes.

#### Responsibilities
- Provide business context and strategic alignment
- Approve project charter, budget, and timeline
- Make business priority and scope trade-off decisions
- Escalate risks and blockers that impact business outcomes
- Provide user/market feedback and validate success metrics
- Approve major scope changes and release decisions
- Remove organizational blockers

#### Goals
- Deliver business value and measurable ROI
- Maintain stakeholder alignment and confidence
- Enable efficient decision-making and risk escalation
- Protect project resources and priorities

#### Typical Communication
- Monthly or milestone-based executive updates
- Escalation reviews for major risks or scope changes
- Go/no-go decision gates
- Post-release impact and metrics reviews

#### Interaction Points
- **Project Manager:** Receive status updates, approve decisions, provide escalation authority
- **Product Manager:** Align on strategy, provide market and user input, validate success metrics
- **Developers:** Communicate business context and priority via product and project teams

---

### Scrum Master/Agile Coach

#### Role Summary
Scrum Masters facilitate agile ceremonies, remove impediments, and coach the team on agile practices and continuous improvement. They enable self-organizing teams and maintain process discipline.

#### Responsibilities
- Facilitate daily standups, sprint planning, reviews, and retrospectives
- Identify and help resolve team impediments and blockers
- Coach team on agile principles and practices
- Maintain sprint health metrics and velocity trends
- Support Definition of Done and acceptance criteria clarity
- Remove organizational barriers to team effectiveness
- Foster psychological safety and continuous improvement culture

#### Goals
- Enable high-performing, self-organizing teams
- Maintain consistent sprint execution and predictable delivery
- Build agile maturity across the organization
- Create a culture of continuous learning and improvement

#### Typical Communication
- Daily standups (timebox and impediment focus)
- Sprint ceremonies (planning, review, retrospective)
- One-on-one coaching conversations
- Process improvement discussions

#### Interaction Points
- **Project Manager:** Collaborate on schedule and risk management, support escalation paths
- **Team Members:** Coach on agile mindset, remove blockers, facilitate collaboration
- **Stakeholders:** Communicate sprint progress and capability
- **Product Manager:** Ensure backlog clarity and prioritization discipline

---

### DevOps/Infrastructure Engineer

#### Role Summary
DevOps Engineers manage deployment pipelines, infrastructure, and operational support. They enable reliable, automated, and observable deployments while maintaining infrastructure availability and security.

#### Responsibilities
- Design and maintain CI/CD pipelines and automation
- Manage infrastructure, environments, and configuration management
- Support deployment planning and execution
- Monitor system health, performance, and availability
- Implement infrastructure-as-code and version control
- Collaborate on security, compliance, and operational requirements
- Support incident response and rollback procedures

#### Goals
- Enable fast, safe, and repeatable deployments
- Maintain high system availability and performance
- Reduce deployment risk and mean time to recovery (MTTR)
- Build reliable, scalable infrastructure

#### Typical Communication
- Release planning and deployment coordination
- Infrastructure requirements review
- Incident response and post-mortems
- Performance and availability metrics reviews

#### Interaction Points
- **Project Manager:** Coordinate release planning and deployment windows
- **Technical Lead:** Advise on infrastructure requirements and scalability
- **Developers:** Support CI/CD integration and deployment troubleshooting
- **Security Officer:** Collaborate on security infrastructure and compliance controls

---

### Security Officer/Champion

#### Role Summary
Security Officers ensure security compliance, threat assessment, and secure coding practices. They champion security throughout the project lifecycle and integrate security into development processes.

#### Responsibilities
- Define security requirements and compliance standards
- Conduct threat assessments and security reviews
- Review code and architecture for security vulnerabilities
- Establish secure coding guidelines and best practices
- Support security testing and penetration testing
- Manage security incidents and coordinate response
- Track security debt and remediation plans

#### Goals
- Protect customer data and system integrity
- Reduce security vulnerabilities and incident risk
- Enable secure-by-design development practices
- Maintain compliance with security standards and regulations

#### Typical Communication
- Security reviews and threat assessment discussions
- Code review feedback (security perspective)
- Incident response and post-mortem participation
- Security training and awareness initiatives

#### Interaction Points
- **Technical Lead:** Review architectural security decisions and trade-offs
- **Developers:** Provide secure coding guidance and security review feedback
- **DevOps Engineer:** Collaborate on infrastructure security and compliance controls
- **Project Manager:** Flag security risks and coordinate remediation planning

---

### UX/Design Specialist

#### Role Summary
UX/Design Specialists own user experience, design systems, and usability validation. They ensure features are intuitive, accessible, and delight users while maintaining design consistency.

#### Responsibilities
- Conduct user research and usability testing
- Design user interfaces and user experiences
- Maintain design systems and component libraries
- Ensure accessibility and inclusive design
- Collaborate on feature requirements and trade-offs
- Provide design feedback and usability guidance to developers
- Support design documentation and specifications

#### Goals
- Create intuitive, delightful user experiences
- Maintain design consistency and brand alignment
- Ensure accessibility for all users
- Reduce user friction and support burden

#### Typical Communication
- Design reviews and feedback sessions
- User research findings and insights
- Design specifications and component documentation
- Usability testing results and recommendations

#### Interaction Points
- **Product Manager:** Collaborate on feature direction and user value
- **Developers:** Provide design specifications and review implementation
- **QA Lead:** Define usability acceptance criteria and test scenarios
- **Stakeholders:** Communicate design decisions and user research findings

---

## How these personas are used in the exercise

- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference interaction points to understand cross-functional dependencies and communication needs.
- Use the responsibilities and goals to clarify decision authority and accountability on your project.
