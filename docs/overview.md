# Overview

Flashlight is about causal interpretability for language models.

In plain terms, the project asks a harder question than standard interpretability: when a model behaves differently, which internal change actually caused that difference?

Many interpretability approaches identify patterns that are interesting but inconclusive. A feature may correlate with a behavior without being responsible for it. Flashlight tries to close that gap by combining internal analysis with controlled interventions.

The intended result is a more defensible chain of evidence:

- observe a behavioral pattern
- identify a candidate internal mechanism
- intervene on that mechanism
- test whether the behavior changes accordingly

That framing makes the work relevant to debugging, alignment, capability analysis, and evaluating whether an interpretation claim is strong enough to trust.
