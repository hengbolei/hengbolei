### Hi, I'm Hengbo Lei 👋

I'm a Master of Computing (Applied AI) student at **Nanyang Technological University, Singapore**.
My background is in data science, spanning machine learning engineering and applied research on
AI agents. I'm interested in getting AI out of notebooks and into real applications, with
evidence that it works: reproducible pipelines, honest evaluation and results that can be
traced back to their sources.

### Research interests

- **Verifiable LLM agents**: grounding agent outputs in cited evidence, deterministic checks and
  human review, especially in high-stakes domains such as healthcare
- **Evaluation methodology**: benchmarks against strong baselines, temporal (out-of-time)
  validation, leakage control, calibration and drift
- **Machine learning for scientific data**: feature engineering for time series such as
  astronomical light curves, with interpretability and ablation analysis

### Selected projects

**Research and evaluation**

- [**fractional-tde-classification**](https://github.com/hengbolei/fractional-tde-classification)
  · *undergraduate thesis*: classifies tidal disruption events in simulated LSST light curves
  (MALLORN data, 3,043 objects, 148 TDEs) using FFT-based fractional-order derivative features.
  Fused features with LightGBM reach AUC 0.885, with ablations over the derivative order and
  photometric band, statistical tests, SHAP analysis and a documented reproduction.
- [**VizJudge**](https://github.com/hengbolei/VizJudge): ranks candidate charts by
  cross-validated incremental gain and turns the evidence into ML actions. A
  [downstream-model benchmark](https://github.com/hengbolei/VizJudge/blob/main/docs/benchmark.md)
  on 10 public datasets compares it with mutual information, AutoViz, dabl, ppscore and random
  selection, and reports where it falls short. Also usable as an MCP server for LLM agents.
- [**uk-road-collision-severity-prediction**](https://github.com/hengbolei/uk-road-collision-severity-prediction):
  out-of-time prediction of serious road collisions from 513,801 UK Department for Transport
  records (2021–2025), comparing five classifiers with calibration, temporal drift and
  permutation-importance analysis.

**Applied agent systems**

- [**provenance-care-note**](https://github.com/hengbolei/provenance-care-note): a clinical
  review agent that drafts patient summaries in which every claim cites an exact span of the
  record and passes deterministic verification before a clinician reviews it. Includes PHI
  redaction, prompt-injection defences, run budgets, and a 39-case synthetic evaluation suite
  replayed in CI for two models. Synthetic data only.

### Toolbox

- **Languages:** Python · SQL · JavaScript
- **ML & data:** scikit-learn · LightGBM · XGBoost · CatBoost · pandas · SHAP
- **Agents & LLMs:** MCP · tool-using agents · structured outputs · LLM evaluation
- **Engineering:** FastAPI · PostgreSQL · OpenTelemetry · pytest · GitHub Actions · uv
