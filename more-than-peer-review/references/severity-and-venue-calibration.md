# Severity and venue calibration

Use severity and venue tier privately before selecting the review thesis. These
labels guide depth, remedy, and recommendation. Do not copy P labels into the final
review unless the venue explicitly asks for them.

## Internal severity

- `P0` means the central result is demonstrably false, unsafe, internally
  contradictory, or defeated by a concrete case inside the stated model. Repair
  requires replacing the central contribution rather than revising its presentation.
- `P1` means a central mechanism, assumption, proof, threat model, or evaluation fails
  in a realistic core setting. `P1-high` is effectively fatal. `P1-low` is serious
  but may support a substantially redesigned resubmission.
- `P2` means a substantive but bounded problem. It limits scope, evidence, novelty,
  reproducibility, or practical use, yet has a plausible remedy through a targeted
  mechanism change, analysis, experiment, or claim narrowing.
- `P3` means a local clarity, presentation, notation, or minor reporting issue that
  should not determine the recommendation.

Assign severity from five questions. How central is the affected claim? How realistic
is the triggering case? How far do the consequences propagate? How much work is
needed to repair it? How certain is the evidence? Do not infer severity from the
number of symptoms, and do not raise a label merely because the venue is selective.

## Match comment strategy to severity

For a supported `P0` or `P1-high`, make it the review thesis and pursue it vertically.
Show the construction or contradiction, explain why the proposed safeguard fails,
and trace the result into the evaluation and conclusion. Three or four connected
comments may all arise from this root failure.

For `P1-low` or `P2`, state the limitation and give a proportionate repair path. Do
not stretch one bounded concern into the entire review. Continue the private search
for another serious or related issue. If none exists and there are only one or a few
moderate concerns, the final review should remain focused but solution-oriented.

Several related `P2` findings may collectively expose a `P1` root cause. Several
unrelated `P2` findings do not become fatal merely by counting them. `P3` findings
belong in the private record unless a small correction would materially help the
authors.

## Establish venue tier

Use a tier supplied by the user or already available in the active review material.
For journals, record `Q1`, `Q2`, `Q3`, or `Q4`. For conferences, record the applicable
CORE rank such as `A*`, `A`, `B`, or `C`. Rankings can depend on year, category, and
source. Never invent a tier. If it is unknown, use `tier-neutral` calibration and ask
only when the missing tier would materially change the recommendation.

Venue tier changes the acceptance threshold, not factual certainty or professional
conduct.

- `Q1` and `A*` demand a clearly important contribution, strong novelty, closure of
  central edge cases, and evidence that directly establishes the headline claims.
- `Q2` and `A` remain demanding but can tolerate a narrower contribution when the
  mechanism and evidence are sound.
- `Q3` and `B` use a standard contribution threshold and should favor revision when
  a useful core result is recoverable.
- `Q4` and `C` may tolerate narrower novelty, limited evaluation breadth, or more
  presentation debt when the central result remains correct and useful.

No venue tier excuses a `P0` or supported `P1-high`. A top tier does not turn an
ordinary `P2` into a fatal technical error. A lower tier does not make a false or
unsafe central claim acceptable.

## Recommendation calibration

Use these as defaults, then map to the exact labels offered by the venue.

- A supported `P0` or `P1-high` normally means `Reject` at every tier.
- A `P1-low` with a plausible redesign normally means `Reject and Resubmit` for a
  Q1 or Q2 journal. A Q3 or Q4 journal may use `Major Revision` when the repair fits
  a normal revision cycle. At an A* or A conference it normally means `Borderline
  Reject` or the nearest weak-reject score.
- One or a few `P2` issues with concrete remedies may mean `Reject and Resubmit` or
  `Major Revision` at Q1, and normally `Major Revision` at Q2. Q3 and Q4 should favor
  revision over rejection when the core contribution is correct.
- At A* a central P2 may support `Borderline Reject`. At A it may sit near the
  borderline. At B or C, an isolated P2 should not normally determine rejection
  unless it defeats the central claim.
- Multiple aligned `P2` findings may justify `Reject and Resubmit` or `Borderline
  Reject` when their shared cause prevents the central claim from being established.

If `Reject and Resubmit` or `Borderline Reject` is unavailable, choose the nearest
official label and preserve the intended calibration in the confidential rationale.
Never tell authors that a paper is rejected because its venue is highly ranked.
