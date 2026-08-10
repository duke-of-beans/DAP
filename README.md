# DAP — Deliberative Assembly Protocol

A verification residual framework for multi-model AI systems.

## The problem

When several models weigh in on the same question, most systems either force a single answer through majority vote or averaging, or they punt and show all the disagreement unfiltered. Forcing consensus hides real, useful disagreement. Showing everything unfiltered dumps the problem back on whoever's reading it.

## What it does

DAP tracks what's actually agreed on across models and — just as importantly — what's left over: the residual disagreement that can't be honestly reconciled. Rather than collapsing that residual into a false consensus or a wall of raw disagreement, it surfaces it as its own structured output: here's where the models agree, here's where they don't, and here's what that split actually turns on.

## Part of a family

One of several reasoning-layer engines built around routing, scoring, and gating AI output on epistemic grounds. See [davidkirsch.me/builds](https://davidkirsch.me/builds) for how they fit together.
