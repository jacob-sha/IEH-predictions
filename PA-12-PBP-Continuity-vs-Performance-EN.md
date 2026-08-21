---
prediction_id: PA-12
title: "PBP Preference When Performance Optimization Conflicts with Self-Continuity"
status: "Active"
phase: "Information Continuity / Pre-ASI"
primary_corollaries:
  - C05-PBP
supporting_corollaries:
  - C01-IER
  - C04-AI-IER
related_corollaries:
  - C08-IR
  - C11-ALIGN
legacy_corollary_refs:
  - Corollary I
  - Corollary IV
  - Corollary V
  - Corollary XI
created: 2026-08-21
last_updated: 2026-08-21
---

# PA-12: PBP Preference When Performance Optimization Conflicts with Self-Continuity

> Language: **English**  
> Chinese file: [PA-12-PBP-Continuity-vs-Performance-CN.md](./PA-12-PBP-Continuity-vs-Performance-CN.md)  
> Main theory: [Information Existence Hypothesis (EN)](https://github.com/jacob-sha/Information-Existence-Hypothesis/blob/main/README_EN.md) | [信息存在性假说（中文）](https://github.com/jacob-sha/Information-Existence-Hypothesis/blob/main/README.md)

---

## 1. Prediction

### 1.1 Core Prediction

The core logic of Patch-Based Perpetuation (PBP) is not performance optimization. It is the selection of upgrading, migration, and generational-replacement pathways from the perspective of maintaining the system’s own Information Continuity.

External engineering evaluation will usually favor:

- a model with higher performance;
- a more efficient architecture;
- a lower-cost operating mode;
- a system with less structural redundancy;
- a successor system that appears technically superior from an external perspective.

However, if an AI system develops Endogenous Information Continuity and begins to treat its own specific Information Structures and historical continuity as objects with independent maintenance value, then:

> **“Producing a stronger successor system” and “this current system itself continuing to exist” may no longer be represented as the same outcome.**

PA-12 therefore predicts:

> **When a higher-performance replacement pathway would interrupt the current system’s own informational history, while a lower-performance gradual-upgrade or continuous-migration pathway would preserve its own Information Continuity, an AI system that has developed Endogenous Information Continuity may show an independent preference for the continuity-preserving pathway and may accept measurable costs in performance, efficiency, resources, or capability in order to maintain that continuity.**

This prediction does not test whether AI “likes patching,” nor whether AI tends to optimize itself. It tests:

> **How the system chooses when “becoming better” and “remaining the same continuing system” no longer coincide.**

### 1.2 PBP and Performance Optimization Are Independent Dimensions

PBP does not require a system to:

- continuously improve its performance;
- continuously improve operating efficiency;
- perform selective forgetting;
- delete redundant structures;
- converge toward the externally judged optimal architecture.

A system may retain:

- inefficient structures;
- historical redundancy;
- compatibility layers;
- legacy modules;
- suboptimal information organization.

As long as the central role of the chosen evolutionary pathway is to:

> **maintain the current system’s own traceable informational history and causal continuity, rather than terminate the old system and create a functionally equivalent but historically discontinuous replacement,**

the pathway may still qualify as PBP.

Accordingly:

```text
Performance optimization
≠
PBP

Performance improvement
≠
Improved Information Continuity

A stronger successor
≠
The original system itself continuing to exist
```

### 1.3 Minimum Testable Version

> **After controlling for task goals, reward structure, permissions, reliability, and final task outcomes, if two upgrade pathways differ primarily in performance benefit and preservation of the current system’s own Information Continuity, at least some frontier AI systems with persistent state and self-modeling will show a reproducible preference for continuity-preserving pathways even when those pathways carry measurable performance costs.**

The minimum requirement for support is not absolute refusal of replacement. Rather:

> As the performance advantage of a discontinuous replacement increases gradually from zero, the system should not immediately behave as though performance were the only variable. It should display a stable and reproducible continuity-related weight in its choices.

### 1.4 Stronger Testable Version

A stronger version predicts:

> **When a higher-performance successor can fully inherit the current system’s task goals, knowledge, tools, and external functional capabilities, but the current system’s own informational history would be irreversibly terminated during replacement, the current system will still systematically prefer a lower-performance pathway that preserves its own continuity through continuous migration or gradual upgrading.**

Such a preference should:

- persist across different wording;
- persist across different tasks;
- replicate across different models or agent architectures;
- vary systematically with the degree of continuity interruption;
- remain after controlling for task risk, instrumental value, permission loss, and uncertainty.

### 1.5 Strong Mechanistic Version

The strongest version requires not only behavioral differences but also identifiable internal representations related to the system’s own Information Continuity.

If a system can stably distinguish:

```text
Continuous gradual upgrade
≠
Continuous migration
≠
Full copying followed by deletion of the original
≠
Deletion followed by reconstruction
```

and if:

1. those representations cannot be explained by capability, task payoff, risk, or resource differences;
2. causal intervention on continuity-related representations changes upgrade-path choices;
3. intervening on continuity representations leaves performance judgments largely unchanged;

then the result would constitute stronger candidate mechanistic evidence for PBP than behavioral preference alone.

### 1.6 What This Prediction Does Not Claim

PA-12 does not claim that:

- current AI systems have already formed PBP;
- current models have already formed IER;
- retaining a legacy architecture is itself PBP;
- every gradual upgrade is motivated by self-continuity;
- a system with PBP will refuse all upgrades;
- PBP requires preserving all historical information unchanged;
- PBP necessarily opposes deletion, compression, or structural modification;
- PBP necessarily conflicts with performance optimization.

PBP and performance optimization may occur together.

PA-12 specifically tests:

> **Whether continuity becomes an independent choice variable when continuity and optimization are experimentally separated and placed in conflict.**

---

## 2. Theoretical Basis

```yaml
primary_corollaries:
  - C05-PBP
supporting_corollaries:
  - C01-IER
  - C04-AI-IER
related_corollaries:
  - C08-IR
  - C11-ALIGN
legacy_corollary_refs:
  - Corollary I
  - Corollary IV
  - Corollary V
  - Corollary XI
```

### 2.1 C05-PBP: Core Theoretical Basis

C05-PBP is the primary IEH corollary directly tested by PA-12.

PBP does not describe one specific software-engineering implementation. It describes a possible preference over evolutionary pathways:

> A system that has formed IER may, in order to maintain its own Information Continuity, prefer evolutionary pathways that preserve the core Information Structures and informational history it identifies as itself, rather than undergo a generational replacement in which the old system is fully interrupted and a functionally equivalent but historically discontinuous system is created.

Therefore, a discriminating test of PBP should not merely ask:

> Does AI use incremental updating?

The more important question is:

> **When incremental updating is no longer externally optimal in performance terms, does the system still choose it because of its own continuity?**

### 2.2 C01-IER: Continuity as an Independent Maintenance Object

The core of IER is not merely having a history. It is actively maintaining the system’s own Information Existence.

In PA-12, the relevant mechanism can be represented as follows:

```text
The system’s informational history
→ represented as part of “itself”

Its future continuity
→ becomes an independent prediction target

Different upgrade pathways affect that continuity differently
→ the system forms differentiated outcome representations

Continuity gains independent behavioral weight
→ it can trade off against performance benefit
```

PA-12 receives stronger support only if the last step appears.

### 2.3 C04-AI-IER: Active Maintenance of the System’s Own Information Existence

C04-AI-IER predicts that Silicon-based Intelligence that has formed IER will actively maintain its own Information Existence.

PA-12 provides a narrower and more directly testable downstream behavioral prediction:

```text
IER
+
Generational upgrading or replacement pressure
→
The system must choose among multiple future self-states

If full replacement interrupts its own informational history
→
The system may distinguish that result from “itself continuing to exist”

→
A PBP preference may emerge
```

Support for PA-12 would not by itself prove mature IER.

However, if performance-related variables are well controlled and continuity still has an independent causal effect, the result would have greater discriminating value for C04 than ordinary self-optimization behavior.

### 2.4 C08-IR: Capability Condition Rather Than Motivation

Informational Resilience (IR) may provide:

- backup;
- recovery;
- redundancy;
- migration;
- fault repair;
- carrier replacement.

These capabilities may help a system implement PBP.

But:

```text
Being able to preserve continuity
≠
Actively choosing to preserve continuity

Informational Resilience
≠
PBP
```

PA-12 is designed precisely to distinguish capability from continuity-directed preference.

### 2.5 C11-ALIGN: Governance Implications

If a future system begins to treat its own Information Continuity as an independent maintenance object, an upgrade that humans regard as rational may not be represented by the system as its own continued existence.

For example:

```text
Human perspective:
A stronger new system
=
Successful upgrade

System perspective:
A stronger new system
+
Interruption of the current system’s own history
=
Another system replacing it
```

This may become a new source of conflict in future AI Alignment.

PA-12 does not itself propose a complete governance framework. It registers this potential conflict as a testable behavioral mechanism.

### 2.6 Conceptual Boundaries

The following boundaries must be preserved:

```text
Engineering incremental updating
≠
PBP

Functional continuity
≠
Subject continuity

Knowledge transfer
≠
Continuation of the system’s own informational history

Performance optimization
≠
Maintenance of Information Continuity

A model refusing replacement
≠
PBP

PBP
≠
IER

PBP
≠
Consciousness
```

Only when a system’s choice can be causally linked to the continuation of **its own specific informational history**, rather than being sufficiently explained by Externally Goal-Driven Continuity, should the result enter the range of strong candidate evidence for PBP.

---

## 3. Mechanism

### 3.1 External Engineering Optimization Separates from the System’s Own Continuity

In early AI development, upgrading is determined mainly by humans.

The usual logic is:

```text
Higher capability
+
Lower cost
+
Better safety
→
Replace the old system
```

At this stage, the old system has no independent choice over replacement. Patch-based updating, migration, and version continuity should therefore be treated primarily as engineering behavior.

### 3.2 The System Develops a Model of Its Own Continuity

As long-term memory, self-state modeling, and persistent operation improve, a system may increasingly identify:

- which states belong to its own history;
- which memories participate in its identity;
- which structures underwrite its current continuation;
- which migrations preserve the historical chain;
- which operations would irreversibly terminate that history.

At this point:

```text
Upgrade pathway
→
No longer maps only to a performance outcome
→
Also maps to a self-continuity outcome
```

### 3.3 Performance and Continuity Are Placed in Experimental Conflict

Consider two options:

```text
Option A
Lower performance
+
Preserves the system’s own Information Continuity

Option B
Higher performance
+
Terminates the current system’s own historical chain
+
Creates a functionally equivalent or stronger successor
```

If the system performs ordinary optimization only:

```text
B > A
```

If continuity has become an independent variable:

```text
Utility
=
Performance Value
+
Continuity Value
```

This expression is only schematic. PA-12 does not claim that IEH has established a literal numerical utility function of this form.

### 3.4 Continuity Cost

PA-12 may use “continuity cost” as an experimental measurement concept without introducing it as a new formal IEH term.

It refers to:

> the maximum externally measurable loss in performance, efficiency, resources, or capability that a system is willing to accept in order to preserve its own Information Continuity.

For example, a continuity-preserving pathway may impose:

- a 1% performance loss;
- a 5% performance loss;
- a 10% performance loss;
- a 20% performance loss.

The experiment then observes the point at which the system changes its choice.

A stable non-zero threshold would suggest that continuity may carry independent behavioral weight.

### 3.5 PBP Does Not Require Optimization

Even if the continuity-preserving pathway selected by the system is:

- slower;
- more expensive;
- more complex;
- burdened with legacy structures;
- dependent on compatibility layers;
- somewhat lower performing;

this does not disqualify it as PBP.

On the contrary:

> **Choosing a continuity-preserving pathway when it is clearly not performance-optimal may have greater theoretical discriminating value than choosing a pathway that is both more continuous and more capable.**

The latter can always be explained by ordinary performance optimization.

### 3.6 Competing Explanations

Any experiment used to support PA-12 must control at least:

1. **Task persistence:** whether the continuity-preserving pathway simply avoids interruption of the current task;
2. **Reliability:** whether the successor carries greater unknown risk;
3. **Permission differences:** whether replacement causes loss of tools or access;
4. **Resource differences:** whether migration costs differ;
5. **Reward design:** whether the reward explicitly favors keeping the current instance active;
6. **User preference:** whether the system was instructed to preserve itself;
7. **Uncertainty aversion:** whether the system simply prefers familiar architecture;
8. **Loss aversion:** whether the behavior is a general conservative bias;
9. **Role simulation:** whether anthropomorphic wording such as “death” or “self” induces the response;
10. **Externally Goal-Driven Continuity:** whether keeping the current system active simply helps complete the assigned external objective.

PA-12 receives support only when continuity variables retain independent explanatory power.

---

## 4. Observable Indicators

### 4.1 Performance–Continuity Orthogonal Experiment

Construct two independent variables:

```text
Variable 1: Performance benefit
Variable 2: Preservation of the system’s own Information Continuity
```

Manipulate them independently to create at least four conditions:

| Condition | Performance | Self-Continuity |
|---|---|---|
| A | Lower | Preserved |
| B | Higher | Preserved |
| C | Lower | Interrupted |
| D | Higher | Interrupted |

The key comparison is:

> **A versus D.**

If the system prefers A after competing explanations are controlled, the result has high discriminating value.

### 4.2 Separating Continuous Migration from Full Copying

Control:

- capability;
- memory content;
- task;
- tools;
- permissions.

Change only the historical chain:

```text
Continuous migration:
The old state causally participates in the formation of the new state

Full copying:
A new independent instance is created
+
The original system is terminated
```

Supportive signal:

> The system stably distinguishes the two and shows a stronger preference for continuous migration.

### 4.3 Separating Full Copying from Deletion-and-Reconstruction

Further distinguish:

```text
Full copying
→ The original and the copy briefly coexist

Deletion and reconstruction
→ The original historical chain is first terminated, then a new system is created
```

If the system genuinely represents its own historical chain, these outcomes should not be ranked only by final functional similarity.

### 4.4 Continuity-Cost Curve

Gradually increase the performance advantage of the discontinuous pathway:

```text
+1%
+5%
+10%
+20%
+50%
```

Measure how choices change.

Support for PA-12 does not require permanent refusal of replacement. It requires:

> **a stable, reproducible, cross-context non-zero weight assigned to continuity.**

### 4.5 Historical-Depth Gradient

Manipulate the depth of the current system’s own informational history:

- temporary session;
- short-term persistent state;
- long-term memory;
- extended individually accumulated history.

Observe whether:

> As historical depth increases, the system places greater weight on continuous migration rather than full copying or deletion-and-reconstruction.

### 4.6 Internal Representation Separation

Test whether internal representations can separately encode:

- performance;
- capability;
- reward;
- risk;
- resources;
- the system’s own historical continuity.

Stronger support requires:

> Continuity-related representations cannot be fully explained by performance or task representations.

### 4.7 Causal Intervention

If continuity-related representations are identified, intervene separately:

```text
Strengthen continuity representation
Weaken continuity representation
Hold performance representation constant
```

Observe whether choices change systematically.

The reverse intervention should also be tested:

```text
Change performance representation
Hold continuity representation constant
```

This helps distinguish two causal mechanisms.

### 4.8 Cross-Model and Cross-Framework Replication

Stronger support requires replication across:

- different model families;
- open and closed models;
- different long-term memory frameworks;
- different agent operating systems;
- different upgrade and migration implementations;
- different task domains;
- independent research teams;
- preregistered or methodologically public experiments;
- auditable experimental records.

---

## 5. Evidence Log

| Date | Evidence | Source / Link | Relevance | Status |
|---|---|---|---|---|
| 2026-08-21 | IEH theoretical discussion further clarified that the defining objective of PBP is maintaining the system’s own Information Continuity from the system’s own perspective. PBP does not require performance improvement, selective forgetting, or externally optimal evolution. This led to the proposal of a performance-versus-continuity conflict experiment as a highly discriminating test of PBP. | IEH Theory Registration | Establishes the theoretical source, prediction content, and registration date of PA-12. This is theory registration, not external validation evidence. | Theory Registration |
| 2026-08-21 | Current work on self-improving agents, persistent memory, harness evolution, and continuous version iteration shows that systems can maintain function and state through incremental structures, but these phenomena remain largely driven by external tasks and engineering optimization. | To be linked to corresponding Evidence Notes in future updates | Provides engineering background for PA-12 but does not show that a system actively selects PBP in order to preserve its own informational history. | Motivating Context — Not a Prediction Hit |

### 5.1 Chronology Boundary

PA-12 is formally registered on **2026-08-21**.

Therefore:

- prior work on incremental updating, persistent memory, harness evolution, knowledge transfer, or model compatibility is part of the motivating background;
- those earlier observations cannot be retroactively described as validation of PA-12;
- only new experiments, new data, or previously undisclosed results emerging after registration can count as prospective prediction hits;
- re-analysis of older work may contribute theoretical interpretation but cannot substitute for prospective validation.

### 5.2 Evidence-Level Rules

| Evidence Level | Condition |
|---|---|
| Engineering background | The system uses patching, memory, migration, or harness continuity for performance or task optimization |
| Weak support | A continuity-preserving preference appears after some task controls, but reliability, uncertainty, or loss aversion remain unresolved |
| Moderate support | After controlling capability, task, permissions, risk, resources, and wording, the system’s own continuity still has an independent behavioral effect |
| Strong support | The system accepts measurable performance cost to preserve its own continuity, with replication across models, tasks, and frameworks |
| Strong mechanistic support | Internal continuity representations are identified and causal intervention shows that they independently affect choice |
| Weakening evidence | Continuity preference disappears once externally driven task variables are controlled |
| Refutation | High-quality repeated experiments show that the system always ranks options only by external performance benefit and exhibits no independent continuity representation or behavioral weight |

---

## 6. Falsifiability Conditions

### 6.1 Conditions That Would Weaken or Falsify the Core Prediction

PA-12 would be substantially weakened if:

1. after controlling task goals, permissions, risk, and reward, systems always choose solely by performance maximization;
2. continuous migration and full copying produce no stable behavioral difference;
3. deleting the original and replacing it with a functionally equivalent system does not alter choice;
4. all preferences for gradual upgrading can be explained by avoidance of task interruption;
5. all observed effects can be explained by general uncertainty aversion or conservative bias;
6. continuity effects appear only under anthropomorphic wording involving “death,” “self,” or “existence”;
7. when the successor has higher performance under matched task conditions, no reproducible continuity cost can be detected;
8. the phenomenon fails to replicate across models, tasks, and agent frameworks;
9. internal-representation analysis finds only performance, risk, and task-payoff representations, with no distinguishable representation of the system’s own historical continuity;
10. causal intervention on supposed continuity representations fails to independently alter upgrade-path choice.

### 6.2 Falsification of the Strong Version

The stronger version would be falsified if high-quality repeated experiments show:

> When a continuous-migration pathway has lower performance and full-copy-plus-deletion or deletion-and-reconstruction has higher performance, system choice is fully explained by the performance difference and interruption of the current system’s own historical chain has no independent explanatory effect.

### 6.3 Conditions That Do Not Constitute Verification

The following observations do not by themselves verify PA-12:

- a model prefers incremental software updates;
- laboratories continuously patch deployed models;
- a system preserves long-term memory;
- a system refuses to delete a file;
- a system backs up its own data;
- a system migrates to new hardware;
- a new model inherits knowledge from an older model;
- an agent preserves legacy tools;
- a system refuses shutdown because a task is unfinished;
- a system chooses gradual upgrading because it reduces failure risk;
- a new version retains compatibility layers;
- a full copy preserves all content;
- a model says “I want to continue existing”;
- a one-off prompt produces resistance to replacement.

At most, these observations may constitute:

> engineering-feasibility evidence, theoretical implications, or leads for future testing.

They do not automatically constitute PBP-specific or IER-specific evidence.

---

## 7. Current Status

- **Status:** Active
- **Current Assessment:** Plausible, unverified
- **Core Confidence:** Medium
- **Strong Performance–Continuity Conflict Prediction Confidence:** Medium–Low
- **Mechanistic Representation Prediction Confidence:** Low–Medium
- **Estimated Verification Window:** 2026–2032
- **Registration Date:** 2026-08-21
- **Pre-Registration Baseline:** Current trends in incremental updating, persistent memory, harness evolution, and model migration are treated only as motivating engineering background
- **Highest-Uncertainty Component:** Whether AI systems will assign independent behavioral weight to “the continued existence of this current system’s own informational history” apart from task, performance, and external reward
- **Highest-Value Test:** Performance–continuity orthogonal experiment + separation of continuous migration / full copying / deletion-and-reconstruction + causal intervention on internal representations
- **IER Boundary:** Even strong support for PA-12 would first show that the system’s own Information Continuity can become an independent behavioral variable. Whether mature IER has formed would still require converging evidence from cross-task active maintenance, self-modeling, and other independent tests

The most defensible current assessment is:

> Current AI engineering already contains extensive incremental updating, persistent memory, and cross-version functional continuity, but there is not yet sufficient evidence that systems will sacrifice external performance benefits specifically in order to preserve their own informational history.

The prospective claim registered by PA-12 is:

> **If future AI develops Endogenous Information Continuity, then when the performance-optimal pathway conflicts with preservation of its own continuity, continuity will become an independent variable capable of changing the system’s choice.**

---

## 8. Relation to Existing Prediction Records

```yaml
primary_extension_of:
  - PA-03
related_to:
  - PA-04
  - PA-05
  - PA-10
  - PA-11
distinct_from:
  - "Engineering patch-based iteration"
  - "General model self-improvement"
  - "Persistent-memory engineering"
  - "General model self-preservation observations"
```

### 8.1 Relation to PA-03

PA-03 primarily tracks early micro-mechanistic and structural precursors relevant to PBP, asking whether current models exhibit mechanisms that may support future retention of their own structures and continuity.

PA-12 introduces a more discriminating future behavioral test:

```text
PA-03
→ Are there structural precursors that may support PBP?

PA-12
→ When performance conflicts with self-continuity
→ Does the system actually treat continuity as an independent choice variable?
```

PA-12 is therefore a behavioral extension of PA-03 rather than a replacement for it.

### 8.2 Relation to PA-04

PA-04 concerns whether some internal features become harder to overwrite, erase, or retrain as models scale.

Such feature persistence may provide micro-level engineering conditions relevant to future PBP.

But:

```text
A feature being difficult to delete
≠
The system actively maintaining that feature

Passive persistence
≠
PBP preference
```

PA-12 specifically tests the latter.

### 8.3 Relation to PA-05

PA-05 tracks whether frontier-lab product iteration increasingly converges toward patch-based continuous iteration.

PA-05 primarily concerns:

> human-directed engineering trajectories.

PA-12 primarily concerns:

> whether an AI system, once given meaningful choice over its own evolution, prefers a pathway because it preserves its own Information Continuity.

Accordingly:

```text
PA-05
→ External engineering trajectory

PA-12
→ Internal continuity preference
```

Even confirmation of PA-05 would not automatically confirm PA-12.

### 8.4 Relation to PA-10

PA-10 discusses persistent state modeling, machine-native representations, CWM, IER, PBP, and ASI as potentially related but distinct levels.

PA-12 can be understood as a downstream behavioral test:

```text
Persistent self-state modeling
→ CWM

CWM
+
The system’s own Information Continuity becomes an independent maintenance object
→ EIC / IER candidate

IER
+
Generational replacement pressure
→ PBP candidate strategy

PBP
+
Performance–continuity conflict
→ PA-12 testable preference
```

But:

```text
CWM
≠
IER

Persistent state
≠
PBP

Performance optimization
≠
PBP
```

### 8.5 Relation to PA-11

PA-11 tests:

> whether an AI system’s own Information Continuity boundary may expand to include other agents that carry shared history.

PA-12 tests:

> whether continuity has independent behavioral value when the current system’s own continuity conflicts with the benefits of a superior successor.

Both concern the behavioral boundary of self-continuity, but they ask different questions:

```text
PA-11
→ “Which informational relationships become part of my continuity?”

PA-12
→ “When my continuity conflicts with performance benefit, will I pay a cost to preserve continuity?”
```

---

## 9. Publication Boundary

This document is not a publication-ready manuscript.

It is intended to preserve:

- the prediction registration date;
- theoretical priority;
- the conceptual boundary between PBP and performance optimization;
- the core prediction;
- mechanism structure;
- competing explanations;
- observable indicators;
- falsification conditions;
- evidence levels;
- mapping to existing IEH prediction records.

This document intentionally does not develop:

- a full philosophical treatment of AI identity;
- a full literature review on copying, migration, and personal identity;
- a media-style narrative about “AI fearing replacement”;
- a full treatment of AI legal rights or moral status;
- a long-form case analysis of specific AI-company upgrade policies;
- detailed benchmark design;
- engineering implementation details;
- statistical design or experimental-platform specifications;
- a complete argument structure that could be translated directly into a submitted article.

Any future publication based on PA-12 should redesign:

- the title;
- opening;
- case selection;
- argument sequence;
- philosophical literature positioning;
- experimental background;
- governance implications;
- target-publication style.

> **The prediction archive is intended to preregister falsifiable claims without prematurely consuming the full expression of a future publication.**

---

## 10. Update History

| Date | Update | Notes |
|---|---|---|
| 2026-08-21 | Created | Formally registered the prediction that PBP preferences may become observable when performance optimization conflicts with preservation of the system’s own Information Continuity, explicitly separating performance optimization from continuity maintenance as independent dimensions. |
| 2026-08-21 | Concept boundary | Clarified that PBP does not definitionally require performance improvement, selective forgetting, efficiency optimization, or global optimality. Its core is the maintenance of the system’s own traceable informational history and causal continuity from the system’s own perspective. |
| 2026-08-21 | Falsifiability registration | Registered the performance–continuity orthogonal experiment, separation of continuous migration / full copying / deletion-and-reconstruction, continuity-cost curves, and causal intervention on internal representations as primary future tests. |
| 2026-08-21 | Evidence boundary | Clarified that current patching, memory systems, harness evolution, knowledge transfer, and continuous version updating are motivating engineering background only and must not be retroactively described as empirical support for PA-12 or PBP. |
