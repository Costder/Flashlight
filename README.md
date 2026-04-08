# Flashlight

Core idea: connect internal model change to behavioral cause.

`Flashlight` is a documentation-first causal interpretability project. Its purpose is to move beyond correlational explanations and test whether specific internal changes actually drive observable behavioral differences in a model.

The emphasis is intervention-based validation. It is not enough to find an internal signal that co-occurs with a behavior. The research question is whether changing that internal signal reliably changes the behavior in the predicted direction.

## Why This Matters

Interpretability work often stops at descriptive patterns:

- this neuron activates here
- this feature cluster appears there
- this representation correlates with a response style

Flashlight is interested in the next step: causal evidence. If an internal feature matters, intervention should reveal that relationship more directly.

## System Outline

- `dummy brains`: controlled model surrogates used to make analysis loops cheaper and more testable
- `analyzer`: the component that extracts candidate internal signals and hypotheses
- `intervention loop`: the validation process that perturbs internal state and measures behavioral effects

## Scope

This repository documents the conceptual system, research direction, and validation philosophy. Detailed instrumentation, training procedures, and experimental implementation are intentionally kept abstract.

## Repository Map

- `STATUS.md`: current project state
- `docs/overview.md`: plain-language overview
- `docs/methodology.md`: high-level methodology
- `docs/roadmap.md`: staged research plan
