# Core Concepts

[← Documentation home](./README)

Extimator uses a few key building blocks. Understanding them makes estimates faster and more consistent.

---

## Projects

A project is the top level container. Each project has its own categories, tasks, roles, pricing model, and sprint settings.

## Categories

Categories group related work. Example categories are Discovery, Design, and Implementation.

## Tasks

Tasks live inside categories. Each task can have:
- A name and description
- One or more role assignments
- Hours per role
- Optional risk markup

## Roles

Roles represent delivery roles such as Lead Developer or UX Designer. Roles have a default hourly rate and drive effort and cost totals.

---

## Sprint settings

Sprint settings define:
- Sprint length and count
- Meeting templates
- Capacity and load

## General costs

General costs are percentage based adjustments such as risk buffer or overhead.

---

## How these pieces fit together

An easy way to think about it:
- **Tasks** carry hours.
- **Roles** multiply hours into cost (via hourly rates).
- **Sprints and meetings** model delivery load and capacity.
- **General costs** adjust totals at the end (for example risk buffer).

Example (simplified):
1. Create a “Build” category.
2. Add a task “Implement authentication”.
3. Assign “Lead Developer: 12 hours” and “QA: 4 hours”.
4. Review totals, then validate capacity with sprint planning.

## Next step

Continue with: [Estimation Workflow](./04-estimation-workflow.md)

---

**Previous:** [Getting Started](./02-getting-started.md)  
**Next:** [Estimation Workflow](./04-estimation-workflow.md)
