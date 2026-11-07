# SIMULATION GUIDE — STAND UP YOUR OWN NODE

## What a node is

A node is one community's mirror: its record, its categories,
its calibrations, its results. Nodes are independent. The network
is what happens when nodes publish to each other.

## Steps

1. **Fill in the city template** ([city-template/CITY-NODE.md](city-template/CITY-NODE.md)):
   your place, your population shape, your category list (what
   needs funding first, in your place's own order), your
   statistics sources, and your documented history — with its
   gaps declared, not papered over.
2. **Write your first question** and put it through the
   nine-judge gate ([NINE-JUDGES.md](NINE-JUDGES.md)). Start with
   a counterfactual from your own record — a decision your place
   actually faced, run the other way.
3. **Calibrate.** Set the decision layers
   ([CALIBRATION.md](CALIBRATION.md)): base rates, the fast
   decider, escalation thresholds, and — if you are modelling the
   Trust — the allotment band you are trying to find, not assert.
4. **Enter the adversary.** Controllers, manufactured inputs,
   captured structures. A run without them is a fair-weather
   model of a place that does not exist.
5. **Run, then run the fairness inversion.** Same inputs, the
   oversight layer doing its job. Publish both result sets.
6. **Share.** File your results in the common format (below) so
   the next community can adopt, adapt, or refute them.

## Sharing format

Each published result set states:

- the community and the node version;
- the question, exactly as it passed the gate;
- the record and statistics used, with gaps declared;
- the calibration settings (layers, thresholds, bands);
- the census of outcomes (what the agents did, in numbers);
- the operators' reading, labelled as reading — separate from
  the numbers;
- what would make the operators re-run.

## On engines

The founding runs used a locally hosted open-source agent
simulator (MiroFish/OASIS class) with local models and no cloud
keys. Any engine that honours the tiered calibration contract —
cheap decisions cheap, judgement escalated, words generated only
when needed — can serve as a node's engine. Engine choice is
local; the gate and the sharing format are the shared parts.
