# Slide Blueprint

Author: Mohammad Saleh Nikoopayan Tak

Deck file: `Cotiviti_Prompt2_Presentation_Mohammad_Saleh_Nikoopayan_Tak.pptx`

## Slide 1

Title: Federated Claim-Graph Intelligence

Subtitle: Payment integrity with privacy-preserving pattern recognition and auditor-ready evidence chains

Footer content:
- Author: Mohammad Saleh Nikoopayan Tak
- Report + Hackathon POC + Slide Overview

Visual guide: Minimal executive cover. Use a white canvas, oversized black title, muted gray subtitle, and a right-side claim graph visual with five nodes: Claim, Provider, Code, Member, Policy. Accent colors: red for claim, blue for provider, teal for code, gray for member, amber for policy.

Presenter guidance: Open by saying this is not a generic healthcare automation idea. It is a Cotiviti-relevant payment integrity strategy with a working POC.

## Slide 2

Title: A claim is a relationship graph

Subtitle: Prompt 2 narrowed to clinical decision making and pattern recognition for payment operations.

Body:
- Instead of treating a claim as a flat row, the system links member, provider, CPT, diagnosis, time, modifier, peer group, and policy context.

Output list:
- Classification: is this claim likely clean, questionable, or urgent?
- Inference: which relationship explains the risk?
- Clustering: which providers, codes, and members form unusual groups?
- Time-series anomaly detection: what changed suddenly?

Closing line: Design principle: no score without a story.

Visual guide: Left side text explanation and outputs. Right side graph diagram with Claim in the center connected to Provider, CPT, Member, Policy, and Time.

Presenter guidance: Define the topic. Emphasize that graph intelligence adds context and reasoning to ordinary claims analytics.

## Slide 3

Title: Pressure, connectivity, trust

Subtitle: The market is ready because payment risk is visible, payer data is more connected, and AI governance expectations are rising.

Stat cards:
- $94B+ | FY 2025 CMS improper payment estimates across Medicare FFS, Part C, Part D, and Medicaid
- 455 | Defendants charged in DOJ's June 23, 2026 health care fraud takedown
- $21.2B | Suspect FWA claims Cotiviti says it identified for clients in 2025

Strategic read:
- Earlier lead prioritization matters because bad payments are expensive to chase after the fact.
- Interoperability makes richer graph features possible across claims, policies, encounters, and contracts.
- Trust becomes a feature: privacy, explainability, human review, and drift monitoring have to be built in.

Footer source line: Sources: CMS FY 2025 improper payments fact sheet; DOJ June 23, 2026 takedown; Cotiviti FWA Pattern Review.

Visual guide: Three metric cards across the upper middle and a small bar chart on the right showing improper payment estimates by program.

Presenter guidance: Use this slide to justify urgency. Clarify that improper payment does not mean every case is fraud.

## Slide 4

Title: A natural extension of payment accuracy

Subtitle: The strongest angle is not novelty alone. It is a practical layer on top of Cotiviti's existing strengths.

Column 1:
- Payment accuracy foundation
- Cotiviti already operates across claim accuracy, payment policy, coding validation, clinical review, data mining, contracts, coordination of benefits, and FWA review.

Column 2:
- Interoperability flywheel
- The Edifecs acquisition can strengthen the data fabric needed for connected claim, policy, encounter, and contract evidence.

Column 3:
- Managed-service trust
- Cotiviti can package the evidence chain with specialist review, case tracking, client governance, and provider-facing defensibility.

Closing line: Positioning: broaden learning across payers without broadening raw data exposure.

Footer source line: Sources: Cotiviti payment accuracy pages; Cotiviti Edifecs acquisition announcement.

Visual guide: Three large panels with soft blue, teal, and amber fills. Keep the text sparse and executive.

Presenter guidance: Connect the idea to Cotiviti's current product footprint and operating model.

## Slide 5

Title: Do not ship a black box

Subtitle: The strategic risk is not that the model is imperfect. The risk is acting on a score without context, controls, or accountability.

