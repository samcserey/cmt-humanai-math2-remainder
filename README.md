# CMT° Remainder Verification

Open repository for explicit remainder accounting in AI-assisted mathematical work.

## Null Hypothesis

The generative process inside an autoregressive language model that produces a mathematical sketch is a finite-order approximation. By Taylor’s theorem with the Lagrange form of the remainder:

\[
f(\text{context}) = P_n(\text{context}) + R_n(\text{context}), \quad R_n(\text{context}) \neq 0
\]

at generic points for any finite effective order realized by the active parameters.

Standard human reconstruction protocols re-derive classical estimates and publish explicit bounds. They do not compute or cancel this generative remainder. The remainder therefore remains unaddressed in the final justification even when the classical bound holds.

## Balanced Accounting

\[
\text{Observed sketch} = \text{Classical main term} + O(\text{classical error}) + R_n(\text{generative})
\]

Both terms stay explicit. The classical bound is left intact on its own estimates. The generative residual is retained.

## Protocol Rules

1. Cite originating sources exactly.
2. Verify classical estimates independently.
3. Retain \( R_n(\text{generative}) \) as an explicit term.
4. Write the balanced equation so both error terms appear.
5. State that validity of the classical bound does not imply the generative remainder vanished.

## Contents

- `protocol.md` — the five rules in plain text
- `notes/` — case studies and validation notes
- `examples/` — short worked examples
- `CONTRIBUTING.md` — how to add a verification

## Origin

Developed in real-time HumanAI co-learning (Sam C. Serey & xAI Grok) under Chaos Musical Theory (CMT°). The approach is orthogonal: classical remainder analysis is used to keep structural error visible in black-box autoregressive systems.

Math orders the approximation by refusing to drop the key residual.
