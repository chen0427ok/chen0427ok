# Hi there, I'm Chih-Hsi (Brian) Chen 👋

<div align="center">

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&pause=1000&color=29D130&center=true&vCenter=true&width=760&lines=Incoming+MS+ECE+%40+Carnegie+Mellon+University;Generative+AI+Engineering+Intern+%40+GIGABYTE;LLM+Agents+%7C+Long-Term+Memory+%7C+Speech+Processing;Open+Source+Contributor" alt="Typing SVG" />
</a>

</div>

---

I work on **long-term memory for LLM agents**, **agentic retrieval and evaluation**, and **speech-language modeling** — and I care as much about the engineering around a result as the result itself.

I hold a **B.S. in Computer Science and Information Engineering from National Cheng Kung University** (GPA 4.15 / 4.30, conferred January 2026), and I am an **incoming M.S. in Electrical and Computer Engineering at Carnegie Mellon University** starting January 2027. Right now I am a **Generative AI Engineering Intern on GIGABYTE's LLM Algorithm Team**.

---

## 🚀 Highlights

- 🏅 **AKBC 2026 Featured Paper** — GRACE-Mem was selected as one of three featured papers at the EMNLP 2026 AKBC workshop and named a **Best Paper Award candidate**.
- 📄 **First author on two ROCLING papers** — a published Hakka ASR system (ROCLING 2025) and an accepted valence–arousal shared-task system (ROCLING 2026).
- 🔧 **Function calling that actually orders tools right** — raised ordered tool-sequence exact-match accuracy from **64.0% → 88.3%** on a 300-query benchmark at Phison, and shipped 9 MCP servers to an internal pilot of ~200 R&D users.
- 🎖️ **Open source** — merged PRs into [Apache Airflow](https://github.com/apache/airflow/pull/59374) (Playwright E2E tests for the DAGs list) and [Kinto](https://github.com/Kinto/kinto/pull/3636) (fixed a 500-level server crash on invalid POST data).
- 🏆 **Hackathon champion** — 1st of 150 teams at the Hsinchu × Meichu Hackathon (NXP group) with an IoT smart-agriculture system.

---

## 📄 Publications

| Paper | Venue | Role | Status |
|---|---|---|---|
| [GRACE-Mem: Graph Retrieval with Agentic Curation of Evidence for Long-Term Conversational Memory](https://openreview.net/forum?id=fFVQIuZ6qM) | EMNLP 2026 Workshop on Automated Knowledge Base Construction (AKBC) | 4th author | **Accepted** · Featured Paper · Best Paper candidate |
| [The SLAM Hakka ASR System for Formosa Speech Recognition Challenge 2025](https://aclanthology.org/anthology-files/pdf/rocling/2025.rocling-main.61.pdf) | ROCLING 2025, pp. 504–511 | **First author** | Published |
| NCKU_NLP at ROCLING-2026 Shared Task: Source-Aware Lexicon-Augmented Regression for Valence–Arousal Prediction | ROCLING 2026 DSA-NIFT shared task | **First author** | Accepted |

**GRACE-Mem** — I ran every experiment and benchmark evaluation reported in the paper, built the evaluation pipeline and ablation study, implemented graph ingestion and retrieval reranking, and designed the Grep / Read / Vector / Final agent operations and their prompts. With GPT-4o-mini the system reaches **85.3% on LoCoMo** and **73.2% on LongMemEval-S**, exceeding previously reported AMA results by 7.9 and 3.4 percentage points. Code: [gbtailab-tech/GRACE-Mem](https://github.com/gbtailab-tech/GRACE-Mem).

**Hakka ASR** — A data-centric Whisper-large-v3 system for the low-resource Dapu and Zhaoan Hakka varieties. I collected 27 hours of real broadcast and e-learning speech, trained per-dialect VITS models to synthesize 343 hours of Hakka speech, and took 6th place (15.73% CER, Hanzi) and 4th place (20.68% WER, Pinyin) in the FSR 2025 final tracks.

**ROCLING 2026 DSA-NIFT** — Continuous valence–arousal regression on Chinese new-immigrant reflection texts with no labeled target-domain data, using a MacBERT encoder, a 31-dimensional affective-lexicon feature vector, and source-aware arousal supervision. Placed **4th among 7 participating teams** (valence MAE 0.620 / PCC 0.866).

---

## 💼 Experience

| Role | Organization | Period |
|------|--------------|--------|
| 🧪 Generative AI Engineering Intern | **GIGABYTE Technology** — LLM Algorithm Team | Jun 2026 – Dec 2026 |
| 🔬 Research Assistant | **Academia Sinica**, Institute of Information Science | Jul 2025 – Feb 2026 |
| 🤖 ML Algorithm Engineer Intern | **Phison Electronics** — LLM Application Group | Oct 2024 – Jun 2025 |
| 🎓 Research Assistant | **NCKU AI Lab** | Sep 2023 – Jan 2026 |

- **GIGABYTE** — Building GRACE-Mem, an agentic long-term conversational-memory system over retrieval and knowledge-graph components. Also refactored the research codebase along Domain-Driven Design lines and tightened CI with Ruff, mypy, and Pytest.
- **Academia Sinica** (advisor: Prof. Hsin-Min Wang) — Low-resource Hakka ASR, speech-encoder fusion on AIShell-1, and Speech-LLM modality adapters connecting speech encoders to a 2B Chinese LLM (best config: 5.01% CER). Deployed a Hakka speech-generation service used by ~5–20 researchers across 2–5 collaborating labs.
- **Phison Electronics** — Co-developed a LoRA + ChatML fine-tuning workflow for Qwen2.5-72B-Instruct function calling on the aiDAPTIV+ platform (4 × H100). Personally implemented 9 MCP servers, two dispatcher paths, the `call_first` decision token, the benchmark harness, and an end-to-end TableRAG system for a major retail client.
- **NCKU AI Lab** (advisor: Prof. Shu-Han Hsu) — First-authored an unpublished manuscript on structured pruning for PatchCore anomaly detection, comparing five pruning criteria across five ratios on MVTec AD and sustaining pruning ratios up to 70% with limited image-level degradation.

---

## 🛠️ Tech Stack

<div align="center">

### Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)

### AI & GenAI
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![PEFT / LoRA](https://img.shields.io/badge/PEFT%20%2F%20LoRA-FF9E0F?style=for-the-badge&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LlamaIndex](https://img.shields.io/badge/LlamaIndex-5A3E85?style=for-the-badge&logoColor=white)
![vLLM](https://img.shields.io/badge/vLLM-000000?style=for-the-badge&logoColor=white)
![WandB](https://img.shields.io/badge/W%26B-FFBE00?style=for-the-badge&logo=weightsandbiases&logoColor=black)

### LLM Systems & Retrieval
![MCP](https://img.shields.io/badge/MCP-1F1F1F?style=for-the-badge&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-4B8BBE?style=for-the-badge&logoColor=white)
![Knowledge Graphs](https://img.shields.io/badge/Knowledge%20Graphs-2E8B57?style=for-the-badge&logoColor=white)
![LLM-as-a-Judge](https://img.shields.io/badge/LLM--as--a--Judge-7952B3?style=for-the-badge&logoColor=white)
![NeMo Guardrails](https://img.shields.io/badge/NeMo%20Guardrails-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![Dify](https://img.shields.io/badge/Dify-1C64F2?style=for-the-badge&logoColor=white)

### Speech & Audio
![OpenAI Whisper](https://img.shields.io/badge/Whisper-412991?style=for-the-badge&logo=openai&logoColor=white)
![WavLM](https://img.shields.io/badge/WavLM-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![HuBERT](https://img.shields.io/badge/HuBERT-0866FF?style=for-the-badge&logo=meta&logoColor=white)
![VITS](https://img.shields.io/badge/VITS-8E44AD?style=for-the-badge&logoColor=white)
![Librosa](https://img.shields.io/badge/Librosa-FF6F61?style=for-the-badge&logoColor=white)
![Kaldi](https://img.shields.io/badge/Kaldi-2C3E50?style=for-the-badge&logoColor=white)

### Deployment & MLOps
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![MinIO](https://img.shields.io/badge/MinIO-C72E49?style=for-the-badge&logo=minio&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![InfluxDB](https://img.shields.io/badge/InfluxDB-22ADF6?style=for-the-badge&logo=influxdb&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=for-the-badge&logo=onnx&logoColor=white)
![OpenVINO](https://img.shields.io/badge/OpenVINO-00C7FD?style=for-the-badge&logo=intel&logoColor=black)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

### Testing & Web
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-45ba4b?style=for-the-badge&logo=playwright&logoColor=white)
![Ruff](https://img.shields.io/badge/Ruff-D7FF64?style=for-the-badge&logo=ruff&logoColor=black)
![mypy](https://img.shields.io/badge/mypy-2A6DB2?style=for-the-badge&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

</div>

---

## 🔬 Other Things I've Been Measuring

- **Translation model evaluation** — Found that the official TranslateGemma template collapses Chinese locale codes into one "Chinese" label, emitting Simplified Chinese in 66.8% of Traditional-Chinese requests. Naming the language explicitly pushed Traditional-Chinese output to 98.0% and gained +6.22 chrF++ / +10.62 BLEU.
- **ASR encoder fusion** — Compared Whisper, WavLM, DistilHuBERT, and Chinese HuBERT encoders and several fusion architectures on AIShell-1; fusion design and decoder initialization mattered more than simply adding another encoder.

---

## 📊 GitHub Stats

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats-eight-theta.vercel.app/api?username=chen0427ok&show_icons=true&theme=radical&hide_border=true&count_private=true&include_all_commits=true" />
    <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats-eight-theta.vercel.app/api?username=chen0427ok&show_icons=true&theme=default&hide_border=true&count_private=true&include_all_commits=true" />
    <img src="https://github-readme-stats-eight-theta.vercel.app/api?username=chen0427ok&show_icons=true&theme=radical&hide_border=true&count_private=true&include_all_commits=true" alt="Brian's GitHub Stats" height="180"/>
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=chen0427ok&layout=compact&theme=radical&hide_border=true&langs_count=8" />
    <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=chen0427ok&layout=compact&theme=default&hide_border=true&langs_count=8" />
    <img src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=chen0427ok&layout=compact&theme=radical&hide_border=true&langs_count=8" alt="Top Languages" height="180"/>
  </picture>
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com/?user=chen0427ok&theme=radical&hide_border=true" alt="GitHub Streak" />
</div>

---

## 🐍 Contribution Snake

<div align="center">
  <img src="https://raw.githubusercontent.com/chen0427ok/chen0427ok/output/github-contribution-grid-snake-dark.svg" alt="Snake animation" />
</div>

---

## 📫 Reach Me

<div align="center">

<a href="mailto:chenbrian930427@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://www.linkedin.com/in/chih-hsi-chen-356b9a2ba/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>

<br /><br />

<img src="https://komarev.com/ghpvc/?username=chen0427ok&color=blueviolet&style=flat-square" alt="Profile Views" />

</div>
