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

## Product Owner

### Role Summary
Product Owners maintain the product vision and prioritize requirements to maximize value delivery. They serve as the primary decision-maker for scope and direction, working closely with stakeholders and the delivery team.

### Responsibilities
- Define and communicate the product vision and strategy
- Maintain and prioritize the product backlog
- Make decisions about scope, features, and trade-offs
- Ensure requirements align with business goals and user needs
- Accept or reject completed work based on acceptance criteria
- Collaborate with stakeholders to gather feedback and validate direction

### Goals
- Maximize return on investment (ROI) and business value
- Ensure the product meets user needs and market demands
- Balance competing priorities and constraints effectively
- Maintain a healthy, prioritized backlog

### Typical Communication
- Backlog refinement sessions with the delivery team
- Stakeholder reviews and feedback sessions
- Sprint planning and review meetings
- Regular sync with Product and Project Managers

### Interactions with Other Roles
- **Product Managers**: Aligns on product strategy and metrics; Product Owner focuses on tactical prioritization while Product Manager owns the broader vision
- **Project Managers**: Provides input on priorities and scope decisions; collaborates on timeline and resource planning
- **Developers**: Clarifies requirements, answers questions, and provides acceptance feedback
- **Business Analyst**: Works together to refine requirements and ensure clarity
- **QA Lead**: Reviews acceptance criteria and validates that quality standards are met

### Example Scenarios

**Initiation Phase**: During project kickoff, the Product Owner defines the initial product vision and success criteria in the project one-pager, identifying the high-value features that must be delivered.

**Planning Phase**: In sprint planning, the Product Owner prioritizes backlog items, ensuring the team focuses on the highest-value work first. They answer questions about requirements and adjust priorities based on team capacity.

**Execution Phase**: During development, the Product Owner is available to clarify acceptance criteria, make scope decisions when blockers arise, and provide feedback on work-in-progress during demos.

**Deployment Phase**: Before release, the Product Owner reviews completed features against acceptance criteria and approves the release, ensuring all critical requirements are met.

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between stakeholder needs and technical solutions. They gather requirements, document workflows, facilitate discussions, and support validation efforts to ensure solutions meet business objectives.

### Responsibilities
- Elicit and document business requirements from stakeholders
- Analyze current state processes and identify improvement opportunities
- Translate business needs into clear, actionable requirements
- Create process flows, use cases, and documentation
- Support testing and user acceptance validation
- Facilitate requirements workshops and stakeholder sessions

### Goals
- Ensure requirements are complete, clear, and testable
- Minimize rework by identifying gaps and conflicts early
- Bridge communication gaps between business and technical teams
- Support data-driven decision making

### Typical Communication
- Requirements gathering sessions with stakeholders
- Documentation in the form of user stories, process maps, and specifications
- Collaboration with developers on technical feasibility
- Participation in sprint planning and backlog refinement

### Interactions with Other Roles
- **Product Owner**: Collaborates on requirement clarification and backlog refinement; helps translate vision into detailed requirements
- **Developers**: Provides detailed requirements and answers technical questions about business logic
- **QA Lead**: Collaborates on test scenarios and validation criteria
- **Stakeholders**: Primary liaison for gathering needs and validating solutions
- **Project Manager**: Provides input on scope, dependencies, and risks

### Example Scenarios

**Initiation Phase**: The Business Analyst conducts stakeholder interviews to understand pain points and document initial requirements. They contribute to the problem statement in the project one-pager.

**Planning Phase**: During backlog refinement, the Business Analyst works with the Product Owner to flesh out user stories with detailed acceptance criteria, process flows, and edge cases.

**Execution Phase**: As developers implement features, the Business Analyst is available to clarify business rules and logic. They review prototypes and provide feedback to ensure solutions meet business needs.

**Deployment Phase**: The Business Analyst supports user acceptance testing (UAT), helping validate that the solution works as expected and documenting any gaps for future iterations.

---

## QA Lead

### Role Summary
QA Leads ensure quality standards for project deliverables through planning, coordination, and execution of comprehensive testing efforts. They work with developers and project leads to define quality criteria and testing strategies.

### Responsibilities
- Define quality standards and testing strategy for the project
- Plan and coordinate testing efforts across unit, integration, and end-to-end tests
- Review acceptance criteria for testability
- Lead test execution, defect tracking, and test reporting
- Advocate for quality best practices and automation
- Ensure security and performance testing are addressed

### Goals
- Deliver high-quality, reliable software with minimal defects
- Catch issues early in the development cycle
- Build confidence in releases through comprehensive testing
- Improve test coverage and automation over time

### Typical Communication
- Daily coordination with developers on test status and blockers
- Sprint planning to estimate testing effort and identify risks
- Test reports and quality metrics in status updates
- Bug triage and prioritization discussions

