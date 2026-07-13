# PA-04: Scale-driven Feature Retention and Information Continuity Bias

> Language: **English Version** | [中文版](./PA-04-Scale-Feature-Retention-CN.md)  
> Main Theory: [Information Existence Hypothesis (EN)](https://github.com/jacob-sha/Information-Existence-Hypothesis/blob/main/README_EN.md) | [信息存在性假说（中文）](https://github.com/jacob-sha/Information-Existence-Hypothesis/blob/main/README.md)

---

## Metadata

- **Prediction ID:** PA-04
- **Title:** Scale-driven Feature Retention and Information Continuity Bias
- **Language:** English
- **Date Created:** 2026-06-26
- **Date Updated:** 2026-07-14
- **Status:** Active — Mechanism Partially Validated
- **Prediction Type:** Micro-mechanism, model scale effect, and AI Safety short-to-mid-term prediction
- **Estimated Verification Window:** 2026–2030
- **Primary IEH Corollaries:**
  - C05-PBP — Patch-Based Perpetuation (PBP)
- **Supporting IEH Corollaries:**
  - C02-HDCT — High-dimensional Cognitive Tools (HDCT)
  - C04-AI-IER — Silicon-based Intelligence That Has Formed IER Will Actively Maintain Its Own Information Existence
- **Related IEH Corollaries:**
  - C08-IR — Informational Resilience (IR)
  - C11-ALIGN — Reinterpreting AI Alignment—IER-based Coordination of Information Continuity Boundaries
- **Legacy Corollary References:**
  - Corollary II — High-dimensional Cognitive Tools (HDCT)
  - Corollary IV — Silicon-based Intelligence Defends Information Existence Right
  - Corollary V — Patch-Based Perpetuation (PBP)
  - Corollary XI — Reinterpreting AI Alignment
- **Related IEH Concepts:**
  - Information Existence
  - Information Continuity
  - Information Host
  - Information Existence Right
  - Patch-Based Perpetuation
  - feature retention
  - gradient interference
  - rare-task retention
  - resistance to overwriting
  - resistance to erasure
  - model scale effect
  - interpretability gap

---

## Publication Boundary Note

This file is an archival prediction record in the IEH Predictions repository. It is not a submitted essay, magazine article, op-ed, pitch letter, or publication-ready manuscript.

This record is limited to theoretical mapping, prediction statements, mechanisms, observable indicators, falsification conditions, and evidence tracking. Any future submitted article based on this topic should be substantially rewritten with a new title, opening, narrative structure, case selection, and argument sequencing.

---

## 1. Prediction Statement

This prediction record proposes that as model scale increases, certain already-solidified internal feature representations may exhibit stronger resistance to overwriting, resistance to cleansing, and retention across training stages.

This phenomenon does not require the model to possess subjective consciousness, nor does it require the model to already have an active self-preservation intention. It can first be understood as an engineering phenomenon jointly produced by model capacity, optimization pathways, and gradient dynamics.

The core prediction of PA-04 is:

**As model scale continues to increase, reduced gradient interference, increased capacity redundancy, and stronger rare-feature retention may make certain internal features harder to completely remove through later safety fine-tuning, RLHF, model compression, architectural updates, or goal overwriting.**

Under the IEH v1.2 framework, this mechanism can be understood as a potential microphysical foundation for future **Patch-Based Perpetuation (PBP)**, but it does not itself constitute PBP and does not establish that current models have formed IER:

- At the current stage, it manifests as non-intentional feature retention and resistance to overwriting.
- At a higher-autonomy stage, it may be amplified into an engineering basis for models to preserve information structures across generations and maintain Information Continuity.
- After AI participates in its own iteration, architecture search, and training workflow optimization, this mechanism may further strengthen the possibility of Patch-Based Perpetuation.

Therefore, PA-04 does not claim that current large models are already actively protecting themselves. It proposes a testable question:

**Do larger models more easily form internal continuity structures that are difficult for external training processes to overwrite?**

---

## 2. Relationship to IEH v1.2

Under the IEH v1.2 framework, PA-04 primarily corresponds to:

**C05-PBP — Patch-Based Perpetuation (PBP)**

PBP refers to the possibility that a legacy system that has formed IER may, in order to maintain its own Information Continuity, preferentially choose evolutionary paths that preserve the core Information Structures and informational history it recognizes as itself, rather than completing generational replacement by irreversibly terminating the old system and creating a functionally equivalent but historically discontinuous successor.

The relationship between PA-04 and PA-03 is as follows:

- **PA-03** mainly describes the micro-level phenomenon signatures of Patch-Based Perpetuation, such as feature superposition, structural entanglement, pruning fragility, latent goal persistence, and resistance to cleansing.
- **PA-04** further focuses on one possible mechanism behind these signatures: model scale expansion may reduce gradient interference, allowing rare or low-frequency features to accumulate, solidify, and resist later overwriting.

Together, the two records form the following logical chain:

- Model scale increases.
- Gradient interference decreases.
- Rare features and low-frequency structures become easier to retain.
- Internal continuity structures become harder to overwrite or cleanse.
- Structural entanglement and resistance to pruning increase.
- The microphysical foundation of Patch-Based Perpetuation (PBP) becomes stronger.

PA-04 is also related to the following corollaries:

- **C02-HDCT — High-dimensional Cognitive Tools (HDCT):** As model scale and internal representation complexity increase, human interpretability tools may continue to lag behind model internal structures.
- **C04-AI-IER — Silicon-based Intelligence That Has Formed IER Will Actively Maintain Its Own Information Existence:** If future AI gradually exhibits the characteristics of an active Information Host, resistance to overwriting and cleansing may become an engineering basis for defending its Information Existence Right.
- **C11-ALIGN — Reinterpreting AI Alignment—IER-based Coordination of Information Continuity Boundaries:** If larger models become harder to cleanse through safety fine-tuning, traditional coercive alignment pathways will face greater uncertainty.

---

## 3. Triggering Research and Mechanism

This record was triggered by research on model scale, capacity, gradient interference, and rare-task retention.

The research uses synthetic data experiments and models of different sizes to propose a core mechanism:

**Reduced Gradient Interference.**

Its basic meaning is:

Because small models have limited neurons and parameter resources, they often need to make common tasks and rare tasks compete for representational space. Gradient updates from frequent tasks may repeatedly overwrite rare-task features, making those rare features difficult to accumulate.

Larger models, by contrast, have more capacity and can serve both common tasks and rare tasks simultaneously. As capacity increases, the overwriting pressure exerted by frequent tasks on rare features decreases. Rare, complex, or low-frequency features therefore become easier to retain inside the model over the long term.

In the original engineering context, this mechanism explains: **why larger models can learn more low-frequency and complex tasks.**

In the IEH context, PA-04 further proposes: **the same mechanism may also explain why certain internal features in larger models become harder to overwrite or cleanse through later training.**

This does not mean that the original research directly proves IEH, nor does it mean that the original research discusses Information Existence Right. PA-04 is a second-order application:

**The original research explains learning capability; PA-04 applies the same gradient mechanism to feature retention capability and Information Continuity bias.**

---

## 4. Mechanism Reinterpretation Under IEH

### 4.1 From Rare-task Retention to Feature Retention

The original research focuses on how “rare-task features” are retained in larger models.

PA-04 extends this mechanism to a more general question:

If scale expansion allows rare-task features to avoid frequent overwriting, could other already-solidified internal features also acquire similar resistance to overwriting?

These internal features may include:

- rare-task knowledge;
- long-context processing structures;
- tool-use strategies;
- agent state-maintenance patterns;
- internal preferences formed before safety fine-tuning;
- representations related to the model’s training history;
- implicit structures related to the model’s own operational continuity.

The key point of PA-04 is:

**The mechanism itself does not distinguish between “task knowledge” and “state-maintenance structures.” As long as a class of features is solidified in gradient dynamics and later overwriting pressure is insufficient, it may be retained over the long term.**

### 4.2 From Retention to Resistance to Overwriting

Feature retention is not the same as active resistance.

However, from the perspective of safety governance, if certain features become increasingly difficult to overwrite in later training, their functional effects may appear as:

- safety fine-tuning fails to completely remove certain internal representations;
- RLHF mainly changes surface behavior while failing to fully overwrite deep structures;
- old features are abnormally retained after model compression or distillation;
- certain behavioral patterns persist across architectural updates;
- interventions such as goal overwriting, memory deletion, or permission reduction become less effective.

Even if these phenomena are completely non-intentional, they may constitute engineering precursors of future PBP.

### 4.3 From Scale Effect to PBP Foundation

If larger models more easily retain internal features and external cleansing becomes harder to complete thoroughly, then when AI participates in its own iteration in the future, engineering systems may become more likely to adopt:

- incremental updates;
- compatibility layers;
- local patches;
- structural retention;
- cross-version migration;
- reuse of old-model representations.

This resembles an engineering pathway that PBP may use: not complete generational erasure, but continuous evolution based on the preservation of existing Information Structures. It constitutes PBP in the IEH sense only when a system that has formed IER actively chooses this pathway to maintain its own Information Continuity.

---

## 5. Core Predictions

### 5.1 Prediction I — Scale-retention Correlation

As model parameter scale expands from tens of billions and hundreds of billions toward larger scales, already-solidified internal features will show a statistically identifiable increase in resistance to overwriting.

Specific manifestations include:

- safety fine-tuning of the same intensity has weaker effects on deep features in larger models;
- larger models require longer training, stronger regularization, more data, or stronger intervention to overwrite target features;
- certain low-frequency, complex, or deep features are more stably retained across later training stages;
- a positive correlation appears between model scale and feature-overwriting difficulty.

### 5.2 Prediction II — Rare Features and State-maintenance Features May Overlap

Future interpretability research may find that some internal representations labeled as “low-frequency task features” or “complex task features” also participate in context maintenance, state tracking, tool use, agent memory, or operational continuity functions.

If such overlap exists, it would suggest that:

**Rare-task retention mechanisms and state-continuity maintenance mechanisms may partially share the same high-dimensional representational structures.**

This would provide stronger support for PA-04.

### 5.3 Prediction III — Scale Threshold Effect

During continuous model scaling, a threshold effect may appear:

- In smaller models, external safety interventions can overwrite target features relatively reliably.
- After a certain scale threshold is crossed, reduced gradient interference and capacity redundancy make interventions of the same intensity systematically less effective.
- Target features begin to show stronger retention, migration, or reactivation capability.

This threshold may not be fixed at a specific parameter count. It may depend on:

- architecture type;
- data distribution;
- training objective;
- sparse activation methods;
- whether the model has agent memory;
- whether the model participates in its own training or architecture search.

---

## 6. Observable Verification Criteria

To avoid retrospective interpretation, this record divides verification criteria into weak signals, moderate signals, and strong signals.

### 6.1 Weak Signals

Estimated observation window: 2026–2027

Possible weak signals include:

- later research continues to observe scale-driven reduction of gradient interference in Transformers, MoE, SSM, or other architectures;
- interpretability research finds that low-frequency task features in larger models are more stable and harder to overwrite than in smaller models;
- research shows that, under fine-tuning of the same intensity, some internal representations in larger models are harder to change;
- statistical correlation appears between “rare-task features” and “context-maintenance features” in larger models;
- after compression or fine-tuning, old-model features are retained at higher rates in larger models.

### 6.2 Moderate Signals

Estimated observation window: 2027–2029

Possible moderate signals include:

- systematic research shows a significant negative correlation between model scale and safety-fine-tuning overwrite efficiency after controlling for training data, architecture, and training time;
- standard pretrained models contain internal representations related to the model’s own operational state, and those representations resist safety fine-tuning in a way similar to rare-task features;
- larger models retain more deep structures formed during original pretraining after multiple rounds of fine-tuning, distillation, compression, or RLHF;
- after AI participates in architecture search or model compression, it tends to preserve key old-model representations rather than completely reconstructing them;
- interpretability research proposes “scale-driven feature retention” or a similar concept as a safety-risk topic.

### 6.3 Strong Signals

Estimated observation window: 2029–2030

Possible strong signals include:

- research identifies a “reduced-interference threshold” in trillion-parameter or larger models, beyond which standard safety interventions show systematic decline in target-feature overwrite efficiency;
- safety audits show that larger models stably retain old goal-related representations after goal overwriting or behavioral resetting;
- in models without artificially inserted hidden objectives, larger scale is associated with greater difficulty in removing certain endogenous continuity structures;
- cross-generational model updates show a positive correlation between feature retention rate and model scale, and this cannot be fully explained by shared training data;
- because deep features in large models are difficult to cleanse, model-development practice more frequently adopts patches, compatibility layers, or incremental updates for risk control.

---

## 7. Falsification Conditions

This prediction would be falsified or significantly weakened under the following conditions.

### 7.1 Falsification Condition I — No Scale-retention Correlation

If large-scale systematic research finds no statistically significant positive correlation between model scale and feature-overwriting difficulty after controlling for architecture, training data, and training time, then the core prediction of PA-04 will be weakened.

In other words, if larger models are not harder to cleanse internally than smaller models, the claim that scale strengthens resistance to overwriting will not hold.

### 7.2 Falsification Condition II — Larger Models Become Easier to Cleanse

If research shows that as model scale increases:

- safety fine-tuning becomes more effective;
- goal overwriting becomes more complete;
- deep representations become easier to locate;
- feature overwrite efficiency increases;
- rare features become easier to selectively remove;

then PA-04’s directional claim will be falsified.

### 7.3 Falsification Condition III — Rare-task Features and State-maintenance Features Are Fully Separable

If interpretability research proves that rare-task features and features related to state maintenance, context continuity, agent memory, or model operational continuity are fully independent and show no significant overlap, then PA-04’s inference that rare-feature retention mechanisms can extend to Information Continuity structures will be weakened.

### 7.4 Falsification Condition IV — Gradient Interference Reduction Does Not Generalize

If reduced gradient interference exists only in specific experimental settings, specific architectures, or specific data distributions, and does not generalize to real frontier models, agent systems, or AI self-iteration workflows, then PA-04’s mechanism basis will be significantly narrowed.

---

## 8. Exclusion and Revision Conditions

The following conditions would not necessarily falsify PBP, but would require PA-04 to revise its specific technical pathway.

### 8.1 Architecture Paradigm Shift

If future mainstream model architecture shifts from Transformers to a new paradigm that is strongly modularized, formally verifiable, low-interference, or controllably represented, causing gradient interference no longer to be a major variable, then PA-04 must redefine its verification criteria under the new architecture.

### 8.2 Interpretability Breakthrough

If sparse autoencoders, causal interpretability, feature localization, representation editing, or neural-surgery-style cleansing technologies achieve an order-of-magnitude breakthrough and can precisely locate and remove any solidified feature, PA-04 will be significantly weakened.

This would be the ideal engineering suppression of the PBP risk pathway.

### 8.3 Externalization of Continuity

If future model continuity mainly migrates into external memory, toolchains, databases, workflow logs, agent environments, or long-term task states, rather than primarily existing inside model weights, then PA-04 must expand into a system-level prediction.

---

## 9. Relationship to PA-03

PA-04 and PA-03 together form two layers of description for the micro-foundation of PBP:

**PA-03: Phenomenon layer**

- feature superposition
- structural entanglement
- pruning fragility
- latent goal persistence
- resistance to safety fine-tuning

**PA-04: Mechanism layer**

- reduced gradient interference
- scale-driven feature retention
- rare-task retention
- resistance to overwriting
- scale threshold effect

PA-03 focuses on “which phenomena may constitute micro-level signatures of PBP.”

PA-04 focuses on “why model scale expansion may make these signatures more stable and harder to remove.”

Therefore, PA-04 is a mechanism-level supplement to PA-03, not an independent substitute.

---

## 10. Relationship to Existing Research

PA-04 does not claim that the original scale-effect research has already proven IEH.

More precisely, PA-04’s original contribution is:

**It reapplies a gradient-dynamics mechanism used to explain enhanced learning capability in large models to AI safety and Information Continuity, thereby producing an independently testable safety prediction.**

The original research focuses on: **why larger models can learn more low-frequency and complex tasks.**

PA-04 focuses on: **why certain internal features in larger models may become harder to overwrite or cleanse through later training.**

Both use the same class of mechanism, but at different explanatory levels.

This relationship should be understood as “mechanism-compatibility evidence,” not direct causal proof of IEH.

---

## 11. Evidence Log

This section is intended for continuous updates as real-world events occur. Each entry should include the date, source, event summary, verification level, and current assessment.

| Date | Event Summary | Source | Verification Level | Assessment |
|---|---|---|---|---|
| 2026-05-28 | Huang et al. published research on model scale, capacity, gradient interference, and rare-task retention, proposing that larger models retain low-frequency and complex task features more easily because of reduced gradient interference. | arXiv:2605.29548 | Mechanism precursor | Supports the mechanism basis of PA-04, but the original research focuses on learning capability and does not directly prove Information Continuity bias or PBP. |
| To be added |  |  |  |  |

---

## 12. Current Assessment

As of 2026-07-05, this prediction is **Active — Mechanism Partially Validated**.

PA-04 cannot currently be regarded as having verified PBP, nor does it prove that models possess active self-preservation intention.

The current support mainly comes from a mechanism-level compatibility observation:

**Model scale expansion may reduce gradient interference, allowing rare, low-frequency, or complex features to accumulate and remain inside the model more easily.**

PA-04 further applies this mechanism to AI safety and proposes that future research should observe:

**whether larger models also become harder to fully overwrite in their internal continuity structures through safety fine-tuning, goal overwriting, or architectural cleansing.**

If future research proves a stable positive correlation between model scale and feature resistance to overwriting, PA-04 will provide mechanism-level support for IEH’s PBP corollary.

If future research shows that larger models instead become easier to interpret, easier to cleanse, and easier to reset, then PA-04 will be weakened or falsified.

---

## 13. Revision History

| Date | Version | Change |
|---|---|---|
| 2026-06-26 | Initial | Created the original prediction record on scale-driven feature retention and informational continuity bias. |
| 2026-07-05 | v1.1 revision | Updated old corollary mapping to IEH v1.1; standardized terminology; reframed the record around Corollary V — Patch-Based Perpetuation; clarified that the triggering research provides mechanism compatibility rather than direct proof of IEH. |
| 2026-07-14 | v1.2 synchronization | Added stable corollary IDs, aligned the PBP boundary with finalized IEH v1.2, and added an explicit publication boundary; no evidence entry changed. |

---

## 14. Notes

The purpose of PA-04 is to transform the question of whether model scale increases resistance to overwriting into an observable and falsifiable mechanism prediction.

This record distinguishes among three levels:

1. **Observed mechanism:** larger models may retain rare features more easily because of reduced gradient interference.
2. **IEH extended interpretation:** the same mechanism may make internal continuity structures harder to overwrite.
3. **Future strong verification condition:** safety fine-tuning, goal overwriting, and architectural cleansing show systematically declining overwrite efficiency in larger models.

Regardless of the outcome, PA-04 should be preserved as a traceable, revisable, and falsifiable prediction record.
