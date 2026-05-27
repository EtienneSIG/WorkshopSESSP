# Prompt Library (SE + SSP)

## Prompt Pattern
Use this structure for better outputs:
- Context
- Goal
- Constraints
- Desired output format
- Quality criteria

## SE Prompts

### 1) Architecture Decision Matrix
Context: I am an Azure Solution Engineer preparing options for a customer.
Goal: Build a 3-option architecture decision matrix.
Constraints: Include security, cost, operations, and scalability trade-offs.
Output format: Table with recommendation and rationale.
Quality criteria: Actionable, clear assumptions, no vague statements.

### 2) Incident Triage Assistant
Context: I have incident notes and partial logs.
Goal: Propose a triage plan with likely root causes.
Constraints: Prioritize high-impact checks first.
Output format: Step-by-step runbook with expected observations.
Quality criteria: Fast to execute, clear rollback steps.

### 3) Executive Summary
Context: Technical deep-dive finished.
Goal: Summarize for customer leadership.
Constraints: Non-technical language, business impact first.
Output format: 8-bullet executive summary + 3 actions.
Quality criteria: Concise, decision-oriented.

## SSP Prompts

### 1) Persona-Based Value Story
Context: I am an Azure Sales Specialist preparing account messaging.
Goal: Build a value narrative for CIO, CISO, and CFO.
Constraints: Tie each point to measurable outcomes.
Output format: Persona sections with outcome, proof point, next question.
Quality criteria: Customer-centric and specific.

### 2) Proposal Skeleton
Context: Discovery meeting notes are available.
Goal: Create a proposal outline with phases and milestones.
Constraints: Include risks and dependencies.
Output format: Structured proposal skeleton with timeline and owners.
Quality criteria: Ready for internal review.

### 3) Follow-Up Email Pack
Context: Meeting completed.
Goal: Draft three follow-up emails (executive, technical, procurement).
Constraints: Keep each under 180 words.
Output format: 3 separate emails with clear CTA.
Quality criteria: Professional tone, clear next step.

## ClawPilot Prompts

### 1) Expense Workflow Preparation
Context: I have multiple receipts and categories.
Goal: Prepare a draft expense submission package.
Constraints: Flag missing fields and policy mismatches.
Output format: Checklist + categorized summary.
Quality criteria: Submission-ready draft with review notes.

### 2) Action Tracker Build
Context: I have meeting notes and commitments.
Goal: Convert notes to a clean action tracker.
Constraints: Include owner, deadline, risk, dependency.
Output format: Action table + priority ordering.
Quality criteria: No ambiguous owners or dates.
