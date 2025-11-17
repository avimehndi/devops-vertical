# DevOps Assignment — Aviral Mehndiratta

## 1. Your First 4 Weeks

In the first month, my priority will be to learn everything from the ground up and establish a solid foundation before moving into automation.

### Week 1 
- Understand how the existing systems are hosted, deployed, monitored, and accessed
- Speak with engineers to learn what slows them down and what causes the issues
- Review the CI/CD pipelines: note reliability and maintainability gaps
- Document what exists before suggesting improvements

### Week 2 
- Understand the existing CI/CD flows and improve them for the most active repositories
- Add monitoring and logging to high-impact services
- Map current infrastructure: highlight patterns, unknowns, inconsistencies
- Document real deployment flows to remove confusion

### Week 3
- Define the standards for branching, code reviews, and deployments
- Create a reusable CI/CD workflow template
- Automate the repetitive tasks thoughtfully and document them with proper reasoning

### Week 4
- Publish 60–90 day roadmap aligned with engineering needs 
- Share weekly updates: make work visible, predictable, trackable
- Document root causes and prevention steps for discovered issues

## 2. Designing DevOps Foundations

### CI/CD Pipeline Template
- Build a simple, reusable workflow: build → test → scan → deploy
- Keep it clear, maintainable, and easy enough for new engineers to understand without assistance.
- Rollback feature should be present as well

### Infrastructure Baseline
- Use Terraform for all infrastructure provisioning 
- Follow a clean module layout (networking, compute, DB, secrets, monitoring)
- Maintain strict separation between dev, staging, and production

### Deployment & Rollback Strategy
- Use containerization as the default approach to ensure consistency
- Include rollback mechanisms and version tagging in every release keeping it simple
- Use blue-green or rolling deployments based on what the hosting platform supports

### Monitoring and Alerting
- Start with basic metrics: uptime, latency, memory, logs
- Centralize logs and enforce structured logging
- Build basic dashboards and alert only on actionable events

### Security Hygiene
- Move all secrets into a proper secrets manager (AWS Secrets Manager)
- Use least-privilege IAM roles and short-lived credentials
- Treat security as part of everyday development

## 3. Making Work Visible

### Board Structure
- Backlog
- Ready
- In Progress
- Review
- Staging
- Done
- Blocked
- Follow-ups (incident learnings, improvements)

Why this:
- Provide context, acceptance criteria, expected outcome, and validation steps for every task
- Break work into small pieces to maintain flow
- Share weekly updates that are short, clear, and structured
- Use simple, meaningful metrics
- Emphasize transparency

## 4. Developer Experience (DX)
I focus on simplifying the day-to-day development experience so engineers aren’t stuck fixing local setups or pipeline problems—they can just code.

- Provide repo templates with built-in folder structures, tests, CI workflows
- Create docker-compose-based local setups that align closely with cloud environments.
- Write scripts that simplify daily tasks
- Improve documentation

## 5. Entrepreneurial Contribution
Early DevOps engineers play a role in shaping both the internal foundations and how the company presents its technical capabilities externally.

### Case Studies
- Document meaningful changes and improvements
- Focus on root causes, decisions, and the business impact behind each improvement
- Create reusable case study formats for consistency

### Reusable Assets
- Build Terraform base modules, CI templates, dashboards, runbooks
- Prioritize repeatability

### Public Documentation
- Write guides on CI/CD, IaC structure, migrations, security patterns
- Create diagrams, examples, and checklists
- Support the development of early DevOps website content and demos

### Sales & Marketing Support
- Join technical discovery conversations
- Help create clean summaries, and demo environments

DevOps contributes not only to internal reliability but also to how ColoredCow's engineering culture is seen by clients and the public.

## 6. Strengths & Weaknesses

### Strengths
- Hands-on DevOps automation (CI/CD, Docker, Kubernetes) 
- Well versed in Linux commands (RHCSA certified)
- Clear communicator who documents decisions, reasoning, and runbooks 
- Natural sense of ownership and comfort
- Strong willingness to learn

### Weaknesses
- Want to deepen knowledge in multi-account cloud networking and advanced platform design
- Still improving at designing scalable infra from the start
- Continuing to improve automation strategies for complex, multi-service pipelines

### Where I Add The Most Value
- Creating clarity where systems are undefined
- Designing foundational templates, modules, workflows
- Improving developer experience through automation
- Establishing essential metrics and system insights

## 7. Questions for the ColoredCow Team
- How do you measure success for DevOps in the first 90 days?
- How are deployments handled right now, and what challenges come up most often?
- What technologies, tools, and platforms make up your current tech stack?
- What long-term outcome matters most for the DevOps vertical?
- What mentorship or support is available during the early onboarding period?
