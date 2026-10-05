# Human-AI Control Framework

## Experiment

**AI Automation Test #1 — Brand Awareness & Market Entry**

## Purpose

This framework defines how responsibility and decision authority were allocated between humans and AI within the AI-enabled process.

The purpose was to ensure that AI integration increased human capacity without removing appropriate human judgement, accountability, or control.

The framework distinguishes between:

> **Automation → Augmentation → Human Authority**

These categories were used to determine how different types of work should be handled.

---

## 1. Automation

### Definition

Automation refers to activities that AI can perform under defined conditions where the activity does not require independent human judgement at every step.

Suitable activities may include:

* structured information processing;
* repetitive preparation;
* formatting;
* summarisation;
* initial classification;
* drafting;
* pattern identification;
* and other defined operational activities.

### Conditions

Automation should only occur where:

1. the task is sufficiently defined;
2. the expected output can be evaluated;
3. appropriate safeguards exist;
4. the consequences of an incorrect output are understood;
5. and human intervention remains possible where required.

Automation does not mean that AI receives unrestricted authority.

---

## 2. Augmentation

### Definition

Augmentation refers to activities where AI increases human capacity while the human remains responsible for judgement or approval.

Examples include:

* analytical support;
* research assistance;
* synthesis of information;
* option generation;
* content development;
* interpretation support;
* and decision preparation.

The AI may perform substantial work, but the human remains responsible for determining whether the resulting information or recommendation should be accepted.

---

## 3. Human Authority

### Definition

Human authority applies where a decision requires strategic judgement, accountability, contextual interpretation, ethical consideration, or has meaningful business consequences.

Human authority was retained for:

* strategic direction;
* consequential decisions;
* ambiguous situations;
* risk-sensitive decisions;
* brand decisions;
* financial commitments;
* public-facing approval;
* and decisions where evidence was insufficient.

The principle was:

> **AI can support the decision without owning the decision.**

---

# Decision Authority Framework

| Activity Type              | AI Role           | Human Role            |
| -------------------------- | ----------------- | --------------------- |
| Repetitive structured work | Automate          | Oversight             |
| Information processing     | Automate / Assist | Review where required |
| Research synthesis         | Assist            | Interpret             |
| Drafting                   | Assist            | Review / Approve      |
| Strategic recommendation   | Assist            | Decide                |
| Brand positioning          | Assist            | Decide                |
| Budget allocation          | Assist            | Decide / Approve      |
| Public publication         | Assist            | Approve               |
| Risk-sensitive decisions   | Assist            | Decide                |
| Ambiguous situations       | Assist            | Decide                |
| Learning interpretation    | Assist            | Validate              |
| Process changes            | Recommend         | Approve               |

---

# Human Approval Gates

Human approval was retained at points where an incorrect or inappropriate AI output could create meaningful consequences.

Approval requirements applied particularly to:

### Strategic Decisions

AI-generated recommendations do not automatically become strategy.

A human must determine whether the recommendation is appropriate to the business objective and context.

### Brand Decisions

AI-generated content or recommendations affecting positioning, tone, reputation, or public identity require human judgement.

### Publication

Public-facing outputs require appropriate human approval before release.

### Financial Decisions

Budget commitments and financial decisions remain under human authority.

### Risk Escalation

Where an output creates material uncertainty, contradiction, risk, or potential harm, the process should escalate to human review.

---

# Evidence and Confidence Controls

AI outputs should not automatically be treated as factual simply because they are confidently presented.

The process therefore distinguishes between:

* verified evidence;
* supported inference;
* uncertain information;
* missing information;
* and unsupported assumptions.

Where evidence is insufficient, the appropriate response may be:

> **Stop → Investigate → Escalate**

rather than automatically generating an answer.

---

# Audience Relevance Control

The process should distinguish between:

> **Attention**

and

> **Meaningful relevance.**

High reach, impressions, or engagement should not automatically be interpreted as successful performance.

The process must consider whether the activity reached the intended audience and generated signals relevant to the campaign objective.

---

# Brand Protection Control

AI-generated work may be technically polished while still being strategically or culturally inappropriate for the brand.

Outputs should therefore be assessed against:

* positioning;
* intended audience;
* brand voice;
* strategic objective;
* contextual relevance;
* and reputational considerations.

Human judgement remains the final authority for consequential brand decisions.

---

# Causality Control

Observed changes should not automatically be interpreted as evidence that a specific marketing activity caused the outcome.

Where causality cannot reasonably be established, the process should distinguish between:

> **Observed change**

and

> **Confirmed causal effect.**

This reduces the risk of making strategic decisions based on false attribution.

---

# Missing Data Control

Missing information should be treated as a recognised condition.

The process should not silently replace missing data with assumptions.

Where important information is unavailable, the system should:

1. identify the gap;
2. determine whether the gap affects the decision;
3. seek additional evidence where appropriate;
4. or escalate to human judgement.

---

# Publication Control

AI-generated outputs should not automatically move from generation to publication.

The process should provide an appropriate review point before external release.

The level of review should reflect the potential consequences of the publication.

Higher-risk public outputs require stronger human oversight.

---

# Budget Control

AI may support analysis or recommendations relating to spend, but authority over financial commitments remains human.

The process should not permit AI-generated recommendations to independently create financial obligations without appropriate approval.

---

# Intervention and Escalation

Human intervention should remain possible throughout the process.

Intervention is particularly appropriate when:

* evidence is insufficient;
* confidence is low;
* outputs contradict available information;
* the request falls outside defined conditions;
* the output creates brand or reputational risk;
* the decision has significant financial implications;
* or the consequences of an error are material.

The intended operating principle is:

> **Automate where safe. Assist where useful. Escalate where uncertain. Retain human authority where consequential.**

---

# Learning Governance

Stage 14 introduced a mechanism for incorporating learning into future decision-making.

However, learning should not automatically become permanent system behaviour.

Before learning is incorporated into future process decisions, it should be considered for:

* validity;
* relevance;
* evidence;
* repeatability;
* context;
* and potential unintended consequences.

Human governance therefore remains part of the learning loop.

---

# Core Principle

The framework can be summarised as:

> **AI should increase capability without transferring accountability.**

The objective of the control framework is therefore not to minimise human involvement.

It is to ensure that human involvement is concentrated where human judgement creates the greatest value and where accountability cannot appropriately be delegated.

---

# Evidence Boundary

This framework represents the control architecture designed within the controlled experiment.

It does not establish that these controls have been validated through live production automation.

Future testing should examine whether the framework remains effective when exposed to:

* real system failures;
* unexpected inputs;
* live data;
* production-scale workloads;
* repeated execution;
* and real-world decision consequences.
