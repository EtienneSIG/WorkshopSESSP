# SE Workbook

## Purpose
This workbook helps Azure Solution Engineers run practical AI-assisted workflows during and after the workshop.

## Session Timing (SE Track - 35 minutes in workshop)
- 5 min: AI value framing for technical work
- 8 min: Copilot personalization for SE tasks
- 7 min: Copilot Cowork team flow
- 10 min: daily practical SE use cases
- 5 min: ClawPilot operational use case

## 0) Why AI in Your Daily Technical Work

### Your Current Baseline
Fill this before the session:
- Repetitive task I do every week:
- Average time spent per week:
- Quality pain point (consistency, speed, clarity):

### Technical ROI Lens
Use AI where it creates measurable outcomes:
- Faster architecture draft creation
- Better troubleshooting triage quality
- Better demo and customer-readiness

## 1) Personalize Copilot for SE

### Copy/Paste SE Instruction Starter
Use this as your baseline instruction profile:

I am an Azure Solution Engineer.
Prioritize technical correctness, Azure Well-Architected guidance, and secure-by-default patterns.
When requirements are unclear, ask 3 clarifying questions first.
Output should be structured, concise, and implementation-ready.
When providing options, always include trade-offs on cost, security, operations, and scalability.
For scripts or IaC, include verification steps and rollback-safe guidance.

### Exercise
1. Paste your profile into your Copilot instructions.
2. Run one prompt before and after personalization.
3. Compare output quality.

### Quality Checklist
- Did the response ask clarifying questions?
- Are trade-offs explicit?
- Is there a safe implementation path?

## 2) Personalize Copilot Cowork for SE

### Cowork Template (SE + SSP handoff)
- Context: customer workload, constraints, current environment
- Objective: target architecture or migration decision
- Constraints: security, budget, timeline, compliance
- Output format: decision matrix + recommendation
- Reviewer persona: platform architect

### Exercise
1. Work in pair mode with an SSP participant.
2. SSP writes business objectives and objections.
3. You convert that into technical options with rationale.
4. SSP challenges assumptions. You revise.

## 3) Daily Practical SE Use Cases

## Use Case A: Discovery to Architecture Matrix
Prompt:
Create 3 Azure architecture options from these requirements. Include one conservative, one balanced, and one growth-first option. Add a score table on security, cost, complexity, and time-to-value. End with recommendation and assumptions.

Notes:
- Inputs used:
- Best output section:
- What needed human correction:

## Use Case B: Triage from Logs
Prompt:
Given this incident summary and logs, rank likely root causes by probability. For each root cause, provide quick verification actions, expected evidence, and rollback-safe next action.

Notes:
- Most useful diagnostic step:
- Risk if blindly executed:
- Final validated path:

## Use Case C: Demo Readiness Pack
Prompt:
Generate a demo run-of-show for this customer persona, including storyline, key value points, likely questions, fallback plan, and a 2-minute executive wrap-up.

Notes:
- Strongest narrative element:
- Missing business framing:
- Final demo adjustment:

## 4) ClawPilot for SE

### What to Use It For
- Operational workflows that are structured and repetitive
- Intake normalization and action-tracker generation
- Expense preparation support and evidence organization

### Exercise: Technical Trip Expense Prep
1. Prepare sample receipt list.
2. Ask ClawPilot to classify by type and date.
3. Ask for missing-field validation and policy flags.
4. Produce submission-ready draft, then human review.

## 2-Week Adoption Plan
- Weekly task to automate:
- Baseline time:
- AI-assisted time:
- Quality score before/after:
- One improvement to your SE prompt profile:

## Personal Prompt Backlog
- Prompt to improve:
- Prompt to share with team:
- Prompt to retire:
