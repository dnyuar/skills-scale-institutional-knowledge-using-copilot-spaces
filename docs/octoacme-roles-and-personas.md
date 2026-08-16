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

## QA/Testing Lead

### Role Summary
QA/Testing Leads own quality assurance strategy, test planning, and validation activities. They ensure deliverables meet acceptance criteria and quality standards before release.

### Responsibilities
- Create and maintain test plans aligned with feature acceptance criteria
- Define testing strategy (unit, integration, end-to-end, security scanning)
- Coordinate manual and automated testing efforts
- Identify and track quality issues and regressions
- Validate smoke tests before production releases
- Report quality metrics and test coverage to the team

### Goals
- Prevent defects from reaching production
- Maintain high test coverage and reliability standards
- Enable fast, confident releases

### Interaction with Other Roles
- **Developers**: Collaborate on test strategy and provide feedback on code quality and test coverage
- **Product Managers**: Validate acceptance criteria are testable and align on quality expectations
- **Project Managers**: Update on test progress, blockers, and readiness for release gates
- **Technical Architects**: Ensure testing strategy aligns with system design and integration points

### Typical Communication
- Planning sessions and QA approach definition
- Backlog refinement (acceptance criteria review)
- Status updates on test coverage and quality metrics
- Pre-release coordination and smoke test validation

---

## Sponsor/Executive Stakeholder

### Role Summary
Sponsors are senior stakeholders who authorize and oversee projects. They provide business context, resource approval, and escalation authority.

### Responsibilities
- Approve project charter and resource allocation
- Escalate business-impacting risks and blockers
- Provide executive visibility and stakeholder alignment
- Review milestone achievements and release outcomes
- Communicate project status to broader organization

### Goals
- Ensure project delivers business value
- Maintain alignment with organizational strategy
- Minimize business risk and resource constraints

### Interaction with Other Roles
- **Project Managers**: Receive status updates and escalation notifications; approve resource changes
- **Product Managers**: Align on strategic priorities and business outcomes
- **Developers**: May provide guidance on business context and strategic importance
- **All Roles**: Approve major project decisions and serve as escalation authority for Level 3 blockers

### Typical Communication
- Project initiation and approval meetings
- Monthly stakeholder updates
- Escalation reviews for Level 3 blockers
- Post-release retrospectives and outcome reviews

---

## Technical Architect

### Role Summary
Technical Architects define system design, integration patterns, and technical strategy to support project goals. They ensure scalability, maintainability, and alignment with organizational standards.

### Responsibilities
- Define system architecture and design patterns
- Identify technical risks and integration points
- Review designs and code for architectural alignment
- Propose mitigation strategies for technical debt and scalability concerns
- Collaborate on technical trade-offs during planning
- Provide technical guidance to development team

### Goals
- Deliver technically sound, scalable solutions
- Reduce technical risk and future maintenance burden
- Ensure consistency with organizational standards

### Interaction with Other Roles
- **Developers**: Provide architectural guidance, review designs, and mentor on technical standards
- **Project Managers**: Identify technical dependencies and integration points for planning
- **QA/Testing Leads**: Define testing strategy for complex architectural components
- **Product Managers**: Advise on technical feasibility and trade-offs for features
- **Security Leads**: Collaborate on security architecture and threat modeling

### Typical Communication
- Design reviews and technical spike discussions
- Project planning and risk assessment
- Code review comments on architectural decisions
- Integration planning with dependent systems
- Technical documentation and architecture decision records

---

## Security Lead

### Role Summary
Security Leads ensure projects incorporate security best practices, comply with organizational policies, and manage security risks throughout the project lifecycle.

### Responsibilities
- Review security requirements and design
- Define security testing and scanning requirements
- Participate in risk assessment and threat identification
- Coordinate security incident response
- Ensure compliance with security policies and standards
- Provide security guidance to development and QA teams

### Goals
- Prevent security vulnerabilities and data breaches
- Maintain compliance with security standards
- Enable secure, trustworthy releases

### Interaction with Other Roles
- **Developers**: Provide security guidance, review code for vulnerabilities, and educate on secure practices
- **QA/Testing Leads**: Ensure security testing is included in test plans and CI/CD pipeline
- **Technical Architects**: Collaborate on security architecture, threat modeling, and design reviews
- **Project Managers**: Escalate security risks and participate in risk register management
- **Sponsors**: Report compliance status and critical security incidents for escalation

### Typical Communication
- Security design reviews and threat modeling sessions
- Risk register updates and security risk escalations
- CI/CD pipeline integration (security scanning and policy checks)
- Incident response coordination and post-incident reviews
- Pre-release security validation and sign-off

---

## Scrum Master/Agile Coach

### Role Summary
Scrum Masters facilitate agile practices and remove impediments to team productivity. They coach the team on agile methodologies, manage sprint ceremonies, and foster continuous improvement.

### Responsibilities
- Facilitate daily standups, sprint planning, reviews, and retrospectives
- Remove impediments and blockers to team progress
- Coach team members on agile practices and ceremonies
- Maintain sprint backlog and tracking
- Monitor team velocity and identify process improvements
- Protect team focus and manage scope creep

### Goals
- Enable team productivity and flow
- Foster continuous improvement and psychological safety
- Ensure adherence to agile practices and ceremonies
- Support team self-organization and accountability

### Interaction with Other Roles
- **Project Managers**: Coordinate on timelines and escalations; provide sprint metrics
- **All Team Members**: Facilitate ceremonies, coach on agile practices, and remove blockers
- **Product Managers**: Manage backlog refinement and sprint planning alignment
- **Developers**: Support with process impediments and team dynamics

### Typical Communication
- Daily standups and sprint ceremonies
- One-on-one coaching and team retrospectives
- Sprint metrics and velocity reporting
- Impediment tracking and resolution
- Continuous process improvement discussions

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Cross-functional interactions are documented to help teams understand dependencies and communication flows.
