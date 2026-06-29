# Claim Integrity Radar POC

Author: Mohammad Saleh Nikoopayan Tak

## What this demonstrates

Claim Integrity Radar is a simple browser-based reviewer cockpit prototype for prompt 2. It shows how clinical decision making and pattern recognition can support payment operations through:

- Synthetic healthcare claims
- Provider, member, code, diagnosis, and policy graph relationships
- Local payer baselines
- A simulated federated summary that shares only aggregate peer statistics
- Explainable anomaly scoring with an evidence card for each flagged claim
- A clear human-review guardrail for every recommendation

## How to run

Open `index.html` in any modern browser. No install step is required.

Recommended demo flow:

1. Click `Train Local Baselines`.
2. Click `Share Federated Summary`.
3. Move the risk threshold slider.
4. Select a high-risk claim from the review queue.
5. Explain the graph path, the scoring reasons, and the recommended action.
6. Click `Export Evidence Card` to show how a reviewer handoff could work.

## Design note

This is a proof of concept, not a production fraud model. The dataset is synthetic, the scoring engine is transparent, and the federated exchange is simulated. That is intentional: the goal is to prove the concept quickly while making the core engineering ideas visible.

The system does not approve, deny, or alter payment. It ranks cases for human review, stores evidence, and makes override or monitoring decisions easier to explain.
