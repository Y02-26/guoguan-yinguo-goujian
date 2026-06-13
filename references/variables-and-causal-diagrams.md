# Variables And Causal Diagrams

Use this reference when the user needs to identify variables or draw a causal diagram.

## Why Introduce Variables

The chapter introduces variables because causal explanation requires researchers to describe change and relationships among changing things. A concept becomes a variable only in a research context where it can vary.

Example logic:

- Geography may be treated as a constant in a short period.
- Geography may become a variable in a long historical period.

## Independent And Dependent Variables

### Independent variable

The independent variable is the proposed cause.

Ask:

- What changes first?
- What factor is expected to produce change in the outcome?
- Can this factor take different values in the research scope?

### Dependent variable

The dependent variable is the outcome to be explained.

Ask:

- What result needs explanation?
- Is the result occurrence/non-occurrence, degree, timing, direction, or form?
- What are the unit, period, and scope?

## Mediating Variable

A mediating variable lies between the independent and dependent variables. It expresses the transmission path from cause to outcome.

```text
X -> M -> Y
```

Use a strict test:

- X must directly affect M.
- M must directly affect Y.
- M explains how X's effect is transmitted.

Do not call a variable a mediator merely because it is “between” the international system and foreign policy in a loose narrative.

## Moderating Variable

A moderating variable changes the strength, direction, timing, or condition of the relationship between X and Y.

```text
Z changes how X affects Y
```

Unlike a mediating variable, a moderating variable does not need to be directly caused by X. It answers:

- When does X matter more or less?
- Under what condition does X produce Y?
- Does Z change the direction of X's effect?
- Does Z explain why similar X leads to different Y?

If the case involves domestic variables in foreign-policy analysis, read `mediator-vs-moderator.md` before finalizing the causal diagram.

## Confounding Variable

A confounding variable affects both the supposed cause and the outcome. It may create a misleading relation between X and Y.

```text
C -> X
C -> Y
```

Use it when checking whether the relation between X and Y is false or spurious.

## Collider

A collider is a common result of two variables.

```text
X -> D <- Y
```

Conditioning on a collider can create misleading association. Be careful when the research only selects cases that share a post-outcome or post-treatment feature.

## Causal Diagrams

The chapter discusses causal diagrams as tools for clearly expressing variable relationships.

Basic rules:

- Nodes represent observable variables.
- Arrows represent temporal and causal direction.
- An arrow means the researcher assumes a causal relation.
- No arrow means the researcher assumes no direct causal relation.
- A diagram is a representation of assumptions, not direct proof of causation.

Basic diagram:

```mermaid
flowchart LR
  X["自变量 / 原因 X"] --> M["中介变量 / 机制环节 M"]
  M --> Y["因变量 / 结果 Y"]
  C["混杂变量 C"] --> X
  C --> Y
```

## Do Not Confuse These

| Item | Meaning | Common mistake |
|---|---|---|
| Concept | Abstract idea | Treating a vague concept as already measurable |
| Variable | Concept with changing values | Forgetting the research context |
| Indicator | Observable measure | Mistaking indicator for the concept itself |
| Mechanism | Process linking cause and outcome | Treating any intermediate variable as a full mechanism |
| Causal diagram | Assumption map | Treating the diagram as evidence |

## Domestic Variable Warning

Domestic variables are not automatically mediating variables. A domestic factor can be:

- a mediator, if systemic pressure directly changes it and it transmits that pressure to policy;
- a moderator, if it conditions how systemic pressure affects policy;
- an independent variable, if it directly explains the outcome while systemic factors are only background;
- a confounder or omitted factor, if it shapes both the supposed cause and the outcome.

Always locate the domestic variable in the causal diagram before naming its role.
