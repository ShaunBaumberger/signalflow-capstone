# SignalFlow

A Product Faculty capstone prototype for turning fictional mobile-banking feedback into evidence-backed Jira work, with a Head of Product making the final decisions.

## Open the demo

Visit the repository's GitHub Pages website, or download `index.html` and open it in a browser. No installation or build step is needed.

Follow the **Happy path** case through Input, Context, Decision, Output and Review. Open the simulated Jira issue to choose its priority and status. Use **Evals** to run all seven cases and record your own verdicts and notes.

## What works

- Thirty fictional feedback records across three simulated source channels.
- A new actionable privacy-mode bug, evidence added to existing work, and an unverified urgent-review allegation.
- A visible refusal at 20 incomplete reports, developer investigation at 21, and later evidence attached to an active investigation.
- Human review, edits, priority and status updates, decision history and evaluation notes.
- A responsive layout for desktop and phones.

## Sample mode and studio AI

The GitHub Pages demo uses built-in sample responses. Jira, source ingestion and all records are simulations. State lasts for the current browser visit.

The same `index.html` includes Product Faculty's helper placeholder and calls `PFAI.generate` when the studio supplies and connects its AI helper. GitHub Pages does not supply that helper. Real AI therefore runs inside Product Faculty's studio, while the public demo remains usable without a key.

## Checks

The current version passed twelve local compatibility checks covering sample cases, studio markers, prepared AI responses, errors and retries, citations, saved human edits, evaluation isolation and mobile layout. Prepared AI responses are test doubles; real AI quality has not been verified by these checks.
