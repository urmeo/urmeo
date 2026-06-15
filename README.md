<h1 align="center">Urme</h1>

<h3 align="center">Software Engineer · Trustworthy ML for Human-Centered AI</h3>

<p align="center"><i>Measuring stress, anxiety, and emotion from the body and from language — and proving where the models work, and where they break.</i></p>

<h3 align="left">Languages</h3>
<p align="left">
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" height="48" width="48" />
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" height="48" width="48" />
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="typescript" height="48" width="48" />
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg" alt="html5" height="48" width="48" />
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg" alt="css3" height="48" width="48" />
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg" alt="postgresql" height="48" width="48" />
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/sqlite/sqlite-original.svg" alt="sqlite" height="48" width="48" />
</p>

<h3 align="left">Machine Learning &amp; Data</h3>
<p align="left">
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pytorch/pytorch-original.svg" alt="pytorch" height="48" width="48" />
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/tensorflow/tensorflow-original.svg" alt="tensorflow" height="48" width="48" />
<img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="scikit-learn" height="48" width="90" />
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pandas/pandas-original.svg" alt="pandas" height="48" width="48" />
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/numpy/numpy-original.svg" alt="numpy" height="48" width="48" />
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/matplotlib/matplotlib-original.svg" alt="matplotlib" height="48" width="48" />
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/jupyter/jupyter-original-wordmark.svg" alt="jupyter" height="48" width="90" />
</p>

<h3 align="left">Generative AI &amp; NLP</h3>
<p align="left">
<img src="https://huggingface.co/datasets/huggingface/brand-assets/resolve/main/hf-logo.png" alt="hugging face" height="48" width="48" />
<img src="https://github.com/ollama.png" alt="ollama" height="48" width="48" />
<img src="https://github.com/lancedb.png" alt="lancedb" height="48" width="48" />
</p>

<h3 align="left">Systems &amp; MLOps</h3>
<p align="left">
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/fastapi/fastapi-original.svg" alt="fastapi" height="48" width="48" />
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/flask/flask-original.svg" alt="flask" height="48" width="48" />
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/django/django-plain.svg" alt="django" height="48" width="48" />
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original.svg" alt="nodejs" height="48" width="48" />
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" alt="docker" height="48" width="48" />
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/githubactions/githubactions-original.svg" alt="github actions" height="48" width="48" />
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pytest/pytest-original.svg" alt="pytest" height="48" width="48" />
</p>

# Projects

## Affective Computing &amp; Physiological ML
| Project | What it does | Stack |
|---|---|---|
| [**CalmSense**](https://github.com/urme-b/CalmSense) | Honest, reproducible stress-detection benchmark on WESAD, evaluated leave-one-subject-out — best model **0.913 acc / 0.898 F1**, with SHAP explanations and a cross-dataset failure analysis | scikit-learn · XGBoost/LightGBM · 1D-CNN (PyTorch) · SHAP · FastAPI · Docker |
| [**Multimodal-Multisensor**](https://github.com/urme-b/Multimodal-Multisensor) | Longitudinal within-subjects anxiety study (10 adults, 3 weekly sessions) pairing psychometrics with synced eye-tracking, cardiac/HRV, EDA, and facial-action data | pandas · NumPy · SciPy · PCA/K-Means · OpenFace · Pupil Labs |
| [**Sensor**](https://github.com/urme-b/Sensor) | A field guide to the 10 sensors and 2 platforms behind the anxiety-detection research — eye tracking, HRV, skin conductance, video, motion capture | Jupyter · biometric sensors |
| [**Psychometric**](https://github.com/urme-b/Psychometric) | Psychometric test suite (HADS, STAI-S/T, BFI, FQ) with CSV export and PDF report generation | Django · JavaScript · jQuery |

## Generative AI, NLP &amp; Applied
| Project | What it does | Stack |
|---|---|---|
| [**NovaVision**](https://github.com/urme-b/NovaVision) | Emotion-conditioned image generation with a CLIP recovery benchmark that measures whether the intended affect survives the pipeline | DistilRoBERTa · Stable Diffusion Turbo · CLIP · Diffusers |
| [**NexusRAG**](https://github.com/urme-b/NexusRAG) | Self-correcting RAG for science — hybrid retrieval + DeBERTa NLI faithfulness check; **nDCG@10 0.685** (p = 0.031), 266 tests, fully local | Sentence-Transformers · BM25 · DeBERTa-NLI · LanceDB · Ollama |
| [**PulseShift**](https://github.com/urme-b/PulseShift) | Decision support for outdoor activity under climate stress — ranks safer adaptations from NOAA forecasts and EPA AirNow AQI | Python · Node.js · PostgreSQL · SQLite |
| [**Antenna**](https://github.com/urme-b/Antenna) | Comparative study of five microstrip patch antenna geometries at 2.45 GHz — CST Studio simulation, FR-4 fabrication, VNA measurement | CST Studio · RF engineering |

---

<p align="center"><i>I'd rather report a confidence interval than a headline number — every project here ships with its own paper, citation metadata, and test suite, so the results can be checked, not just believed.</i></p>
