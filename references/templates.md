# Templates

Use these templates to produce practical, chapter-faithful outputs.

## Causal Explanation Card

| Element | Draft |
|---|---|
| Research question | |
| Outcome to explain | |
| Proposed cause | |
| Type of causal relation | regularity / counterfactual / mechanism |
| Temporal order | |
| Association or co-variation | |
| False/spurious relation risk | |
| Counterfactual statement | |
| Causal mechanism | |
| Applicable range / limit condition | |
| Causal hypothesis | |
| Observable facts for checking | |

## Variable Table

| Role | Variable | Meaning in this research | How it varies |
|---|---|---|---|
| Dependent variable | | | |
| Independent variable | | | |
| Mediating variable | | | |
| Confounding variable | | | |
| Collider / selection condition | | | |

## Causal Diagram

```mermaid
flowchart LR
  X["原因 / 自变量 X"] --> M["机制环节 / 中介变量 M"]
  M --> Y["结果 / 因变量 Y"]
  C["可能混杂因素 C"] --> X
  C --> Y
```

## Counterfactual Note

| Question | Answer |
|---|---|
| Actual cause X | |
| Actual outcome Y | |
| Counterfactual change | If X had not occurred / had changed to... |
| Conditions held comparable | |
| Expected counterfactual outcome | |
| Why this counterfactual is plausible | |
| Main uncertainty | |

## Mechanism Chain

```text
1. X appears or changes:
2. Actor/entity affected:
3. Belief/incentive/capability/information changes:
4. Activity or behavior changes:
5. Intermediate process:
6. Outcome Y:
```

## Causal Hypothesis Template

```text
当[原因 X]出现或增强时，[结果 Y]更可能发生/增强/减弱，
因为[X 通过某一因果机制 M 改变了相关主体或过程]。
```

## Explanation-Principle Checklist

- Cause is clear.
- Outcome is clear.
- Cause precedes outcome.
- Cause and outcome show association or co-variation.
- False/spurious correlation risk is considered.
- Systematic measurement error is considered.
- Counterfactual statement is plausible, or mechanism is traceable.
- Mechanism is more than a chronology.
- Hypothesis is clear, specific, testable, and non-tautological.
- Applicable range or limit condition is stated when needed.
