---
layout: page
title: Projects
permalink: /projects/
---
## Fairness–Utility Trade-offs in Graph Learning {#fairness-utility}

A reproducible mini-study on **utility–fairness trade-offs** in graph learning (node classification + link prediction), with **scripted sweeps**, **JSON audit trails**, and **trade-off plots**.

**Highlights:** scripted sweep · JSON artifacts (config+metrics) · multi-objective trade-offs (Pareto-ready)

**Links:**  
- Repo: https://github.com/LexAI-Fan/<Fan-lex-ai_Fairness_Utility_GraphLearning>  
- Release v1.0.0: https://github.com/LexAI-Fan/<YOUR_REPO_NAME>/releases/tag/v1.0.0  
- Results summary: https://github.com/LexAI-Fan/<YOUR_REPO_NAME>/blob/main/docs/results_summary.md

<div style="display:flex; gap:16px; flex-wrap:wrap; margin-top:12px;">
  <div style="flex:1; min-width:280px;">
    <img src="/images/projects/fairness-utility/fig_node_tradeoff.png" alt="Node classification trade-off" style="width:100%; border-radius:10px; box-shadow:0 4px 14px rgba(0,0,0,.08);" />
    <div style="font-size:14px; opacity:.85; margin-top:6px;">Node classification: utility vs fairness</div>
  </div>
  <div style="flex:1; min-width:280px;">
    <img src="/images/projects/fairness-utility/fig_link_tradeoff.png" alt="Link prediction trade-off" style="width:100%; border-radius:10px; box-shadow:0 4px 14px rgba(0,0,0,.08);" />
    <div style="font-size:14px; opacity:.85; margin-top:6px;">Link prediction: utility vs fairness</div>
  </div>
</div>


A selection of works-in-progress and code I can share publicly. Repos will appear here as I open-source them.

## 1) PHAWM — Participatory Harm Auditing Workbench & Methodologies
What: A lightweight workflow to translate community-reported issues into testable hypotheses, datasets, and governance-ready evidence packs.  
Why: Many fairness audits die in PDF tombs. PHAWM aims for actionable evidence with uncertainty, coverage, and residual risk clearly stated.  
Status: Spec + templates + starter notebooks.  
Links: Repo (soon): `https://github.com/LexAI-Fan/phawm` · Demo notebooks (coming)

## 2) Legal Knowledge Graph from Court Decisions
What: Pipeline to parse judgments and link entities (parties, issues, statutes), producing a graph for doctrine evolution and liability allocation studies.  
Stack: Python, spaCy/transformers, graph tooling.  
Deliverables: ETL notebooks, schema, sample analyses (e.g., liability proportions by fact patterns).  
Repo: `https://github.com/LexAI-Fan/legal-kg-courts` (placeholder)

## 3) Governance-Ready Safety Cards
What: A templated “Safety Card” that reports what is guaranteed, at what thresholds, and with what residual risk, including risk-coverage plots and selective abstention rules.  
Use: For internal reviews and regulator-facing documentation.  
Repo: `https://github.com/LexAI-Fan/safety-cards` (placeholder)

## 4) LexFair — Fairness & Calibration Baselines
What: Reproducible baselines for calibration, ECE/NLL, risk-coverage AUC, and intersectional group metrics under dataset shift.  
Why: Audits fail without solid baselines and honest uncertainty.  
Repo: `https://github.com/LexAI-Fan/lexfair-baselines` (placeholder)

## 5) AI-for-Law Enforcement: Predictive Systems Critique Kit
What: A critical-evaluation toolkit for policing/prediction systems: dataset shift checks, harm scenarios, and abstain/route thresholds.  
Status: Proposal + prototypes; seeking collaborators for public datasets.  
Repo: `https://github.com/LexAI-Fan/policing-eval-kit` (placeholder)

## 6) Personal Site & Notes
This website (Jekyll/Minima).  
Repo: `https://github.com/LexAI-Fan/LexAI-Fan.github.io`
