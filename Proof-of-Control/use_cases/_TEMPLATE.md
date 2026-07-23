---
industry: <sector, e.g. consumer-lending>
use_case: <one line: what the AI system does>
claimed_tier: <1-4>
---

# <Short title for the use case>

> *Illustrative, hypothetical scenario for calibration. Not necessarily
> indicative of any specific organization's current state.*

<!--
HOW TO FILL THIS OUT
- A Tier is a *verifiability* claim: how strongly a property is shown to hold,
  not how good the system is. Tier 1 self-reported, Tier 2 third-party
  evaluated, Tier 3 open/independently reproducible, Tier 4 self-enforcing
  (fail-closed).
- Give each of the six domains its own tier in the table below, with a reason.
- The overall claimed_tier is the highest bar the *risky* domains for this use
  case demand, not an average across all six. Low tiers on domains that don't
  carry risk here are expected and fine.
- The "Why not one tier down?" section is the point of the exercise. Fill it.
- These stories are hypothetical illustrations. Keep the disclaimer line above;
  don't describe any real organization's actual current state.
-->

## Scenario
Who the user is, what the AI system does, and what's at stake if verification
is weak. Keep it concrete: one user, one decision, real consequences.

## Claimed tier: Tier <N>
Why this use case belongs at this tier. What does reaching this tier require,
and why does this use case specifically need it?

## Why not one tier down?
The residual-weakness argument. Name the exact failure mode at Tier <N-1> that
this use case cannot tolerate; that gap is what the next tier up closes. For a
Tier 4 claim, this usually means showing why after-the-fact detection (Tier 3)
is too late and enforcement must be fail-closed.

## Tier by domain
How each of the six verification domains lands here, and why. The overall tier
above is set by the domains that carry the most risk for this use case; the
others can sit lower.

| Domain        | Tier | Why |
|---------------|------|-----|
| Provenance    |      |     |
| Authorization |      |     |
| Security      |      |     |
| Identity      |      |     |
| Privacy       |      |     |
| Portability   |      |     |

## Notes / open questions
Anything unresolved, or where reasonable people might place this differently.
