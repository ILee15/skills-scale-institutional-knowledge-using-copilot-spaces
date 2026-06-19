# OctoAcme Roles & Personas: Interaction Checklist

This checklist helps project teams ensure all necessary roles are engaged and interactions are planned for a successful project.

## Project Staffing Checklist

### Step 1: Assess Project Complexity
- [ ] Highly complex (5+ teams, significant technical dependencies, 3+ month timeline)
- [ ] Moderate complexity (2-4 teams, some dependencies, 1-3 months)
- [ ] Low complexity (single team, minimal dependencies, <1 month)

### Step 2: Identify Required Roles

**Always required:**
- [ ] Project Manager
- [ ] Product Manager
- [ ] Developers
- [ ] QA/Testing

**Recommended for all projects:**
- [ ] Delivery Lead (drives daily execution)

**Assess for your project:**
- [ ] Technical Program Manager (if 3+ teams involved or significant technical sequencing)
- [ ] Release Engineer (if frequent or complex deployments)
- [ ] UX Researcher/Designer (if user experience is critical or new to market)
- [ ] Data Analyst (if success metrics are complex or impact-driven decisions needed)
- [ ] Security Champion (if handling sensitive data or security-critical features)
- [ ] Support Liaison (if feature impacts customers or support processes)
- [ ] Business Analyst (if requirements are complex or cross-functional)

### Step 3: Assign Owners
For each identified role, assign:
- Primary owner: (name/title)
- Backup/support: (optional)
- Notes: (e.g., part-time, external partner, shared across projects)

| Role | Primary | Backup | Notes |
|------|---------|--------|-------|
| Project Manager | | | |
| Product Manager | | | |
| Delivery Lead | | | |
| Technical Program Manager | | | |
| Release Engineer | | | |
| UX Researcher | | | |
| Data Analyst | | | |
| Security Champion | | | |
| Support Liaison | | | |
| Business Analyst | | | |

## Interaction Planning Checklist

### Pre-Project Kickoff
- [ ] All identified roles are assigned and onboarded
- [ ] Communication expectations and meeting cadence documented
- [ ] Roles understand their responsibilities and primary interactions
- [ ] Success metrics defined (Data Analyst aligned if assigned)

### During Project Execution
- [ ] Weekly sync between PM, Product Manager, and Delivery Lead
- [ ] Daily standups include Delivery Lead, Developers, and QA
- [ ] Blockers flagged to Delivery Lead daily; escalated to PM weekly
- [ ] Dependencies mapped with TPM (if assigned) at project start and reviewed weekly
- [ ] Security Champion reviews design and code per sprint
- [ ] Data Analyst provides weekly metrics and progress signals
- [ ] Support Liaison surfaces customer issues weekly
- [ ] Business Analyst clarifies requirements as they emerge

### Release & Deployment
- [ ] Pre-release checklist completed (Release Engineer sign-off)
- [ ] Security scans passed (Security Champion approval)
- [ ] Acceptance criteria met (QA, UX Researcher, Business Analyst validation)
- [ ] Rollback plan documented (Release Engineer ownership)
- [ ] Post-deploy verification planned (Release Engineer + Support Liaison)

### Post-Project
- [ ] Retrospective held with all key roles
- [ ] Action items assigned with clear owners and due dates
- [ ] Lessons learned documented for future projects

## Handoff Template

Use this template to clarify key handoffs between roles:

**Handoff Name:** (e.g., "Requirements to Development")
- **From:** (role)
- **To:** (role)
- **Deliverable:** (what is being passed)
- **Acceptance Criteria:** (what "done" looks like)
- **Timeline:** (when it needs to happen)
- **Owner:** (who drives the handoff)

### Example: Requirements Clarification Handoff
- **From:** Business Analyst
- **To:** Developers
- **Deliverable:** Detailed requirements document with acceptance criteria
- **Acceptance Criteria:** All acceptance criteria are testable; edge cases identified; Developers understand feasibility and estimates
- **Timeline:** Before sprint planning
- **Owner:** Business Analyst with Developer review

## Communication Plan Template

| Role | Meeting/Sync | Frequency | Attendees | Purpose |
|------|--------------|-----------|-----------|---------|
| PM/Product Manager/Delivery Lead Sync | Weekly | 30 min | PM, PdM, Delivery Lead | Status, risks, scope changes, escalations |
| Delivery Standup | Daily | 15 min | Delivery Lead, Developers, QA | Progress, blockers, dependencies |
| Technical Dependency Review | Weekly | 30 min | TPM, Eng Managers, Architects | Sequencing, blockers, integration |
| Security Review | Per sprint | 30 min | Security Champion, Dev Lead, Architects | Design/code review, scan findings, fixes |
| Metrics & Success Review | Weekly | 20 min | Data Analyst, Product Manager, Delivery Lead | Progress signals, impact, adjustments |
| Retrospective | End of milestone | 60 min | All roles | Learnings, action items, improvements |

## Common Antipatterns to Avoid

- **Missing role clarity:** Two people doing the same work or no one owning a critical activity
  - *Fix:* Use this checklist and role matrix to assign explicit owners
- **Unclear handoffs:** Work is lost or reworked because handoff criteria aren't documented
  - *Fix:* Use the handoff template to clarify expectations before work begins
- **Siloed communication:** Roles don't interact regularly, causing surprises or misalignment
  - *Fix:* Schedule regular syncs (daily standups, weekly alignment) and use shared project board
- **Overloaded single person:** One role owner has too many responsibilities or projects
  - *Fix:* Assign backup owners or split role responsibilities across team members
- **Late escalation of risks:** Issues surface too late to be mitigated
  - *Fix:* Ensure Security Champion, Data Analyst, and TPM have weekly visibility; escalate blockers daily
