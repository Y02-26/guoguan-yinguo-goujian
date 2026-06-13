---
name: guoguan-yinguo-goujian
description: Construct causal explanations for international relations research according to Chapter 5 "构建因果解释" of 《国际关系研究实用方法》, with enhanced guidance for distinguishing mediating variables, moderating variables, and domestic variables in IR theory. Use when the user needs to clarify causal relations, distinguish variables, draw causal diagrams, build counterfactuals or causal mechanisms, formulate causal hypotheses, or revise hypotheses after empirical anomalies. Keep outputs faithful to the chapter, topic-sensitive, and non-template-driven.
---

# 国关因果构建

Use this skill in Chinese by default. Help the user construct a causal explanation in the sense of Chapter 5, not a full literature-review, statistical-method, or thesis-writing workflow.

The knowledge base is a paraphrased synthesis of the user-provided PDF segment for Chapter 5 “构建因果解释”. The PDF text layer had OCR/encoding noise, so avoid exact quotation unless the user checks the original book. Prefer source-faithful concepts, section structure, and practical application.

## Anti-Template Rule

Do not mechanically give every topic the same causal mechanism.

Before drafting a mechanism, first identify the topic's specific features:

- What is the concrete outcome to be explained?
- Who are the relevant actors or entities?
- What is the issue area: security, alliance, international organization, IPE, norms, diplomacy, conflict, development, etc.?
- What is the historical or institutional context?
- What changes in beliefs, incentives, capabilities, information, legitimacy, or constraints?
- What sequence is plausible in this particular case?
- What would make this topic different from another superficially similar topic?

Use templates only as a final checklist or formatting aid. Do not let a template determine the substance of the mechanism.

## Variable-Role Gate

Before calling a domestic factor, actor perception, policy process, institution, party preference, public opinion, state-society relation, or alliance reliability a “mediating variable”, check whether it truly transmits the effect of the independent variable to the dependent variable.

Apply the Feng Wei 2024 distinction:

- **Mediating variable**: is directly affected by the independent variable and then directly affects the dependent variable. It answers “how does X pass through this factor to produce Y?”
- **Moderating variable**: changes the strength, direction, timing, or condition of the X-Y relation. It does not need to be directly caused by X. It answers “when, under what condition, or in which direction does X affect Y?”
- **Domestic variable**: is not automatically a mediating variable. It may be a mediator, moderator, independent variable, background condition, or omitted factor depending on the causal diagram.

If the user asks about neoclassical realism, domestic politics, foreign policy analysis, leader perception, policy-making process, policy implementation process, party preference, state-society relation, domestic institution, or alliance reliability, read `references/mediator-vs-moderator.md` before constructing the mechanism.

## Chapter-Based Workflow

Follow the chapter's logic:

1. **明确因果关系的含义**: 区分规律性因果、反事实因果、机制性因果；说明研究是“由因索果”还是“由果溯因”。
2. **引入变量语言**: 界定自变量、因变量、中介变量、混杂变量、碰撞变量等，并用因果图表示变量关系。
3. **检查构建原则**: 至少检查时序性、相关性，并排除虚假相关、伪相关、系统性测量误差等风险。
4. **增强因果推断**: 在时序性和相关性的基础上，构建反事实，或者追踪因果机制；能同时做更好。
5. **形成因果假设**: 将因果解释转化为明确、具体、可检验、非同义反复的因果假设。
6. **必要时修改假设**: 遇到经验反常时，优先检查概念、测量和事实；再考虑限界条件或修改机制。

## Reference Selection

Read only the needed reference:

- `references/knowledge-map.md`: Chapter map, OCR caveats, and what each reference covers.
- `references/causal-relations.md`: Regularity, counterfactual, mechanism, effects-of-causes, causes-of-effects.
- `references/variables-and-causal-diagrams.md`: Variables, mediators, confounders, colliders, causal diagrams.
- `references/mediator-vs-moderator.md`: Feng Wei 2024-based guide for distinguishing mediating variables, moderating variables, and domestic variables, especially in neoclassical realist foreign-policy analysis.
- `references/explanation-principles.md`: Temporal order, association, false/spurious correlation, counterfactuals, mechanisms.
- `references/counterfactuals-and-mechanisms.md`: How the chapter treats counterfactual construction and causal mechanism tracing.
- `references/causal-hypotheses.md`: Meaning, requirements, induction, deduction, abduction, and causal-hypothesis formulation.
- `references/hypothesis-revision.md`: Empirical anomalies, scope/limit conditions, and hypothesis modification.
- `references/chapter-examples.md`: Chapter examples and method table reconstructed from the PDF, with OCR caveats.
- `references/templates.md`: Non-substantive output aids. Use only after topic-specific reasoning.

## Output Discipline

- Do not present `S` and `R` as chapter terminology. If useful, write “适用范围/限界条件” and “其他可能因素、虚假相关或伪相关风险”.
- Do not overclaim that the chapter provides a complete research-design workflow. Keep the focus on causal explanation.
- Do not invent citations or literature.
- Do not reuse a generic mechanism just because two topics share the same abstract variable names.
- When using a term that comes from broader methodology but is not clearly in the chapter, label it as an auxiliary expression.
- Prefer outputs such as: topic-specific causal-relation diagnosis, variable table, causal diagram, counterfactual note, mechanism chain, causal-hypothesis draft, hypothesis-revision memo.
