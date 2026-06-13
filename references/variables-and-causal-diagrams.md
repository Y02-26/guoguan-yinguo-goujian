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
