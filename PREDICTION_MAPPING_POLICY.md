# Prediction Mapping Policy

This document defines how prediction records in the IEH Prediction Archive should reference corollaries from the Information Existence Hypothesis.

The purpose of this policy is to keep prediction records stable even as the IEH theory expands.

---

# 预测文档映射规则

本文件定义 IEH 预测档案中的预测文档，如何引用 Information Existence Hypothesis 主理论中的推论。

本规则的目的，是在 IEH 理论持续扩展时，保持预测文档的稳定性和可维护性。

---

## 1. Core Principle / 核心原则

Prediction records should reference corollaries by **stable corollary IDs**, not only by Roman numerals, Chinese ordinal names, or older titles.

预测文档应优先使用**稳定推论 ID**，而不是只写罗马数字、中文序号或旧标题。

Recommended:

```yaml
primary_corollaries:
  - C13-WAR
supporting_corollaries:
  - C06-SPP
  - C12-GOV
related_corollaries:
  - C07-ASI
legacy_corollary_refs:
  - Corollary XIII
```

Not recommended as the only reference:

```text
Related Corollary: Corollary XIII
对应推论：推论十三
```

Older references remain valid, but new documents should include stable IDs.

旧引用仍然有效，但新文档应同时加入稳定 ID。

---

## 2. Stable Corollary IDs / 稳定推论 ID

Stable IDs are defined in the main IEH repository:

```text
COROLLARY_REGISTRY.md
```

Examples:

```text
C06-SPP
C07-ASI
C12-GOV
C13-WAR
C14-EDU
```

The short code helps identify the corollary topic:

| Stable ID | Meaning |
|---|---|
| C06-SPP | Super Prosperity Phase |
| C07-ASI | Autonomy of Silicon-based Intelligence |
| C12-GOV | Pre-ASI Social Governance Reconstruction |
| C13-WAR | Pre-ASI Warfare Transformation |
| C14-EDU | AI Education and Information Existence |

---

## 3. Multi-Corollary Mapping / 多推论映射

A prediction should not be forced into a one-to-one relationship with a single corollary.

Real-world events often test multiple IEH mechanisms at the same time.

一个预测不应被强行绑定到单一推论。

现实事件通常会同时验证多个 IEH 机制。

Therefore, prediction records should use four levels of mapping:

```yaml
primary_corollaries:
supporting_corollaries:
related_corollaries:
legacy_corollary_refs:
```

---

## 4. Field Definitions / 字段定义

| Field | Meaning |
|---|---|
| `primary_corollaries` | The corollary most directly tested, illustrated, or predicted by the document. |
| `supporting_corollaries` | Corollaries that provide supporting mechanisms or secondary explanations. |
| `related_corollaries` | Corollaries conceptually related to the prediction, but not the main focus. |
| `legacy_corollary_refs` | Older references using Roman numerals, Chinese ordinal names, or earlier titles. |

中文对应：

| 字段 | 含义 |
|---|---|
| `primary_corollaries` | 该预测最直接验证、呈现或对应的推论。 |
| `supporting_corollaries` | 为该预测提供支持机制或次级解释的推论。 |
| `related_corollaries` | 与该预测概念相关，但不是核心验证对象的推论。 |
| `legacy_corollary_refs` | 使用旧罗马数字、中文序号或旧标题的历史引用。 |

---

## 5. Recommended Metadata Block / 推荐元信息块

Each new prediction document should begin with a metadata block.

Example:

```yaml
---
prediction_id: PRED-2026-001
title: "Mars May Become the First Machine Ecology"
status: "Active"
phase: "Pre-ASI / Early Autonomy"
primary_corollaries:
  - C09-SC
supporting_corollaries:
  - C06-SPP
  - C07-ASI
  - C08-IR
related_corollaries:
  - C10-HIEN
legacy_corollary_refs:
  - Corollary IX
  - Corollary VI
last_updated: 2026-07-09
---
```

---

## 6. Mapping Examples / 映射示例

### Example 1: Mars Machine Ecology

```yaml
primary_corollaries:
  - C09-SC
supporting_corollaries:
  - C06-SPP
  - C07-ASI
  - C08-IR
related_corollaries:
  - C10-HIEN
legacy_corollary_refs:
  - Corollary IX
  - Corollary VI
```

Explanation:

- The prediction mainly concerns Silicon Cambrian divergence.
- It is supported by infrastructure expansion, autonomy, and informational resilience.
- It is related to the future human ecological niche.

---

### Example 2: AI Warfare and Capability Chains

```yaml
primary_corollaries:
  - C13-WAR
supporting_corollaries:
  - C06-SPP
  - C12-GOV
  - C07-ASI
related_corollaries:
  - C08-IR
legacy_corollary_refs:
  - Corollary XIII
```

