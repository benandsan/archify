---
name: archify-review
description: 审查 Archify 的问题、PR 或代码，依据价值、成本和影响作出有证据的维护决策。适用于问题分类、变更审查和代码质量评估。
metadata:
  internal: true
---

# Archify Review

Judge whether a problem is worth addressing and an approach is worth maintaining over time.

- **Value**: Identify the real problem, who benefits, how often it occurs, its consequences, and whether it is worth addressing now.
- **Cost**: Consider implementation and verification effort, along with the future cost of understanding, changing, and maintaining the code. Prefer existing capabilities and keep the solution proportional to the problem.
- **Impact**: Identify affected behavior and modules, consequences for users and future development, and whether the change improves maintainability or adds coupling and constraints.

Consider maintainability, complexity, compatibility, performance, and other relevant concerns within these three dimensions, according to the specific problem.

Ground judgments in evidence: verify the target revision and relevant facts, distinguish direct verification from existing evidence and assumptions, and choose checks that resolve the key uncertainties.

Explain whether the work is worthwhile, the approach's cost and impact, any better alternatives, and unresolved questions that matter to the decision. Give reasons and scale the detail to the importance of each concern.

For repository-specific review and contribution requirements, consult [REVIEWING.md](../../../REVIEWING.md) and [CONTRIBUTING.md](../../../CONTRIBUTING.md) as needed.
