# SE Workbook

## Purpose
This workbook helps Azure Solution Engineers run practical AI-assisted workflows during and after the workshop.

## Session Timing (SE Track - 60 minutes)
- 8 min: Why AI now for technical roles
- 12 min: Copilot personalization for SE tasks
- 10 min: Copilot Cowork handoff with SSP
- 20 min: daily practical SE use cases (3 mini-labs)
- 7 min: ClawPilot operational use case
- 3 min: wrap-up commitments

## 60-Minute Flow (Facilitator + Participant)
- 00:00-00:08: baseline and ROI framing
- 00:08-00:20: personalize Copilot and compare before/after
- 00:20-00:30: run Cowork template with SSP handoff
- 00:30-00:50: execute use cases A, B, C with rapid debrief
- 00:50-00:57: ClawPilot expense workflow simulation
- 00:57-01:00: commitment + next two-week actions

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

### Exercise (12 min)
1. Paste your profile into your Copilot instructions.
2. Run one prompt before and after personalization.
3. Compare output quality.
4. Improve your instructions with one concrete rule after first run.

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

### Exercise (10 min)
1. Work in pair mode with an SSP participant.
2. SSP writes business objectives and objections.
3. You convert that into technical options with rationale.
4. SSP challenges assumptions. You revise.
5. Finalize one customer-ready answer in under 150 words.

## 3) Daily Practical SE Use Cases

Run each mini-lab for 6 minutes, then do a 1-minute debrief.

## Use Case A: Discovery to Architecture Matrix
Prompt:
Create 3 Azure architecture options from these requirements. Include one conservative, one balanced, and one growth-first option. Add a score table on security, cost, complexity, and time-to-value. End with recommendation and assumptions.

Notes:
- Inputs used:
- Best output section:
- What needed human correction:
- Estimated time saved:

## Use Case B: Triage from Logs
Prompt:
Given this incident summary and logs, rank likely root causes by probability. For each root cause, provide quick verification actions, expected evidence, and rollback-safe next action.

Notes:
- Most useful diagnostic step:
- Risk if blindly executed:
- Final validated path:
- Verification evidence collected:

## Use Case C: Demo Readiness Pack
Prompt:
Generate a demo run-of-show for this customer persona, including storyline, key value points, likely questions, fallback plan, and a 2-minute executive wrap-up.

Notes:
- Strongest narrative element:
- Missing business framing:
- Final demo adjustment:
- Question to ask customer next:

## 4) ClawPilot for SE

### What to Use It For
- Operational workflows that are structured and repetitive
- Intake normalization and action-tracker generation
- Expense preparation support and evidence organization

### Exercise: Technical Trip Expense Prep (7 min)
1. Prepare sample receipt list.
2. Ask ClawPilot to classify by type and date.
3. Ask for missing-field validation and policy flags.
4. Produce submission-ready draft, then human review.
5. Capture one improvement to your prompt for next month.

## Wrap-Up (Last 3 min)
- One task I will automate this week:
- One risk I will always review manually:
- One prompt I will share with peers:

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
