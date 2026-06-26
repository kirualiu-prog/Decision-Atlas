# Question Analysis Workflow

This workflow turns Decision Atlas from a library into a practical answering process.

Use it when someone gives you a real question and you want to route it to the most relevant models before answering.

## Goal

Move in this order:

1. Understand the real question
2. Route it to the right problem type
3. Pick the smallest useful model set
4. Extend with adjacent and opposing models
5. Synthesize one answer with clear reasoning

## Step 1 — Restate the Question

Before choosing models, rewrite the question in a cleaner form.

Example:

- Raw question: "Should we expand now?"
- Restated question: "Should we commit resources now to expanding into a new market, given uncertainty about demand, competitive response, and opportunity cost?"

Do not route a vague question before making it explicit.

## Step 2 — Classify the Problem

Pick the dominant problem type first.

### Information Problem

Use when the issue is about:

- whether evidence is reliable
- whether a pattern is real
- whether the sample is too small

Start with:

- DS-001 Base Rate
- DS-002 Bayesian Updating
- DS-097 Signal vs Noise

### Choice Problem

Use when the issue is about:

- choosing between options
- allocating limited resources
- making trade-offs explicit

Start with:

- DS-041 Opportunity Cost
- DS-042 Trade-off
- DS-043 Decision Matrix

### Root-Cause Problem

Use when the issue is about:

- why something is happening
- what the real cause is
- where the bottleneck sits

Start with:

- DS-031 First Principles
- DS-033 Root Cause Analysis
- DS-035 Issue Tree

### System Problem

Use when the issue is about:

- unintended consequences
- feedback loops
- time delays
- interacting moving parts

Start with:

- DS-048 Second-order Thinking
- DS-056 Systems Mapping
- DS-061 Delay

### Strategy Problem

Use when the issue is about:

- competitive position
- advantage and defensibility
- expansion and market moves

Start with:

- DS-071 Competitive Advantage
- DS-075 Value Chain
- DS-080 Optionality

### Behavior Problem

Use when the issue is about:

- incentives
- user behavior
- organizational misalignment
- default-driven choices

Start with:

- DS-081 Incentives
- DS-086 Default Effect
- DS-090 Principal-Agent Problem

### Innovation Problem

Use when the issue is about:

- generating options
- reframing the problem
- understanding the job behind demand

Start with:

- DS-091 Divergent Thinking
- DS-093 Lateral Thinking
- DS-095 Jobs to Be Done

## Step 3 — Pick Core Models

Choose only 2 to 3 core models first.

Rule:

- 1 model is too narrow
- 2 to 3 models is usually enough
- more than 5 too early usually means model collecting, not thinking

## Step 4 — Extend the Model Set

After choosing core models, extend in two directions.

### Adjacent Models

Use `related` models and neighboring models from the same category.

Purpose:

- add nearby perspectives
- deepen the primary line of reasoning

### Opposing Models

Always add 1 to 2 challenge models.

Default challenge set:

- DS-097 Signal vs Noise
- DS-098 Inversion
- DS-099 Red Team Thinking

Purpose:

- reduce overconfidence
- catch missing assumptions
- test whether the first answer survives challenge

## Step 5 — Synthesize

Do not answer by listing models.

Answer by integrating them.

Good synthesis means:

- each model changes the interpretation
- the models are connected
- the answer ends with a recommendation, not a reading list

## Output Format

Use this fixed shape:

### 1. Restated Question

Rewrite the problem clearly.

### 2. Problem Type

State the primary type and any secondary type.

### 3. Core Models

List the 2 to 3 main models and why each one matters.

### 4. Extension Models

List the adjacent and challenge models and why they were added.

### 5. Integrated Answer

Give the actual answer after combining the models.

### 6. Recommendation

State what to do next.

### 7. Missing Information

State what evidence would most change the answer.

## Example

Question:

> Should we expand into a new market this quarter?

Route:

- Primary type: Strategy Problem
- Secondary type: Choice Problem

Core models:

- DS-071 Competitive Advantage
- DS-080 Optionality
- DS-041 Opportunity Cost

Extension models:

- DS-075 Value Chain
- DS-076 Porter's Five Forces
- DS-098 Inversion
- DS-099 Red Team Thinking

Integrated answer:

- If the current advantage does not transfer, expansion is weaker than it looks.
- If the move is reversible, a small test is better than a full commitment.
- If the resource cost weakens the core business, the real downside is larger than the expansion case suggests.

Recommendation:

- Do not fully expand yet.
- Run a low-commitment market test first.

Missing information:

- market demand quality
- likely competitor response
- true internal opportunity cost

## Practical Rule

Use Decision Atlas like this:

- start from the problem
- choose the smallest useful model set
- add one challenge layer
- answer only after synthesis

If the output is just "here are some models," stop and do one more pass.
