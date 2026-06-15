# Urme Bose

**Software engineer building trustworthy ML for human-centered AI** — systems that measure stress, anxiety, and emotion from the body and from language, and prove they work — including where they break.

---

I work in **affective computing**: turning noisy physiological and linguistic signals into inference you can act on. The instruments vary — wearable biosignals, eye tracking, cardiac variability, text — but the discipline is constant: model it rigorously, explain it, and benchmark it honestly.

### What I build

- **Multimodal physiological modeling** — stress and anxiety from ECG, EDA, HRV, pupillometry, and facial action units
- **Trustworthy ML** — explainability (SHAP) and faithfulness verification (NLI-grounded retrieval) over black-box accuracy
- **Research-grade systems** — typed, tested, containerized, and shipped with papers and reproducible benchmarks

### Projects

**[CalmSense](https://github.com/urme-b/CalmSense)** — An honest, reproducible stress-detection benchmark on WESAD, evaluated leave-one-subject-out so the numbers survive contact with unseen people.
Best model (Random Forest) reaches **0.913 accuracy / 0.898 F1** across 15 subjects on 58 physiological features; SHAP explanations and a live in-browser demo ship with it — alongside a cross-dataset evaluation that documents where accuracy collapses toward chance on unseen distributions.
`scikit-learn` · `XGBoost / LightGBM` · `1D-CNN (PyTorch)` · `SHAP` · `FastAPI` · `Docker`
