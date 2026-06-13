# Explanation Principles

Use this reference when checking whether a causal explanation satisfies the chapter's principles.

## Temporal Order

The cause must appear before the outcome.

Ask:

- Did the cause happen before the result?
- Did change in the cause precede change in the outcome?
- Is reverse causality possible?
- Are X and Y both consequences of an earlier factor?

## Association / Correlation

There should be observable association or co-variation between cause and outcome.

This may appear as:

- cases with X tend to have Y;
- cases without X tend not to have Y;
- increase in X is associated with increase or decrease in Y;
- within a case, change in X is followed by change in Y.

But association alone is not causation.

## Avoid False And Spurious Correlation

The chapter warns that a relation may look causal when it is not.

Important risks:

- False correlation: apparent association caused by research design, selection, or other distortion.
- Spurious correlation: X and Y appear related because both are affected by another factor.
- Systematic measurement error: measurement makes a relation appear, disappear, or change direction.

Practical check:

```text
If X and Y are associated, ask what else could generate this association.
```

Keep source-faithful language: 虚假相关、伪相关、其他可能因素、系统性测量误差.

## Counterfactual Or Mechanism

On the basis of temporal order and association, the chapter emphasizes that causal explanation should further rely on at least one of:

- constructing a counterfactual;
- tracing a causal mechanism.

In plain language:

```text
If X had been absent, would Y still have happened?
If X produced Y, through what process did it do so?
```

## Checklist

| Principle | Question | If weak, revise by |
|---|---|---|
| Temporal order | Does X precede Y? | rebuild timeline |
| Association | Is X related to Y? | compare cases or clarify variation |
| Avoid false relation | Could the relation be false/spurious? | check selection, third factors, measurement |
| Counterfactual | Would Y differ without X? | construct plausible alternative |
| Mechanism | How does X produce Y? | specify entities, activities, sequence |
