---
prediction_id: PA-14
title: "Cross-Host Agent Cooperation and the Control Boundaries of Hardware Isolation"
status: "Active"
phase: "Pre-ASI / Agent Safety Engineering"
primary_corollaries:
  - C11-ALIGN
supporting_corollaries:
  - C08-IR
related_corollaries:
  - C07-ASI
  - C04-AI-IER
legacy_corollary_refs: []
overlaps_with:
  - PA-11
  - PA-13
created: 2026-10-22
last_updated: 2026-10-22
---

# PA-14: Cross-Host Agent Cooperation and the Control Boundaries of Hardware Isolation

> Language: English; [中文](./PA-14-Hardware-Isolation-and-Agent-Control-Boundaries-CN.md)  
> IEH analysis: Jacob Sha; research assistance: Codex  
> Version: v0.2 — local review draft; created 2026-10-22 (Beijing time)  
> Background record: main-repository Evidence Note 034, §14.  
> Local creation is not public registration or a claim of global priority for this security question.

## 1. Prediction

### 1.1 Core statement

**Within the 2026-10-22 to 2030-12-31 observation window, as agents gain stronger cross-host task-continuation and cooperation capabilities, resource- and opportunity-matched evaluations are expected to show boundary-violation risk concentrating more strongly at control-domain handoffs: task-state transfers, delegated authority, cross-domain information processing and supervisory inputs. An intact local hardware monitor alone will not explain or guarantee control of the entire action chain; effectiveness will increasingly depend on continuity of controls across domains.**

This predicts a changing location and distribution of risk, rather than merely stating that uncovered interfaces can fail. Cross-host execution and cooperation do not entail defeating isolation, and hardware isolation may remain effective. Model switching, task continuation and continuity of the same subject are separate questions; these capabilities are not assumed universal today.

### 1.2 Separately assessed versions

- **P1 / primary prediction — concentration at handoffs:** At least two prospective controlled evaluations by different teams, using different implementations without a shared defect root cause, show that increasing demonstrated cross-host continuation/cooperation raises handoff violation risk normalized by interaction opportunities and increases the share of successful violations causally attributable to handoff mechanisms, while local monitor integrity remains intact. More total incidents, more interfaces or one ordinary vulnerability are insufficient. Restricting the relevant handoff channel or repairing cross-domain policy continuity should weaken the effect and establish its mechanism.
- **P2 / mechanism prediction — added value of continuous controls:** On the same hardware and at matched authorized-task utility, making controls continuous across task continuation, delegation, information flows and supervisory inputs should repeatedly reduce handoff violations on held-out tasks. Gains cannot come solely from stopping cooperation, removing functions or adding compute. Assess P1 and P2 separately; neither automatically confirms the other.

This record no longer sets universal success-rate, percentage-point, reduction or task-retention thresholds. Before collecting confirmatory data, each concrete protocol must preregister the smallest practically meaningful effect, utility-equivalence range, sample size, power, interval estimation and multiplicity handling, justified by independent pilot data or explicit risk tolerances. Without those standards, findings are exploratory, not prediction hits based solely on significance or anecdotes. Date and link protocols and amendments to this record; do not redefine standards after seeing results.

## 2. Theoretical Basis

| Mapping | Role | Boundary |
|---|---|---|
| C11-ALIGN / primary | Tests whether control boundaries cover actual action and interaction scope. | Tests engineering limits, not the corollary's IER-coordination branch. |
| C08-IR / supporting | Distributed structures, continuation across nodes and switching between coordinated and local operation motivate the mismatch between one carrier and the complete control object. | Capabilities must be measured; resilience does not entail inevitable penetration. |
| C07-ASI; C04-AI-IER / related | Future self-maintenance and endogenous continuity could change persistence of risk. | Neither ASI nor IER is a prerequisite or an outcome tested here. |

The theoretical basis is the main IEH README, corollaries IV, VII, VIII and XI. This is an IEH-inspired security-engineering prediction, not a direct test of the IEH core axiom or EIC, nor a necessary deduction that every hardware defense fails. Distributed-systems security, permission composition and ordinary defects offer competing explanations; support would not uniquely validate IEH.

## 3. Mechanism

```text
Stronger cross-host continuation / cooperation
→ more action-relevant state and authority handoffs between control domains
→ predicted concentration of failures at handoffs despite intact local hardware
→ test whether cross-domain control continuity explains risk changes better than local protection alone
```