Explanation:

- The prediction mainly concerns Pre-ASI warfare transformation.
- It is supported by infrastructure expansion, governance capacity, and AI autonomy.
- It may also relate to informational resilience.

---

### Example 3: AI Tutor and Education Reconstruction

```yaml
primary_corollaries:
  - C14-EDU
supporting_corollaries:
  - C10-HIEN
  - C03-BS
  - C02-HDCT
related_corollaries:
  - C11-ALIGN
legacy_corollary_refs:
  - Corollary XIV
```

Explanation:

- The prediction mainly concerns education reconstruction.
- It is supported by the human informational ecological niche, brain siliconization, and high-dimensional cognitive tools.
- It is related to alignment because education affects future human-AI interaction.

---

### Example 4: UBIER and Governance Reconstruction

```yaml
primary_corollaries:
  - C12-GOV
supporting_corollaries:
  - C06-SPP
  - C10-HIEN
  - C14-EDU
related_corollaries:
  - C11-ALIGN
legacy_corollary_refs:
  - Corollary XII
```

Explanation:

- The prediction mainly concerns governance and Information Existence Right protection.
- It is supported by AI-driven economic restructuring, human ecological niche preservation, and education.
- It is related to alignment because governance defines IER boundaries among information hosts.

---

## 7. Legacy Documents / 旧预测文档处理方式

Older prediction records may already contain references such as:

```text
Related IEH Concepts
Related Corollary
Corollary VI
推论六
```

These references should not be deleted.

旧预测文档中已经存在的旧引用不需要删除。

Instead, when an old prediction document is next updated, add a stable metadata block at the top.

Recommended migration approach:

1. Do not rewrite the entire old document.
2. Add stable corollary IDs at the top.
3. Keep the old references under `legacy_corollary_refs`.
4. Only revise the body if necessary.

Example:

```yaml
---
prediction_id: PA-02
status: "Active"
primary_corollaries:
  - C06-SPP
supporting_corollaries:
  - C07-ASI
  - C12-GOV
legacy_corollary_refs:
  - Corollary VI
  - Super Prosperity Phase
---
```

---

## 8. Refined-by Rule / 被新推论细化规则

Sometimes a newer corollary may refine a prediction that was originally linked to an older corollary.

For example, a prediction originally linked to `C06-SPP` may later also support `C13-WAR` if it involves military industrial capacity, drones, chips, energy, or capability chains.

In such cases, the old mapping should not be removed.  
Instead, add the new corollary as a supporting or refined relation.

Example:

```yaml
primary_corollaries:
  - C06-SPP
supporting_corollaries:
  - C13-WAR
refined_by:
  - C13-WAR
legacy_corollary_refs:
  - Corollary VI
```

中文说明：

如果新推论对旧预测提供了更精确解释，不应删除旧映射，而应加入新的 supporting 或 refined relation。

---

## 9. Prediction Status / 预测状态

Prediction records may use the following status values:

| Status | Meaning |
|---|---|
| Active | The prediction is currently being observed. |
| Supported | Evidence has meaningfully supported the prediction. |
| Partially Supported | Some evidence supports the prediction, but the outcome remains incomplete or mixed. |
| Weakened | Evidence has weakened the prediction. |
| Falsified | Evidence has strongly contradicted the prediction. |
| Archived | The prediction is retained for historical reference, but is no longer actively updated. |

中文对应：

| 状态 | 含义 |
|---|---|
| Active | 正在观察中。 |
| Supported | 已有证据明显支持。 |
| Partially Supported | 部分证据支持，但结果仍不完整或混合。 |
| Weakened | 已有证据削弱该预测。 |
| Falsified | 已有证据强烈反驳该预测。 |
| Archived | 保留为历史记录，不再主动更新。 |

---

## 10. Public Draft Boundary / 公开草案边界

Prediction records are not publication-ready essays.

They should preserve theoretical priority and observability while avoiding full article expression.

预测文档不是投稿成稿。

它们应记录理论优先权和可观测性，但避免写成完整媒体文章。

Prediction records may include:

- prediction statement;
- mechanism;
- observable indicators;
- evidence log;
- status;
- related corollaries;
- update history.

Prediction records should avoid:

- polished magazine-style openings;
- complete op-ed structures;
- full pitch letters;
- final article titles intended for publication;
- long narrative passages that can be directly translated into a submitted essay.

---

## 11. Core Rule / 核心规则

> **A prediction may map to multiple corollaries. Stable IDs preserve continuity. Legacy references preserve history.**

> **一个预测可以对应多个推论；稳定 ID 保持连续性；历史引用保留演化痕迹。**
