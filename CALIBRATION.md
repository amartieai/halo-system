# CALIBRATION — HOW DECISIONS ARE FITTED TO TASKS

The calibration principle: **a model should be matched to what its
task actually needs.** A task that calls for a quick choice should
not pay for deep reasoning it cannot use; a task that calls for
judgement should not be handed to a model too shallow to make a
real choice. Both directions of mis-fit are failures, and any
large simulation that ignores this pays for one of them in time
or in truth.

## The tiered decision stack

- **Layer 0 — the activity clock (no model).** Most agents, most
  rounds, do nothing. Inactivity is decided by per-role base
  rates. It is also realistic: real populations are mostly
  inactive in any given hour.
- **Layer 1 — the fast decider.** An active agent's action choice
  is made by a small, fast decision model (choice + confidence
  score) over a *compressed* context: who the agent is in one
  line, the top of its feed, its last action.
- **Layer 2 — escalation.** Low confidence, or a principal agent,
  escalates the step to a larger model. The decider is supervised,
  not trusted.
- **Layer 3 — generation.** Only steps that produce words for
  others to read call the language model. A like never needs one.
  A post does.

Measured on the founding stack, this shape converts an evening's
14-agent run into hundreds of agents comfortably, and thousands
with per-round crowd sampling (activate a random slice each
round; crowd behaviour still reads true statistically).

## Calibrating the amounts

The Trust's personal allotment is a calibration problem, not a
political slogan: the amount must be *found* — the level that
supports a life in that community while sitting below the level
at which people leave work they would otherwise keep — and the
mirror is where it is found, per community, before any money
moves.

## Adversarial calibration

A mirror that models only honest flows is calibrated wrong. The
following are first-class inputs, not footnotes:

- **The controllers.** Actors whose interest is control of the
  money and of the people, modelled as agents with their own
  objectives.
- **Manufactured inputs.** Propaganda, fake news, manufactured
  law, staged crises, fake wars, and fear itself — entered as
  measurable interventions with measurable effects.
- **Captured structures.** Funds and bodies that collect in the
  name of a purpose they do not serve (the founding example: a
  victims' fund that never reaches victims). These are modelled
  as leaks with named beneficiaries.

## Removal recalibrates

**The calibration grows with each thing removed.** Deleting a
captured structure from the model is not a local edit: every flow
that passed through it reroutes, every downstream number changes,
jobs and institutions realign. Simulations must therefore be
re-run after each removal, and sequences of removals tested in
different orders — the order is itself a variable.

## The fairness inversion test

Every civic simulation in this project should also be run in
reverse: same community, same history, with the judicial and
regulatory layer set to *doing its one job* (regulators
reprimanding first, courts answering, disclosure complete).
Compare the outputs. The design's claim — unlawfulness down,
desperation down, professional bloat down — stands or falls on
that comparison, in public, on your numbers.
