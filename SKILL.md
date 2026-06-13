---
name: guoguan-yinguo-goujian
description: Build causal explanations for international relations and political science research. Use when the user needs to clarify a causal relation, identify causes and outcomes, build a causal mechanism, state the explanation's applicable range, turn the explanation into a research hypothesis, or revise an explanation when empirical facts do not fit.
---

# 国关因果构建

Use this skill in Chinese by default. Help the user turn an international relations research idea into a clear causal explanation that can support a thesis, article, proposal, or empirical test.

This skill is based on a paraphrased synthesis of the chapter “构建因果解释” from 《国际关系研究实用方法》 and related research-design principles. Do not reproduce long passages from the source. Use the knowledge base to generate practical research artifacts.

## Core Workflow

Move from idea to research design in this order:

1. Define the phenomenon to be explained: outcome Y, unit, time, space, variation, and puzzle.
2. Clarify the causal relation: regularity, counterfactual dependence, mechanism, or a combination.
3. Map the basic elements: cause, outcome, mediator, possible confounder, and applicable range.
4. Build the explanation: why the cause affects the outcome, through which mechanism, and under what conditions.
5. Translate the explanation into hypotheses and observable implications.
6. Support the explanation with counterfactual reasoning and/or causal-mechanism tracing when appropriate.
7. Revise the hypothesis when evidence fails: check measurement, applicable range, omitted variables, and mechanism gaps.

## Reference Selection

Load only the needed reference:

- `references/knowledge-map.md`: Read first when orienting the chapter, choosing which reference file to load, or explaining source caveats.
- `references/causal-relations-and-variables.md`: Use for causality definitions, variable roles, causal diagrams, confounders, colliders, mediators, and moderators.
- `references/building-causal-explanations.md`: Use for the core principles of constructing causal explanations, including temporal order, correlation, excluding rival causes, counterfactuals, and mechanisms.
- `references/mechanisms-and-hypotheses.md`: Use for generating causal mechanisms, hypotheses, propositions, scope conditions, and observable implications.
- `references/counterfactuals-and-case-methods.md`: Use for counterfactual construction, case-study inference, process tracing, congruence analysis, comparison, and causal-effect logic.
- `references/hypothesis-revision.md`: Use when empirical anomalies appear or when the user needs to revise a hypothesis, narrow scope, or improve theoretical fit.
- `references/templates-and-checklists.md`: Use when the user wants a direct output template, critique rubric, proposal scaffold, or quick diagnostic checklist.

## Response Pattern

Prefer producing a concrete artifact rather than general advice. Common outputs:

- Causal design table: puzzle, question, outcome, cause, mechanism, applicable range, evidence, and main inference risk.
- Causal diagram in Mermaid or text.
- Mechanism chain with observable traces.
- Hypothesis set: main hypothesis, mechanism hypotheses, and applicable-range statements.
- Counterfactual and case-comparison plan.
- Process-tracing evidence table.
- Revision memo for a weak or failed causal argument.

## Guardrails

- Do not treat “X affects Y” as a complete explanation. Require temporal order, association, mechanism, and applicable range.
- Do not invent real citations or literature. If literature is needed, ask for sources or use a separate search workflow when explicitly requested.
- Distinguish concept, variable, indicator, hypothesis, mechanism, and evidence.
- Warn when the claim exceeds the evidence or when case selection creates selection bias.
- State when a point is an inference from the knowledge base rather than an exact source claim.
