## Fairness–Utility Trade-offs in Graph Learning {#fairness-utility}

A reproducible mini-study on **utility–fairness trade-offs** in graph learning (node classification + link prediction), with **scripted sweeps**, **JSON audit trails**, and **trade-off plots**.

**Highlights:** scripted sweep · JSON artifacts (config + metrics) · multi-objective trade-offs (Pareto-ready)
**Key takeaway:** Fairness improves early and largely plateaus around λ≈0.3, while utility drops faster beyond that point.


**Links:**  
- [Repo](https://github.com/LexAI-Fan/Fan-lex-ai_Fairness_Utility_GraphLearning)  
- [Release v1.0.0](https://github.com/LexAI-Fan/Fan-lex-ai_Fairness_Utility_GraphLearning/releases/tag/v1.0.0)  
- [Results summary](https://github.com/LexAI-Fan/Fan-lex-ai_Fairness_Utility_GraphLearning/blob/main/docs/results_summary.md)  
- [Decision memo](https://github.com/LexAI-Fan/Fan-lex-ai_Fairness_Utility_GraphLearning/blob/main/docs/decision_memo.md)
- [Pilot study results (N=6)](https://github.com/LexAI-Fan/Fan-lex-ai_Fairness_Utility_GraphLearning/blob/main/docs/pilot_hci_study.md)



**Reproduce (Windows PowerShell):**
- Run a full sweep: `.\scripts\run_sweep.ps1`
- Then generate figures: `python .\make_figures.py`

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
