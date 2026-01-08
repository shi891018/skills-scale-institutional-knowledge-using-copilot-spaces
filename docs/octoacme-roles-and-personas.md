# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

As projects scale in complexity and scope, effective delivery requires a diverse set of specialized roles working in coordination. This expanded guide includes both core delivery roles (Developers, Product Managers, Project Managers) and supporting specialists (UX/UI Designers, DevOps Engineers, QA Automation Engineers, Business Analysts, and Customer Success/Support Specialists) who ensure quality, usability, and customer satisfaction throughout the project lifecycle. Understanding these personas helps clarify responsibilities, enhance cross-functional collaboration, and reduce ambiguity around ownership and expectations.

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
Ensures user needs and accessibility are integrated into design and functionality.

### Responsibilities
- Design wireframes, prototypes, and user interfaces
- Advocate for user needs and accessibility standards
- Collaborate on user research and usability testing
- Create design systems and style guides

### Goals
- Deliver intuitive, accessible user experiences
- Ensure design consistency across products
- Validate designs with users before implementation

### Typical Communication
- Design reviews with Product Managers and Developers
- User research findings and design rationale
- Prototypes and mockups for feature specifications

### Interactions with existing roles
- Works closely with Product Managers on specs and user requirements
- Collaborates with Developers on UI implementation and feasibility
- Partners with Project Managers on design timelines and deliverables

---

## DevOps Engineer

### Role Summary
Owns deployment pipelines, CI/CD, release automation, and system observability.

### Responsibilities
- Manage deployment pipelines and infrastructure automation
- Maintain CI/CD systems and build processes
- Monitor system performance and reliability
- Create and maintain incident response playbooks

### Goals
- Ensure reliable, automated deployments
- Minimize deployment risks and downtime
- Enable developer velocity through tooling

### Typical Communication
- Release coordination and deployment status
- Infrastructure capacity and performance reports
- Incident response and post-mortem facilitation

### Interactions with existing roles
- Works with Developers for smooth deployments and CI/CD optimization
- Partners with Project Managers for release planning and incident response
- Supports Product Managers with system metrics and reliability data

---

## QA Automation Engineer

### Role Summary
Specializes in automated test creation and maintenance, partnering with development teams.

### Responsibilities
- Build and maintain automated test frameworks and test cases
- Create end-to-end and integration test suites
- Collaborate on test strategy and quality gates
- Analyze test results and failure patterns

### Goals
- Ensure quality is built into the development process
- Reduce manual testing effort through automation
- Catch defects early in the development cycle

### Typical Communication
- Test strategy documents and automation plans
- Quality metrics and test coverage reports
- Bug reports and quality gate recommendations

### Interactions with existing roles
- Collaborates with Developers on testability and automation strategy
- Partners with Product Managers on acceptance criteria and quality standards
- Works with Project Managers on testing timelines and release readiness

---

## Business Analyst

### Role Summary
Converts stakeholder requirements into actionable specifications and business logic.

### Responsibilities
- Collect and analyze business requirements from stakeholders
- Create detailed functional specifications and user stories
- Map business processes and identify improvement opportunities
- Facilitate requirements gathering sessions and stakeholder alignment

### Goals
- Ensure technical solutions align with business needs
- Bridge communication gaps between business and technical teams
- Validate that delivered features meet business requirements

### Typical Communication
- Requirements documents and functional specifications
- Business process diagrams and workflow documentation
- Stakeholder interview summaries and requirement validation

### Interactions with existing roles
- Helps translate business needs into actionable tasks for Product Managers
- Supports Developers with detailed business logic and edge case scenarios
- Partners with Project Managers on scope definition and stakeholder management

---

## Customer Success/Support Specialist

### Role Summary
Acts as the voice of the customer post-launch and throughout the product lifecycle.

### Responsibilities
- Receive and triage user feedback and support tickets
- Escalate product issues and feature requests to appropriate teams
- Provide insights on user adoption and satisfaction metrics
- Create user documentation and training materials

### Goals
- Maximize customer satisfaction and product adoption
- Provide timely resolution to customer issues
- Feed customer insights back into product development

### Typical Communication
- Customer feedback summaries and trend analysis
- Support ticket escalations and resolution updates
- User adoption metrics and satisfaction surveys

### Interactions with existing roles
- Provides customer insights to Product Managers for roadmap prioritization
- Escalates technical issues to Developers for resolution
- Works with Project Managers on customer communication and release impact assessment

---

## Cross-functional Collaboration Patterns

Effective project delivery at OctoAcme relies on clear collaboration patterns between roles. Here are common interaction models:

### Design and Development Cycle
1. **Product Manager** defines feature requirements and success criteria
2. **Business Analyst** translates requirements into detailed specifications and user stories
3. **UX/UI Designer** creates wireframes and prototypes based on user needs
4. **Developers** implement features following design specifications
5. **QA Automation Engineer** builds automated tests to verify functionality
6. **DevOps Engineer** ensures smooth deployment through CI/CD pipelines

### Release and Deployment Flow
1. **Project Manager** coordinates release timeline and dependencies
2. **Developers** complete features and pass quality gates
3. **QA Automation Engineer** validates release readiness through automated test suites
4. **DevOps Engineer** manages deployment process and monitors system health
5. **Customer Success/Support Specialist** prepares support materials and monitors user feedback
6. **Product Manager** tracks launch metrics and user adoption

### Incident Response and Improvement
1. **Customer Success/Support Specialist** identifies and escalates issues from user reports
2. **DevOps Engineer** facilitates incident response and system recovery
3. **Developers** diagnose and fix technical issues
4. **Project Manager** coordinates communication and tracks resolution
5. **Product Manager** prioritizes fixes based on customer impact
6. **QA Automation Engineer** adds regression tests to prevent recurrence

## When to Involve Each Role

Understanding when to engage each persona ensures efficient collaboration and prevents bottlenecks:

### Project Initiation Phase
- **Product Manager**: Define vision, success metrics, and initial requirements
- **Project Manager**: Create project charter, timeline, and resource plan
- **Business Analyst**: Gather detailed requirements from stakeholders
- **UX/UI Designer**: Begin early user research and concept exploration

### Planning and Design Phase
- **UX/UI Designer**: Create wireframes, prototypes, and design specifications
- **Business Analyst**: Document functional specifications and business logic
- **Developers**: Provide technical feasibility input and effort estimates
- **DevOps Engineer**: Plan infrastructure and deployment requirements
- **QA Automation Engineer**: Define test strategy and quality gates

### Development and Testing Phase
- **Developers**: Implement features and conduct code reviews
- **QA Automation Engineer**: Build and execute automated test suites
- **UX/UI Designer**: Review implementation for design consistency
- **DevOps Engineer**: Set up CI/CD pipelines and deployment automation
- **Project Manager**: Track progress, manage risks, and remove blockers

### Release and Deployment Phase
- **DevOps Engineer**: Execute deployment and monitor system health
- **QA Automation Engineer**: Validate production release through smoke tests
- **Customer Success/Support Specialist**: Prepare support documentation and training
- **Product Manager**: Monitor launch metrics and user feedback
- **Project Manager**: Coordinate release communication and manage rollout

### Post-Launch and Support Phase
- **Customer Success/Support Specialist**: Handle user inquiries and collect feedback
- **Product Manager**: Analyze adoption metrics and plan iterations
- **DevOps Engineer**: Monitor system performance and reliability
- **Developers**: Address bugs and technical debt
- **Business Analyst**: Document feature usage patterns and improvement opportunities

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

