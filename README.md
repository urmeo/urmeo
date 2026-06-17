<p align="center">
  <b>Urme Bose</b><br>
  <sub>Software Engineer · Trustworthy ML for Human-Centered AI</sub>
</p>

<p align="center">
  <a href="https://urme-b.github.io/portfolio"><img src="https://img.shields.io/badge/Portfolio-1a1b27?style=flat-square&logo=github&logoColor=7aa2f7" alt="Portfolio"></a>
  <a href="mailto:urme.emma@gmail.com"><img src="https://img.shields.io/badge/Email-1a1b27?style=flat-square&logo=gmail&logoColor=7aa2f7" alt="Email"></a>
</p>

> **Most ML portfolios show you the best number and ask you to trust it. Mine shows you the protocol and the data, then reports whatever the result actually was — including the nulls.**
>
> I'd rather report a confidence interval than a headline number — results can be checked, not just believed.

---

## Featured work

Each project headlines its honest result and ships the means to check it.

| Project | The honest result, and how to verify it |
| --- | --- |
| **[NexusRAG](https://github.com/urme-b/NexusRAG)**<br><sub>local-first, self-correcting RAG for scientific papers</sub> | Hybrid retrieval (BM25 + BGE dense + RRF fusion) with an NLI sentence-level faithfulness verifier. Reported plainly: **the verifier only narrowly beats a lexical baseline.** Every BEIR number in the paper auto-generates from committed JSON.<br><sub>Sentence-Transformers · DeBERTa-NLI · LanceDB · Ollama · FastAPI</sub> |
| **[CalmSense](https://github.com/urme-b/CalmSense)**<br><sub>subject-independent wearable stress detection</sub> | An anti-inflation benchmark for a field that reports 95–99% accuracy. Under leak-free Leave-One-Subject-Out CV it lands **~0.91 binary / 0.67 three-class** — plus calibration, few-shot personalization, and an ONNX in-browser demo.<br><sub>scikit-learn · XGBoost/LightGBM · 1D-CNN (PyTorch) · SHAP · ONNX</sub> |
| **[PulseShift](https://github.com/urme-b/PulseShift)**<br><sub>observational-causal study: does air quality suppress activity?</sub> | DC bike-share as a mobility proxy. The apparent effect is mostly seasonal confounding — it shrinks from **−10.9 to −2.4 ride-pts per +50 AQI** under within-day fixed effects. The dependency-free [in-browser forecaster](https://urme-b.github.io/PulseShift) matches a fresh fit to 1e-6.<br><sub>Python · scikit-learn · pandas · vanilla-JS in-browser model</sub> |
| **[NovaVision](https://github.com/urme-b/NovaVision)**<br><sub>emotion-conditioned text-to-image generation</sub> | An automatic benchmark for emotional controllability. The headline is the honest result: an **n=14 null (p=0.255)** from a small CPU pilot — committed and reported, not buried.<br><sub>DistilRoBERTa · Stable Diffusion Turbo · CLIP · Diffusers</sub> |

---

## Skills

**ML** — scikit-learn · PyTorch · XGBoost/LightGBM · SHAP<br>
**NLP & GenAI** — Transformers · Diffusers · Sentence-Transformers · CLIP · RAG · LanceDB · Ollama<br>
**Data & Stats** — pandas · NumPy · SciPy · causal inference · calibration · LOSO/nested CV<br>
**MLOps** — FastAPI · Docker · GitHub Actions · ONNX · pytest

<details>
<summary><b>Also in the repos</b></summary>

<br>

- **[Multimodal-Multisensor](https://github.com/urme-b/Multimodal-Multisensor)** — longitudinal n=10 psychometrics + multimodal biometrics (HRV, eye-tracking, GSR); honestly reports weak/underpowered trait stability (ICC 0.22–0.61).
- **[Sensor](https://github.com/urme-b/Sensor)** — comparative review of 10 biometric sensors + 2 facial-analysis platforms for anxiety detection, with sample data and a data dictionary.
- **[Psychometric](https://github.com/urme-b/Psychometric)** — bilingual EN/FR, fully offline, privacy-first psychometric test suite (HADS, STAI-S/T, BFI-10, Fear Questionnaire) with automated scoring and CSV/PDF export.
- **[Antenna](https://github.com/urme-b/Antenna)** — 2018 RF hardware: five 2.45 GHz microstrip patch-antenna geometries, CST-simulated, FR-4 fabricated, VNA-measured.

</details>

---

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=urme-b&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&theme=tokyonight" alt="GitHub stats">
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=urme-b&layout=compact&hide_border=true&langs_count=8&theme=tokyonight" alt="Top languages">
</p>

<p align="center">
  <img height="165" src="https://streak-stats.demolab.com/?user=urme-b&hide_border=true&theme=tokyonight" alt="GitHub streak">
</p>

---

<p align="center">
  <a href="https://urme-b.github.io/portfolio"><b>Portfolio</b></a> · <a href="mailto:urme.emma@gmail.com"><b>urme.emma@gmail.com</b></a>
</p>
