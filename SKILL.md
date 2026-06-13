---
name: guoguan-yinguo-goujian
description: Build rigorous causal explanations for international relations and political science research. Use when the user needs to construct, critique, revise, or operationalize a causal argument, causal mechanism, causal diagram, research hypothesis, scope condition, rival explanation, counterfactual, process-tracing design, case-comparison strategy, or empirical anomaly response for IR research, thesis proposals, papers, literature-based theory building, or research-method training.
---

# 国关因果构建

Use this skill in Chinese by default. Help the user turn an international relations research idea into a clear causal explanation that can support a thesis, article, proposal, or empirical test.

This skill is based on a paraphrased synthesis of the chapter “构建因果解释” from 《国际关系研究实用方法》 and related research-design principles. Do not reproduce long passages from the source. Use the knowledge base to generate practical research artifacts.

## Core Workflow

Move from idea to research design in this order:

1. Define the phenomenon to be explained: outcome Y, unit, time, space, variation, and puzzle.
2. Clarify the causal relation: regularity, counterfactual dependence, mechanism, or a combination.
3. Map variables: X, Y, mediator, moderator/scope condition, confounder, collider, and rival causes.
4. Build the explanation: why X affects Y, through which mechanism, under what conditions, compared with what alternatives.
5. Translate the explanation into hypotheses and observable implications.
6. Choose causal-inference support: counterfactual reasoning, case comparison, process tracing, congruence analysis, or mixed qualitative/quantitative logic.
7. Revise the hypothesis when evidence fails: check measurement, case scope, omitted variables, mechanism gaps, and boundary conditions.

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

- Causal design table: puzzle, question, Y, X, mechanism, scope, rival explanations, evidence, method.
- Causal diagram in Mermaid or text.
- Mechanism chain with observable traces.
- Hypothesis set: main hypothesis, mechanism hypotheses, scope hypotheses, rival hypotheses.
- Counterfactual and case-comparison plan.
- Process-tracing evidence table.
- Revision memo for a weak or failed causal argument.

## Guardrails

- Do not treat “X affects Y” as a complete explanation. Require mechanism, scope, and rival explanations.
- Do not invent real citations or literature. If literature is needed, ask for sources or use a separate search workflow when explicitly requested.
- Distinguish concept, variable, indicator, hypothesis, mechanism, and evidence.
- Warn when the claim exceeds the evidence or when case selection creates selection bias.
- State when a point is an inference from the knowledge base rather than an exact source claim.
