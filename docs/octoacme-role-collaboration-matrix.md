# OctoAcme Role Collaboration Matrix

## Purpose
This document provides a quick reference for how different roles interact and collaborate throughout the project lifecycle. Use this to understand handoffs, collaboration points, and communication patterns.

## Key Collaboration Patterns

### Product Direction & Strategy
- **Product Manager ↔ Product Owner**: PM defines overall strategy and metrics; Product Owner translates to tactical backlog priorities
- **Product Owner ↔ Business Analyst**: Product Owner sets vision; BA documents detailed requirements and workflows
- **User Advocate ↔ Product Owner**: User Advocate provides user insights to inform Product Owner's prioritization decisions

### Requirements & Planning
- **Business Analyst ↔ Developers**: BA provides requirements; Developers clarify technical feasibility
- **Product Owner ↔ Developers**: Product Owner clarifies acceptance criteria and makes scope decisions
- **Project Manager ↔ Product Owner**: PM manages timeline and risks; Product Owner prioritizes scope
- **QA Lead ↔ Business Analyst**: Collaborate on test scenarios based on business requirements

### Execution & Quality
- **Developers ↔ QA Lead**: Developers build and test; QA Lead validates quality and reports defects
- **QA Lead ↔ Product Owner**: QA Lead ensures acceptance criteria are testable; Product Owner validates quality standards
- **User Advocate ↔ Developers**: User Advocate provides usability feedback on work-in-progress

### Change & Adoption
- **Change Manager ↔ User Advocate**: Partner on user readiness, training, and adoption strategies
- **Change Manager ↔ Project Manager**: Coordinate on communication timeline and stakeholder engagement
- **Change Manager ↔ QA Lead**: Collaborate on UAT planning and identify training needs

### Cross-Functional Coordination
- **Project Manager**: Facilitates communication across all roles, manages dependencies
- **Stakeholders**: Provide input and approvals at key milestones to all relevant roles

## Collaboration by Project Phase

### Initiation
| Role | Key Activities | Primary Collaborators |
|------|---------------|----------------------|
| Product Manager | Define business case and success metrics | Product Owner, Stakeholders |
| Product Owner | Define initial product vision | Product Manager, Business Analyst |
| Business Analyst | Conduct stakeholder interviews, document requirements | Product Owner, Stakeholders |
| Project Manager | Create project plan and timeline | Product Owner, Developers |
| QA Lead | Identify quality risks | Project Manager, Product Owner |
| User Advocate | Conduct user research | Product Owner, Business Analyst |
| Change Manager | Assess change impact | Project Manager, Stakeholders |

### Planning
| Role | Key Activities | Primary Collaborators |
|------|---------------|----------------------|
| Product Owner | Prioritize backlog | Developers, Business Analyst |
| Business Analyst | Detail requirements and acceptance criteria | Product Owner, QA Lead |
| Project Manager | Finalize timeline and dependencies | All roles |
| Developers | Estimate effort and identify risks | Product Owner, QA Lead |
| QA Lead | Define testing strategy | Developers, Business Analyst |
| User Advocate | Review acceptance criteria for usability | Product Owner, Business Analyst |
| Change Manager | Create communication plan | Project Manager, User Advocate |

### Execution
| Role | Key Activities | Primary Collaborators |
|------|---------------|----------------------|
| Developers | Build features | Product Owner, QA Lead |
| Product Owner | Clarify requirements, provide feedback | Developers, Business Analyst |
| Business Analyst | Answer questions on business logic | Developers, Product Owner |
| QA Lead | Execute tests, track defects | Developers, Product Owner |
| User Advocate | Review prototypes, provide usability feedback | Developers, QA Lead |
| Project Manager | Track progress, manage blockers | All roles |
| Change Manager | Conduct training sessions | User Advocate, QA Lead |

### Deployment
| Role | Key Activities | Primary Collaborators |
|------|---------------|----------------------|
| Product Owner | Approve release | QA Lead, Project Manager |
| QA Lead | Execute smoke tests, validate quality | Developers, Product Owner |
| Project Manager | Coordinate deployment | All roles |
| Developers | Deploy and monitor | QA Lead, Project Manager |
| Change Manager | Coordinate rollout communication | Project Manager, Stakeholders |
| User Advocate | Facilitate UAT | QA Lead, Change Manager |
| Business Analyst | Support UAT validation | User Advocate, QA Lead |

## Communication Channels by Role

### Synchronous (Meetings)
- **Daily Standups**: Developers, QA Lead, Project Manager
- **Sprint Planning**: Product Owner, Developers, QA Lead, Business Analyst, Project Manager
- **Sprint Reviews/Demos**: All roles, Stakeholders
- **Backlog Refinement**: Product Owner, Business Analyst, Developers, QA Lead
- **Retrospectives**: All delivery team roles

### Asynchronous (Documentation & Tools)
- **Requirements Documentation**: Business Analyst → Product Owner, Developers, QA Lead
- **Project Board Updates**: Project Manager → All roles
- **Test Reports**: QA Lead → Product Owner, Project Manager, Developers
- **User Research Findings**: User Advocate → Product Owner, Business Analyst
- **Change Communications**: Change Manager → Stakeholders, all roles

## Escalation Paths
- **Technical Blockers**: Developers → Project Manager → Product Owner
- **Requirements Clarification**: Developers → Business Analyst → Product Owner
- **Quality Issues**: QA Lead → Product Owner → Project Manager
- **Scope Changes**: Product Owner → Project Manager → Stakeholders
- **Adoption Issues**: Change Manager → Project Manager → Stakeholders

## Tips for Effective Collaboration
1. **Clarify Roles Early**: In project kickoff, ensure everyone understands who owns what
2. **Establish Communication Norms**: Define which channels (Slack, email, meetings) for what types of communication
3. **Document Decisions**: Use decision logs to track key choices and rationale
4. **Reduce Handoff Friction**: Over-communicate at role boundaries (e.g., BA → Developer, Developer → QA)
5. **Invite the Right People**: Only include necessary roles in meetings to respect everyone's time
6. **Use Shared Artifacts**: Keep project board, backlog, and documentation as single source of truth
