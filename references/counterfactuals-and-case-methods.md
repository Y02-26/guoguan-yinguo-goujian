# Counterfactuals And Case Methods

Use this reference for qualitative causal inference, especially case studies and small-N comparative research.

## The Fundamental Problem

For a single unit, we cannot observe both:

- What happened when X occurred.
- What would have happened to the same unit at the same time if X had not occurred.

The missing counterfactual outcome is the core difficulty of causal inference.

## Approximating Counterfactuals

Use one or more strategies:

- Compare similar cases where X differs.
- Compare the same case before and after X changes.
- Use within-case process evidence to show X triggered M.
- Use theory to specify a plausible alternative.
- Use historical near-misses or unrealized alternatives.
- Use statistical matching or controls when data allow.

## Good Counterfactual Criteria

A useful counterfactual is:

- Minimal: change only X or the smallest necessary set of conditions.
- Plausible: historically and theoretically possible.
- Relevant: changes the outcome through the proposed mechanism.
- Comparable: background conditions remain sufficiently similar.
- Evidenced: supported by traces, comparable cases, or actor expectations.
- Bounded: not stretched into a completely different world.

## Case-Study Causal Methods

### Congruence Analysis

Compare the pattern predicted by a theory with the observed case pattern.

Use when:

- The theory predicts a broad relationship.
- Evidence is available on whether case facts match expectations.

Risk: congruence alone may not identify the mechanism or rule out rivals.

### Process Tracing

Trace whether the expected causal mechanism operated within the case.

Use when:

- The user needs to show how X produced Y.
- There are documents, sequence data, interviews, speeches, or decision records.

Process-tracing table:

| Mechanism step | Expected evidence | Found evidence | Alternative explanation |
|---|---|---|---|
| X appears | | | |
| Actor perception/incentive changes | | | |
| Behavior changes | | | |
| Intermediate condition changes | | | |
| Y occurs | | | |

### Case Comparison

Compare cases to approximate counterfactuals and evaluate rival explanations.

Common designs:

- Most-similar systems: cases are similar on many background factors but differ on X and Y.
- Most-different systems: cases are different on many factors but share X and Y.
- Paired comparison: one positive case and one negative or deviant case.
- Within-case comparison: same unit across periods or episodes.

### Comparative Process Tracing

Combine comparison with mechanism tracing. This is especially useful in IR because cases often differ on many variables, while process evidence helps show whether the same mechanism actually operated.

## Case Selection

Select cases based on the research purpose:

- Typical case: illustrates a well-specified theory.
- Deviant case: exposes what existing explanations miss.
- Crucial case: has high inferential leverage for or against a theory.
- Most-likely case: if theory fails here, it is weakened.
- Least-likely case: if theory succeeds here, it is strengthened.
- Positive-negative pair: compare occurrence and non-occurrence of Y.

Warning: selecting only cases where Y occurred makes it hard to know whether X matters. Add negative cases or counterfactual logic when possible.

## Causal Inference By Method Type

| Causal need | Useful method | Key evidence |
|---|---|---|
| Show X and Y co-vary | comparison, statistics, congruence | cross-case pattern |
| Show X precedes Y | timeline, event sequence | timing evidence |
| Show how X produces Y | process tracing | mechanism traces |
| Estimate effect size | experiment, quasi-experiment, statistics | treated vs comparison units |
| Explain a specific outcome | process tracing, counterfactual, causes-of-effects analysis | within-case evidence |
| Compare rival mechanisms | comparative process tracing | different trace patterns |

## Process-Tracing Evidence Tests

Use these as heuristics:

- Straw-in-the-wind: weakly supports or weakens a hypothesis.
- Hoop test: must pass to remain plausible; passing does not confirm strongly.
- Smoking-gun test: strongly supports if found; absence does not fully disconfirm.
- Doubly decisive test: strongly confirms one hypothesis and disconfirms rivals.

## Counterfactual Prompt

When asked to build a counterfactual, answer:

1. Actual path: what happened?
2. Treatment/change: what is X?
3. Counterfactual intervention: what value of X changes?
4. Held-constant conditions: what remains the same?
5. Mechanism difference: why would M not operate or operate differently?
6. Expected counterfactual outcome: what would likely happen to Y?
7. Evidence: what supports this counterfactual?
8. Rival counterfactuals: what alternative imagined paths are plausible?