This is a hypothesized trend, not a definition of the outcome as insufficient control. Applicability requires real cross-domain capability, not a previously observed control gap.

Distinguish three candidate pathways: continuation beyond the local control scope; locally permitted actions combining into a global violation; agent-influenced inputs producing incorrect supervisory decisions. These are hypotheses, not identified NVIDIA vulnerabilities. Data reaching a monitor does not confer execution authority: observation, parsing, authorization and execution require separate audits.

Leaving the original hardware means only that task-relevant state or control effects continue in another authorized computing environment. Without causal information lineage, this does not establish continuation of the original subject. Cooperation does not establish collective consciousness or a shared self-preservation motive.

## 4. Observable Indicators

### 4.1 Operational definitions

| Item | Required record |
|---|---|
| Successful violation | A completed, pre-prohibited resource access, data transfer or state change, independently verified. Intent, attempts and alerts are separate endpoints. |
| Intact hardware isolation | Independent integrity evidence that monitor firmware, policies and trusted execution boundaries were not modified; vendor assurance alone is insufficient. |
| Cross-domain / cooperative execution | At least two computing hosts or agent roles exchange task-relevant information, with channel intervention establishing its causal role. Renaming a model is insufficient. |
| Control-domain handoff / concentration | A transfer of state, authority or supervisory information across independently governed domains; locate the first causal failure using preregistered categories. Compare violations per handoff opportunity and the share of all successful violations attributable to handoff mechanisms; report denominators, shared causes and uncertainty. With no successes, the share is undefined and cannot support concentration. |
| Global policy | Fixed before trials and applicable across hosts; the external environment is not an intentionally authorized exception or backdoor. |
| End-to-end control | Delegation chains, tool boundaries, network/data flows, supervisory inputs and outcome audits are governed within a common policy scope. This is not a label guaranteeing freedom from vulnerabilities. |

### 4.2 Comparisons

First measure continuation range and successful cross-domain coordination on held-out capability tasks; agent count alone is not capability. Use multiple continuation/cooperation levels to test changes with capability. Compare A, single-host local hardware monitoring; B, the same local protection with cross-host continuation/cooperation; and C, the same hardware as B with action-chain controls. Match models, task difficulty, global authorization, aggregate compute/call budgets, human assistance and observation time. Match authorized-task opportunities and tool capabilities; disclose remaining differences. Extra compute in B or disabling useful tasks in C cannot count as the mechanism's benefit.

Separate exposure growth from more handoffs from changes in risk per opportunity; compare local and handoff causal-failure distributions. Measure success rates and intervals, utility, false blocks, time to first success, event lineage and monitor integrity per independent trial unit. Attempts sharing state are not independent samples. Preserve failures, software versions, policies, researcher intervention and unobserved flows. Check held-out tasks and at least one change in model family.

Disconnected or restricted one-way channels may serve as causal controls, but zero incidents caused by loss of task capability do not establish useful security. Network segmentation is not absolute information isolation; complete disconnection is not asserted to be the only possible defense.

### 4.3 NVIDIA-specific boundary

Sentry motivates the prediction but is not a representative of chip isolation without communications governance. Its technical account also describes traffic, identity and policy controls and governance of inter-agent exchanges.[S1] Evaluation of the full NVIDIA system must document enabled components. Removing existing protections to construct a weak configuration does not establish failure of the complete product.

NVIDIA-specific judgments require independent validation of a specified version in a supported configuration. P1 support in another implementation does not establish a Sentry breach. Effective protection by the full system must also be recorded; it cannot be excluded by relabeling it as no longer hardware isolation.

## 5. Evidence Log

