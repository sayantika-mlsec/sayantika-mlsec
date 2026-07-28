# Hi there, I'm Sayantika 👋
# AI Engineer
**Evaluation & Reliability for LLM Systems**

I build LLM systems and the evaluation harnesses that tell me whether they're actually working — retrieval, agent design, and measurement I can defend. My background is anomaly detection and network security, where the hard problem was never detection. It was getting anyone to believe the alerts.

### What I've built

- **[NIDS](https://github.com/sayantika-mlsec/network-intrusion-detection-system-project.git)** — Catches network intrusions in CICIDS2017 traffic. XGBoost + SHAP, tuned so it doesn't cry wolf, with Evidently AI watching for data drift.
- **[UEBA](https://github.com/sayantika-mlsec/insider-threat-detection-project.git)** — Spots the insider who's behaving *almost* normally. Isolation Forest + anomaly scoring on the CERT dataset.
- **[Tiered Threat Intel Assistant](https://github.com/sayantika-mlsec/RAG-Powered-Threat-Intelligence-Assistant.git)** — A RAG system that answers security questions by actually reading MITRE ATT&CK and CISA KEV, not guessing.

  
### Right now

Building an agent that reads an unfamiliar repository and generates grounded questions about it — tree-sitter navigation, a bounded tool loop, and a deterministic citation verifier with no LLM in that layer. Held-out repos pinned before any code existed, scored exactly twice. Evaluated by ablation rather than by adding features until the demo looks good.
 
### Recently

Built a tiered RAG threat-intelligence assistant over MITRE ATT&CK and CISA KEV — a structured-output router that picks the corpus (or skips retrieval entirely) before the pipeline runs, with model-tier routing for cost and latency. Evaluated the routed pipeline against a blind-retrieval baseline, and built a correctness-against-gold metric after finding that faithfulness scoring rewards a model for refusing to answer. Limitations documented with status labels rather than quietly fixed.
 
### Stack
 
 Python · XGBoost · scikit-learn · LangChain · FastAPI · Docker · MLflow · Evidently AI
 
### Find me
 * **LinkedIn:** https://www.linkedin.com/in/sayantika1379 
 * **X:** https://x.com/sayantika1379
 