### Interactions with Other Roles
- **Developers**: Collaborates on test design, reviews code for testability, and reports defects
- **Product Owner**: Ensures acceptance criteria are testable and validates quality standards
- **Business Analyst**: Works together to understand business logic for test scenarios
- **Project Manager**: Reports on quality metrics, risks, and test progress
- **Change Manager**: Coordinates on UAT and provides quality input for release readiness

### Example Scenarios

**Initiation Phase**: The QA Lead reviews the project one-pager and identifies quality risks, such as areas requiring performance testing or security validation.

**Planning Phase**: During sprint planning, the QA Lead reviews acceptance criteria for testability, estimates testing effort, and ensures the Definition of Done includes quality gates.

**Execution Phase**: As features are developed, the QA Lead coordinates test execution, tracks defects, and provides daily updates on quality status. They work closely with developers to reproduce and resolve issues.

**Deployment Phase**: Before release, the QA Lead executes smoke tests, validates that all critical defects are resolved, and signs off on release readiness. They participate in go/no-go decisions.

---

## Change Manager

### Role Summary
Change Managers oversee organizational change processes, including communications, training, and stakeholder buy-in during major process or tool changes. They ensure smooth adoption and minimize resistance.

### Responsibilities
- Develop and execute change management plans
- Identify and engage stakeholders impacted by changes
- Create communication plans and materials for rollout
- Coordinate training and support for end users
- Monitor adoption and address resistance or concerns
- Collect feedback and support continuous improvement

### Goals
- Maximize user adoption and minimize disruption
- Build stakeholder buy-in and support for changes
- Ensure users are prepared and supported through transitions
- Measure adoption success and identify improvement areas

### Typical Communication
- Change impact assessments and stakeholder maps
- Communication plans, announcements, and training materials
- Regular check-ins with impacted teams and user groups
- Post-deployment surveys and feedback collection

### Interactions with Other Roles
- **Project Manager**: Coordinates on timeline, milestones, and communication touchpoints
- **Product Owner**: Aligns on change scope and user impact
- **QA Lead**: Collaborates on UAT and identifies training needs based on quality feedback
- **User Advocate**: Partners to ensure user perspectives are reflected in change plans
- **Stakeholders**: Primary point of contact for change communication and support

### Example Scenarios

**Initiation Phase**: The Change Manager conducts a change impact assessment to identify who will be affected and develops an initial stakeholder engagement plan.

**Planning Phase**: During planning, the Change Manager creates a detailed communication and training plan, including timelines for announcements, training sessions, and support availability.

**Execution Phase**: As the project progresses, the Change Manager sends regular updates to stakeholders, conducts training sessions, and gathers feedback on readiness and concerns.

**Deployment Phase**: At release, the Change Manager coordinates the rollout communication, ensures support resources are available, and monitors adoption metrics. Post-deployment, they collect feedback for lessons learned.

---

## User Advocate

### Role Summary
User Advocates represent end-users throughout the project lifecycle, ensuring their needs and perspectives are factored into planning and decision-making. They champion usability, accessibility, and user satisfaction.

### Responsibilities
- Represent the voice of the user in planning and design discussions
- Conduct user research and gather feedback
- Review designs and prototypes for usability and accessibility
- Ensure user needs are reflected in acceptance criteria
- Advocate for inclusive design and user experience improvements
- Facilitate user testing and feedback sessions

### Goals
- Ensure solutions are user-friendly and accessible
- Minimize user friction and support costs
- Build products that users love and adopt readily
- Promote user-centered design practices

### Typical Communication
- User research findings and personas
- Usability feedback on designs and prototypes
- Participation in sprint reviews and demos
- User testing session reports and insights

### Interactions with Other Roles
- **Product Owner**: Collaborates to ensure user needs inform backlog priorities
- **Business Analyst**: Partners on requirements gathering and user workflow documentation
- **Developers**: Provides feedback on user experience and usability during development
- **QA Lead**: Participates in UAT planning and execution from a user perspective
- **Change Manager**: Works together to ensure user readiness and smooth adoption

### Example Scenarios

**Initiation Phase**: The User Advocate conducts initial user research to understand pain points and contributes user insights to the problem statement and success metrics.

**Planning Phase**: During backlog refinement, the User Advocate reviews user stories and acceptance criteria to ensure they reflect real user needs and workflows. They may create user personas or journey maps.

**Execution Phase**: As features are built, the User Advocate reviews prototypes and provides usability feedback. They may conduct quick user testing sessions to validate design decisions.

**Deployment Phase**: Before release, the User Advocate facilitates user acceptance testing with real end-users, collects feedback, and ensures critical usability issues are addressed.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

