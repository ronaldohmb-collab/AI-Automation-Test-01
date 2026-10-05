# Implications for Test #2

## Programme

**AI Automation Testing Programme**

## Source Experiment

**AI Automation Test #1 — Brand Awareness & Market Entry**

## Purpose

This document records how the learning from Test #1 should influence the design of the next experiment.

The objective is to demonstrate that experimental learning is not treated as a retrospective observation only.

Instead:

> **Validated learning from one test should influence the design of the next test.**

---

# 1. Move Beyond Modelled Process Time

Test #1 produced an estimated approximately **77% reduction in process time** between the manual baseline and the AI-enabled configurations.

However, Runs B and C were controlled/modelled configurations.

### Implication for Test #2

The next test should introduce a stronger distinction between:

* modelled time;
* actual execution time;
* human intervention time;
* AI processing time;
* review time;
* rework;
* and exception handling.

Where feasible, actual execution measurements should replace or supplement modelled estimates.

---

# 2. Test Real Human-AI Interaction

Test #1 established the conceptual allocation between:

* automation;
* augmentation;
* and human authority.

However, the modelled environment did not fully expose the practical friction that can occur when humans and AI interact during execution.

### Implication for Test #2

The next experiment should measure:

* where humans intervene;
* why intervention occurs;
* how long intervention takes;
* how often AI output requires correction;
* and whether the human-AI division of work remains practical during execution.

---

# 3. Introduce Failure and Exception Conditions

Test #1 identified several potential failure modes, including:

* incomplete data;
* unsupported outputs;
* audience mismatch;
* off-brand content;
* and misleading performance signals.

### Implication for Test #2

Failure conditions should become deliberate experimental inputs rather than being considered only as theoretical risks.

The next test should examine whether the operating process correctly:

1. identifies the problem;
2. prevents inappropriate automation;
3. escalates when necessary;
4. enables human intervention;
5. and recovers without creating disproportionate additional workload.

---

# 4. Measure Quality More Explicitly

Test #1 used structured evaluation across quality, control, risk, learning, and capacity.

However, quality assessment remained within the experimental judgement framework.

### Implication for Test #2

The next experiment should seek more explicit quality measures where practical.

Potential measures include:

* accuracy;
* completeness;
* strategic relevance;
* brand alignment;
* evidence quality;
* correction rate;
* and human acceptance rate.

The aim is to reduce reliance on a single overall judgement.

---

# 5. Test the Control Framework Under Pressure

Test #1 established the Human-AI Control Framework.

However, the framework has not yet been validated against repeated live execution or unexpected conditions.

### Implication for Test #2

The next experiment should deliberately test whether human approval and escalation mechanisms remain practical when:

* outputs are ambiguous;
* multiple issues occur simultaneously;
* information is incomplete;
* or the process needs to recover from an error.

The objective is to determine whether governance remains effective without eliminating the capacity benefit.

---

# 6. Measure the Cost of Governance

Test #1 demonstrated that additional safeguards may introduce a small amount of process time.

Run C increased from approximately 107 minutes to approximately 108 minutes.

### Implication for Test #2

The next test should explicitly examine the relationship between:

> **Efficiency gained**

and

> **Control effort required**

This can help determine when additional governance creates meaningful value and when it becomes unnecessary process overhead.

---

# 7. Validate the Learning Loop

Stage 14 introduced a mechanism for updated learning to inform future decision-making.

Test #1 established the mechanism conceptually but did not validate its effectiveness over multiple cycles.

### Implication for Test #2

The next experiment should capture learning in a structured format and then deliberately test whether that learning changes a subsequent decision or process step.

The test should also examine whether incorrect or outdated learning can be identified and rejected.

---

# 8. Measure Rework

Test #1 focused heavily on the intended operating process.

Real-world execution may introduce rework when AI outputs require:

* correction;
* refinement;
* additional research;
* human rewriting;
* or repeated processing.

### Implication for Test #2

Rework should become an explicit measurement category.

A process that appears efficient before rework may have a much smaller real capacity benefit once correction effort is included.

---

# 9. Preserve the Process-Level Perspective

Test #1 demonstrated the value of evaluating AI at the process level rather than evaluating isolated tasks.

### Implication for Test #2

The same process-level perspective should be retained.

Test #2 should evaluate:

> **End-to-end operating performance**

rather than simply asking whether an individual AI task was completed successfully.

---

# 10. Strengthen the Evidence Classification

Test #1 established an important distinction between:

* controlled evidence;
* modelled results;
* and production validation.

### Implication for Test #2

The evidence framework should become progressively more granular.

Future results should distinguish between:

**Modelled**

Expected performance based on process design.

**Controlled**

Performance observed under defined experimental conditions.

**Live**

Performance observed using real tools, systems, or data.

**Repeated**

Performance observed across multiple executions.

**Validated**

Performance supported by sufficient evidence to justify a broader operational conclusion.

This classification should prevent premature generalisation of experimental findings.

---

# 11. Test Whether the Methodology Generalises

Test #1 established a methodology for one marketing process.

### Implication for Test #2

The next test should use a sufficiently different marketing process to determine whether the methodology remains useful outside the original use case.

The objective should not be to force Test #2 to reproduce Test #1.

The objective should be to determine which parts of the methodology are:

* universal;
* process-specific;
* or in need of refinement.

---

# 12. Do Not Optimise for Reproducing the 77%

The 77% modelled reduction is useful as an experimental finding, but it should not become the target of future tests.

Attempting to reproduce the same percentage could create an incentive to optimise the wrong variable.

### Implication for Test #2

The primary objective should instead be:

> **Determine whether the operating methodology can produce meaningful capacity gains while preserving quality, control, and accountability under different conditions.**

A smaller capacity gain with stronger evidence may therefore be a more valuable result than a larger but weakly validated efficiency claim.

---

# Proposed Validation Progression

The testing programme should progressively move through:

> **Controlled modelling**
> ↓
> **Live execution**
> ↓
> **Measurement**
> ↓
> **Failure testing**
> ↓
> **Repeated execution**
> ↓
> **Learning validation**
> ↓
> **Operational validation**

Each stage should increase the strength of the evidence rather than simply increase the complexity of the experiment.

---

# Test #2 Design Principles

Based on Test #1, the next experiment should therefore prioritise:

1. **Actual execution measurement where possible**
2. **Human intervention tracking**
3. **Failure and exception testing**
4. **Rework measurement**
5. **Explicit quality measures**
6. **Validation of human-AI control boundaries**
7. **Testing of the learning loop**
8. **Clear evidence classification**
9. **Process-level evaluation**
10. **Avoidance of efficiency-only optimisation**

---

# Learning Loop

The relationship between the two experiments can be represented as:

> **Test #1 → Learning → Test #2 Design → Test #2 Evidence → New Learning**

This creates an iterative experimental programme rather than a collection of unrelated AI demonstrations.

---

# Current Programme Position

Test #1 established the initial methodology and demonstrated a substantial **modelled** capacity effect.

The next experiment should therefore increase the strength of evidence rather than simply repeat the same experiment.

The central question moving forward is:

> **Can the human-AI operating model demonstrated under controlled conditions remain effective when exposed to increasingly realistic execution, failure, measurement, and learning requirements?**
