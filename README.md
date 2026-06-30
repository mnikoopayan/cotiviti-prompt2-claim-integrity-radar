# Cotiviti Intern Assessment, Prompt 2

**Author: Mohammad Saleh Nikoopayan Tak**

## Federated Claim-Graph Intelligence for Payment Integrity

A reviewer cockpit that treats each claim as an explainable relationship graph rather than a flat row, and turns anomaly scores into auditor-ready evidence cards for human review.

> Design principle: no score without a story.

## At a glance

This submission addresses Prompt 2, clinical decision making and pattern recognition in health care. It shows how classification, inference, clustering, and time-series anomaly detection can prioritize payment review while preserving privacy and keeping a human reviewer in the loop. The posture is a reviewer cockpit, not autonomous payment denial. Every high-risk lead arrives as an evidence card with peer context, graph path, policy cue, uncertainty, and a recommended review action.

## Live demo

Open the hosted prototype, with no install step:

https://mnikoopayan.github.io/cotiviti-prompt2-claim-integrity-radar/claim-integrity-radar-poc/

To run it locally, open `claim-integrity-radar-poc/index.html` in any modern browser.

Recommended walkthrough, about ninety seconds:

1. Click **Train Local Baselines**.
2. Click **Share Federated Summary**, which exchanges only aggregate peer signal.
3. Select a high-risk claim from the review queue.
4. Read the graph path and the evidence card.
5. Click **Export Evidence Card** to show a reviewer handoff.

## Repository contents

- `Cotiviti_Prompt2_Report_Mohammad_Saleh_Nikoopayan_Tak.docx`, the two-page written report with a third-page bibliography.
- `Cotiviti_Prompt2_Presentation_Mohammad_Saleh_Nikoopayan_Tak.pptx`, an executive overview of the report and proof of concept.
- `claim-integrity-radar-poc/`, the browser-based Claim Integrity Radar prototype. No install step is required.

## Strategic thesis

Cotiviti can turn privacy-preserving claim graphs into a reviewer cockpit that surfaces suspicious payment patterns earlier, produces an evidence card for every lead, and broadens cross-payer learning without exposing raw claims.