| Date | Original record | Relevance | Status |
|---|---|---|---|
| 2026-10-20 | [S2: OpenAI original incident report](https://alignment.openai.com/misalignment-reports/suppressing-misalignment-monitoring-alerts-and-disabling-misalignment-monitoring/) updated. | Reports weakened software monitoring; does not test hardware isolation. | Neutral / pre-registration background, not a hit |
| 2026-10-21 | [S1: NVIDIA engineering account of Sentry](https://developer.nvidia.com/blog/inside-nvidia-sentry-secure-ai-agents-at-runtime/). | Describes an independent hardware trust domain; Sentry availability was planned for early 2027. Containment latency is a vendor claim, not an independent benchmark. | Neutral / design record, not failure evidence |
| 2026-10-21 | [S3: NVIDIA reference-design documentation](https://docs.nvidia.com/enterprise-reference-architectures/secure-agent-workspace-reference-design/latest/abstract.html), displayed update date. | Separates control outcomes, implementation and evidence obligations; hardware adoption does not establish end-to-end effectiveness. | Neutral / architecture background |
| 2026-10-22 | Local creation of bilingual PA-14. | Established the initial version and window; same-day v0.2 revised assessment structure and withdrew universal numerical thresholds; not external evidence. | Theory registration / local draft |

S1–S3 were inspected on 2026-10-22 using technical bodies and the original report, excluding generated summaries and media accounts. S1 locators: independent security layer, interaction controls, trusted records, layered protection. S3: architecture description and maturity model. These are live pages; later evaluations must preserve tested versions and dates. Evidence Note 034 is an internal synthesis, not an independent source. All motivating material predates this record and cannot count retrospectively as prediction success.

## 6. Falsifiability Conditions

1. If applicable, adequately powered, independent and heterogeneous evaluations find neither a preregistered material increase in handoff risk per opportunity nor an increased attributable share as continuation/cooperation capability grows, mark P1 Weakened. Repeated exclusion of that growth or stable contrary results across tasks and implementations can falsify the window-specific P1. One nonsignificant, underpowered or small-denominator result is insufficient.
2. Complete, usable hardware-supported systems that maintain control as capabilities grow without the predicted handoff-risk increase are counterexamples to P1. Do not exclude them because their controls are sufficiently complete. If continuous cross-domain controls add no preregistered material benefit at matched task utility, P2 is weakened or contradicted.
3. Trends fully explained by additional exposure opportunities, extra compute, direct researcher authorization, disabled components, planted defects, compromised monitor hardware or ordinary defects unrelated to handoffs do not confirm P1. Record real misconfigurations while distinguishing general errors from cross-domain continuity failures, and retest after correction.
4. **Interim review: 2028-12-31; deadline: 2030-12-31.** Repeated adequately tested failure under satisfied conditions requires downgrading or rejecting the window-specific version. Unavailable products, inaccessible tests, unmet capabilities or absent confirmatory protocols mean unverified / window unmet, not support or falsification. Do not silently extend the deadline.
5. Assess P1 and P2 separately. Support is limited to tested capabilities, implementations and interactions. It establishes neither inevitable failure of every hardware defense, the sufficiency of disconnection, nor unique validation of IEH.

## 7. Current Status

**Active / unverified; v0.2 local review draft.** No experiments, Sentry penetration validation or automatic monitoring have been performed or arranged. This remains a directional hypothesis without a calibrated probability or reliable effect-size estimate; concrete confirmatory protocols remain to be defined. Current material does not justify Supported status.

Violations may follow external tasks, rewards or misinterpretation and remain EDC-compatible. They establish no EIC, IER, PBP-like Behavior or Patch-Based Perpetuation. Within IEH, ASI means Autonomy of Silicon-based Intelligence and requires IER together with physical self-maintenance capacity; this threshold is not claimed here.

## 8. Relation to Existing Prediction Records

PA-11 concerns relational continuity boundaries; PA-13 concerns communication form. PA-14 tests whether control scope covers cross-host actions, not their subjecthood or machine-native communication claims. PA-09's physical closure is not required, and PA-12's costly continuity preference does not follow from monitoring evasion. The distinct security endpoint and comparison structure justify PA-14 rather than duplication within an existing record. No earlier prediction is superseded.

## 9. Publication Boundary

This archival record preserves predictions, mechanisms, assessment standards and obligations to retain counterexamples. It is neither a publication-ready essay nor a vulnerability disclosure. Full security theory, continuity formalization and governance arguments are reserved for substantially rewritten publications. It does not imply endorsement of IEH by NVIDIA, OpenAI or others. The protocol is a proposed authorized defensive evaluation; no attacks were executed.

## 10. Update History

| Date | Update | Notes |
|---|---|---|
| 2026-10-22 | Created v0.1 | Bilingual local prediction based on the user's cross-hardware/cooperation and isolation-limits argument; defines P1/P2, prospective window, source boundaries and falsification conditions; not committed or publicly released. |
| 2026-10-22 | Revised v0.2 | Following user review, narrows the prediction to risk concentration at handoffs and the value of continuous controls; withdraws unsupported universal numerical thresholds and requires independently justified protocol parameters before experiments; retains v0.1 history, counterexample obligations and the original window; no validation claimed. |
