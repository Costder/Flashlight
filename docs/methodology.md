# Methodology

## Working Principle

Flashlight uses a high-level three-part methodology:

- build controllable research environments
- extract candidate internal signals
- validate claims through intervention

The emphasis is on causal evidence, not only descriptive insight.

## Dummy Brains

`Dummy brains` are simplified or controlled model settings used to make causal experiments tractable.

They serve several purposes:

- reduce experimental cost
- make behaviors easier to isolate
- provide a cleaner environment for hypothesis testing
- support faster iteration before moving to harder model settings

The point is not to perfectly reproduce a full production model. The point is to create a research surface where internal-behavior relationships can be probed with tighter control.

## Analyzer

The `analyzer` inspects internal activity and proposes candidate explanations for observed behavior.

At a high level, it is responsible for:

- identifying internal features or regions of interest
- linking those signals to behavioral hypotheses
- ranking which hypotheses are strong enough to justify intervention

This repository keeps the exact extraction and scoring techniques abstract. What matters publicly is the role the analyzer plays in the causal pipeline.

## Intervention Loop

The `intervention loop` is where interpretation claims are tested.

High-level sequence:

1. observe a behavioral pattern worth explaining
2. isolate candidate internal mechanisms
3. apply controlled interventions to those mechanisms
4. measure whether behavior changes as predicted
5. compare intervention results against the original hypothesis

If the behavior moves in the expected way, confidence increases that the internal mechanism is causally relevant. If it does not, the interpretation may be correlational, incomplete, or wrong.

## Methodological Boundary

This document intentionally stays high level. It describes the structure of the research method without exposing detailed pipelines, instrumentation internals, or intervention recipes.
