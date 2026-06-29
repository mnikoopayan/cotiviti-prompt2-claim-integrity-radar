# Cotiviti Intern Assessment: Prompt 2

Author: Mohammad Saleh Nikoopayan Tak

## Topic

Federated Claim-Graph Intelligence for Payment Integrity

This submission focuses on prompt 2: clinical decision making and pattern recognition in health care. The core idea is to model payment integrity as an explainable claims graph rather than a flat claim row. The report and proof of concept show how classification, inference, clustering, and time-series anomaly detection can help prioritize payment review while preserving privacy and keeping auditors in the loop.

## Repository Contents

- `Cotiviti_Prompt2_Report_Mohammad_Saleh_Nikoopayan_Tak.docx`
  - Two-page written report with a third-page bibliography.
- `Cotiviti_Prompt2_Presentation_Mohammad_Saleh_Nikoopayan_Tak.pptx`
  - PowerPoint overview of the report and proof of concept.
- `claim-integrity-radar-poc/`
  - Browser-based hackathon POC. No install step is required.
- `Cotiviti_Prompt2_Slide_Blueprint_Mohammad_Saleh_Nikoopayan_Tak.md`
  - Exact slide text and visual guidance for each slide.
- `Cotiviti_Prompt2_Recording_and_Submission_Runbook.md`
  - Suggested video structure, demo flow, and submission checklist.

## POC Demo

Live demo:

`https://mnikoopayan.github.io/cotiviti-prompt2-claim-integrity-radar/claim-integrity-radar-poc/`

Local demo:

Open:

`claim-integrity-radar-poc/index.html`

Recommended flow:

1. Click `Train Local Baselines`.
2. Click `Share Federated Summary`.
3. Select a high-risk claim from the review queue.
4. Explain the graph path and evidence chain.
5. Click `Export Audit Packet`.

## Strategic Thesis

Cotiviti can use privacy-preserving claim graphs to detect suspicious payment patterns earlier, explain each lead to auditors, and share cross-payer signal without sharing raw claims.

The key design principle is:

`No score without a story.`

## Video Note

The assessment also asks for a recorded MP4 presentation. The included runbook provides the exact suggested structure and POC demo flow for recording that video.
