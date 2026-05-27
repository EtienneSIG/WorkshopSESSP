# Facilitator Runbook (50-minute core + optional 10-minute ClawPilot module)

This runbook is designed to be used live during the workshop.

## 0. Why Use AI Daily (8 min)

### Goal
Create urgency and relevance. Show that AI is not a gimmick; it is a leverage tool.

### Script (Step by Step)
1. Start with a baseline question: "How much time do you spend weekly on repetitive writing, research, and formatting?"
2. Share framing: AI helps with speed, quality consistency, and context switching.
3. Show 3 concrete outcomes:
   - Faster first drafts
   - Better preparation before customer meetings
   - More consistent follow-up quality
4. Clarify the model: Human owns judgment, AI accelerates execution.

### Slide or Whiteboard Message
- AI should remove low-value effort, not replace customer trust.

## 1. Personalize Copilot (10 min)

### Goal
Move from generic answers to role-aware assistance.

### Live Steps
1. Open VS Code and show Copilot Chat.
2. Create role instructions:
   - SE: architecture accuracy, Azure best practices, ask clarifying questions.
   - SSP: customer value language, concise business outcomes, objection-aware tone.
3. Add communication preferences:
   - Output format (bullets, table, executive summary)
   - Language and brevity level
4. Demonstrate before/after with the same prompt.

### Exercise (2 min)
Each participant writes 5-8 lines of personal instructions and tests one prompt.

### Success Criteria
- Output reflects role language and expected structure.

## 2. Personalize Copilot Cowork (10 min)

### Goal
Show how AI collaboration patterns improve team throughput.

### Live Steps
1. Define Copilot Cowork in practical terms:
   - Working with shared context, role prompts, and reusable collaboration flows.
2. Build a simple Cowork template:
   - Context block (account, objective, constraints)
   - Role block (SE or SSP)
   - Output block (what "done" looks like)
3. Demonstrate handoff patterns:
   - SSP creates discovery summary
   - SE turns summary into solution options
   - SSP converts output into customer narrative
4. Show versioning of prompts in a shared repo/folder.

### Exercise (2 min)
Pairs create one shared prompt template and run it on a mock account.

### Success Criteria
- Same template works for both participants with minor edits.

## 3. Practical Daily Use Cases (19 min)

## Path A: Solution Engineer (9-10 min)

### Use Case 1: Discovery to Architecture Draft (3 min)
1. Input customer requirements and constraints.
2. Ask Copilot for 2 architecture options with trade-offs.
3. Request risk register and assumptions.

### Use Case 2: Troubleshooting Assistant (3 min)
1. Paste logs/error summary.
2. Ask for likely root causes ranked by probability.
3. Ask for verification commands and rollback-safe actions.

### Use Case 3: Demo Readiness (3 min)
1. Ask for demo flow optimized for persona.
2. Generate talk track, expected questions, and fallback plan.

## Path B: Azure Sales Specialist (9-10 min)

### Use Case 1: Account Brief in 10 Minutes (3 min)
1. Input account notes and latest signals.
2. Ask Copilot for executive summary and opportunity map.
3. Request 3 business hypotheses tied to Azure outcomes.

### Use Case 2: Objection Handling (3 min)
1. Input common objections (cost, migration risk, security).
2. Ask for response framework: acknowledge, evidence, next step.
3. Generate role-play snippets.

### Use Case 3: Follow-Up at Scale (3 min)
1. Convert meeting notes into tailored follow-up email.
2. Request stakeholder-specific versions (CIO, IT manager, finance).
3. Ask for clear CTA and timeline.

## Closing (3 min, core session)
1. Ask each participant to pick one weekly task to automate.
2. Define a 2-week experiment:
   - Baseline duration
   - AI-assisted duration
   - Quality score
3. Schedule a follow-up review.

## Optional Module: What is ClawPilot, Access, and Use Cases (10 min)

### What ClawPilot Is
ClawPilot is a task-oriented AI assistant experience focused on getting operational work done quickly with guided automation patterns.

### How to Access
1. Use the internal access path and tenant configuration defined by your organization.
2. Verify account permissions and approved data boundaries.
3. Start with low-risk scenarios and approved data sources.

### Where It Helps Most
- Administrative workflows (expense report preparation, recurring submissions)
- Structured business tasks (meeting prep packages, action trackers)
- Cross-tool productivity (collect, normalize, draft, summarize)

### Example: Expense Reporting
1. Collect receipt data (date, merchant, amount, category).
2. Ask ClawPilot to structure and validate line items.
3. Generate a review-ready expense draft.
4. Human validates and submits.

## Facilitator Notes
- Keep demos realistic and short.
- Always show human validation checkpoints.
- Reinforce trust, compliance, and data handling boundaries.