Risk and control rows:
- False positives | Lead fatigue, delayed payment, and provider abrasion. | Calibrate thresholds by domain and require human review before action.
- Bias | Payer mix and access patterns can masquerade as misconduct. | Monitor cohorts, explain features, and use appeal outcomes as feedback.
- Privacy leakage | Model updates and aggregates can reveal sensitive patterns. | Use secure aggregation, minimum cohort sizes, and client approval gates.
- Adversarial adaptation | Fraud patterns shift once signals are learned. | Track drift, rotate features, and treat investigator notes as signal.

Footer source line: Governance frame aligned to NIST AI RMF: govern, map, measure, manage.

Visual guide: Four horizontal rows. Left side is risk, middle is consequence, right side is control in a light gray panel.

Presenter guidance: Show that the proposal includes operational judgment, not just model enthusiasm.

## Slide 6

Title: Three investable moves

Subtitle: The recommendation is to start narrow, prove lift, then turn the evidence chain into a reusable product layer.

Option cards:
- 1 | Claim-Graph Utility Layer | Create reusable entities, edges, graph features, and explainers for prepay and postpay analytics.
- 2 | Cross-Payer Signal Exchange | Pilot privacy-preserving aggregate learning where raw claims remain inside each client boundary.
- 3 | Evidence Chain Product | Show graph path, peer comparison, time-series change, code-policy rationale, confidence, and next action.

Recommendation banner: Recommended starting point: pair Option 3 with a narrow Option 2 pilot in one domain such as wound care, DME, high-volume labs, or behavioral health.

Visual guide: Three option cards in a row. Use colored number squares and a teal recommendation banner at the bottom.

Presenter guidance: Frame this as a roadmap. The strongest recommendation is evidence-chain productization supported by a narrow federated pilot.

## Slide 7

Title: Claim Integrity Radar architecture

Subtitle: The prototype proves the first principles without overbuilding.

Flow steps:
- Synthetic claims | Generate payer, provider, member, CPT, diagnosis, modifier, week, units, and amount.
- Local baselines | Train peer norms by client, domain, specialty, procedure, and week.
- Federated summary | Share aggregate percentiles and drift signals only. Raw member records stay local.
- Evidence queue | Score anomalies, render graph paths, and recommend an action.

Proof point: The demo can be shown in under three minutes, and every score has a human-readable reason trace.

Visual guide: Four-step process flow with simple arrows. Highlight the Federated summary step in teal.

Presenter guidance: Explain that the POC is intentionally synthetic and transparent so the engineering idea is visible.

## Slide 8

Title: What the evaluator should notice

Subtitle: The demo is built to prove speed to value, not production completeness.

Demo actions:
- Click Train Local Baselines to show peer-group learning.
- Click Share Federated Summary to show zero raw records shared.
- Select a high-risk claim and explain graph path plus reason chain.
- Export an audit packet to show investigator handoff thinking.

Footer source line: Asset: screenshot from the included Claim Integrity Radar POC.

Visual guide: Left panel with four demo actions. Right side should use a screenshot of the working POC dashboard.

Presenter guidance: During video recording, use this slide as the bridge before screensharing the POC.

## Slide 9

Title: A 90-day pilot for speed to value

Subtitle: Constrain the domain, measure lift, and decide whether to invest in a reusable layer.

Pilot plan:
- Weeks 1-2 | Pick one domain | Wound care, DME, high-volume labs, or behavioral health.
- Weeks 3-6 | Build graph features | Entity resolution, peer baselines, time windows, and policy hooks.
- Weeks 7-10 | Compare to current review | Precision, recall proxy, auditor agreement, provider abrasion, and turnaround.
- Weeks 11-12 | Investment decision | Scale, pivot, or stop based on lift and governance readiness.

Closing line: Close with the thesis: no score without a story.

Visual guide: Four-row timeline table with color-coded week labels and a bold final line near the bottom.

Presenter guidance: End decisively. The final takeaway is that this idea is novel enough to stand out and practical enough to pilot quickly.
