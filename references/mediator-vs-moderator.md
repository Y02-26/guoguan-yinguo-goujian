# Mediator Vs Moderator

Use this reference when the user asks about domestic variables, neoclassical realism, foreign policy analysis, leader perception, policy-making process, policy implementation, domestic institutions, party preference, state-society relations, public opinion, alliance reliability, or any case where a variable may be wrongly labeled as a mediator.

This file supplements Chapter 5's discussion of variables and causal diagrams with insights from Feng Wei (2024), “不是所有的国内变量都是中介变量——新古典现实主义理论的中介变量与调节变量辨析”.

## Core Warning

Do not assume that all domestic variables are mediating variables.

Feng Wei's key methodological point is that neoclassical realist research often inserts domestic variables between systemic factors and foreign policy as “mediators”, but many such variables do not meet the standard definition of a mediator. Some are better understood as moderators, background conditions, supplementary factors, or even independent variables.

## Strict Definition: Mediating Variable

A mediating variable transmits the effect of the independent variable to the dependent variable.

```text
X -> M -> Y
```

For a variable to be a mediator:

- X must directly affect M.
- M must directly affect Y.
- X affects Y indirectly through M.
- M is endogenous to the causal process being explained.

In foreign-policy analysis:

```text
systemic pressure -> decision-maker perception -> foreign policy
```

can be a mediator path if systemic pressure directly shapes decision-maker perception, and perception then shapes policy.

## Strict Definition: Moderating Variable

A moderating variable affects the strength, direction, timing, or condition of the relationship between X and Y.

```text
X -> Y
Z modifies the X-Y relationship
```

For a variable to be a moderator:

- Z does not need to be directly caused by X.
- Z changes when, how strongly, or in what direction X affects Y.
- Z often explains why similar systemic pressures produce different policy outcomes.
- Z is often exogenous relative to the X -> Y transmission path.

In foreign-policy analysis:

```text
systemic pressure -> foreign policy
party preference / alliance reliability changes how this pressure is translated into policy
```

is a moderator path if party preference or alliance reliability conditions the effect rather than transmitting it.

## Decision Questions

Ask these before labeling a variable:

| Question | If yes | Likely role |
|---|---|---|
| Is this factor directly changed by X? | Yes | possible mediator |
| Does this factor directly transmit X's effect to Y? | Yes | mediator |
| Does this factor change the strength, direction, timing, or condition of X's effect on Y? | Yes | moderator |
| Can this factor exist or vary independently of X? | Yes | likely moderator or independent variable |
| Is this factor treated as the main cause while X is only background? | Yes | independent variable, not mediator |
| Is this factor simply added beside X without specifying interaction? | Yes | causal mechanism is under-specified |

## Domestic Variables In Neoclassical Realism

Feng Wei argues that much neoclassical realist work has treated domestic variables too loosely. The problem is not that domestic variables are unimportant; the problem is role confusion.

Use this distinction:

```text
Domestic variable directly affected by systemic factor
  -> possible mediator

Domestic variable conditions how systemic factor matters
  -> moderator

Domestic variable directly determines foreign policy while systemic factor is only background
  -> independent variable or primary cause
```

## Three Domestic Decision Processes

The article discusses domestic decision processes in neoclassical realist foreign-policy models. A useful role distinction is:

- **Decision-maker perception**: more likely to serve as a mediator when directly shaped by systemic pressure.
- **Policy-making process**: often better treated as a moderator when it conditions how pressure becomes policy.
- **Policy-implementation process**: often better treated as a moderator when it shapes how policy choices are carried out.

Do not apply this mechanically. Check the causal diagram in the specific topic.

## Australia-China Policy Example

Feng Wei uses Australia's China policy since 2008 to illustrate a framework containing both mediating and moderating variables:

- Independent variable: national strategic environment.
- Mediating variable: threat urgency, because the strategic environment directly shapes decision-makers' perception of threat urgency.
- Moderating variables: party strategic preference and alliance reliability, because they help explain variation in hedging/balancing choices and condition policy direction or form.
- Dependent variable: Australia's China policy.

Use this as a role-identification example, not as a template to copy into unrelated topics.

## Common Mistakes To Prevent

- Calling every domestic variable a mediator.
- Treating any variable between “system” and “policy” in a narrative as a mediator.
- Adding systemic and domestic factors side by side without explaining their interaction.
- Failing to show whether the systemic variable directly affects the domestic variable.
- Ignoring that a domestic variable may condition the X-Y relationship rather than transmit it.
- Letting domestic variables quietly become the real independent variable while still calling them mediators.

## Output Pattern

When role confusion is possible, produce a table:

| Candidate variable | Does X affect it? | Does it affect Y? | Does it condition X -> Y? | Best role | Reason |
|---|---|---|---|---|---|
| | | | | mediator / moderator / independent variable / confounder | |

Then draw the causal relation:

Mediator:

```text
X -> M -> Y
```

Moderator:

```text
X -> Y, with Z conditioning the strength/direction/timing of the relation
```

Independent variable:

```text
Z -> Y, while X is background or scope condition
```

## Source Note

Use this file as a methodological supplement. The skill remains centered on Chapter 5 “构建因果解释”; Feng Wei (2024) strengthens the variable-identification part by clarifying mediator/moderator distinctions.
