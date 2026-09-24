# Álvaro González Méndez

**AI Engineer — LLMs, agents and evaluation.** Madrid, Spain.

Computer Engineer with an MSc in Artificial Intelligence from Universidad Politécnica de Madrid
(GPA 9.05/10). I build LLM-based systems (structured outputs, information retrieval and
multi-agent pipelines) and I care about evaluating them properly. Background in
applied research and in back-end development of hospital software running in
production, with a focus on clinical data (OMOP CDM).

🌐 [alvarogmendez.es](https://alvarogmendez.es) · 💼 [LinkedIn](https://www.linkedin.com/in/alvarogmendez/) · 📫 [alvarogmendez25@gmail.com](mailto:alvarogmendez25@gmail.com)

---

## Experience

**Researcher — SHIELD project (Horizon Europe)** · Biomedical Informatics Group (GIB), UPM · *Nov 2025 – Aug 2026*
- Designed and deployed an LLM pipeline (structured outputs with BAML) that translates clinical
  specifications into executable rules, keeping generation (no access to patient data) apart from
  deterministic execution inside each hospital. Adopted in 3 clinical trials (130+ rules).
- Implemented vocabulary mapping, PostgreSQL loads and testing (pytest and data-quality checks) for
  a multi-agent ETL (CrewAI) that migrated data from around 4,000 patients to OMOP CDM.
- Built a Flask/Python web service used by clinical researchers at 3 centres in Spain, Italy and
  Switzerland to run the validated rules on their own data.

**Back-end Developer, .NET (internship)** · Inetum Spain · *Feb 2024 – May 2024*
- ASP.NET MVC components and REST APIs for hospital software in production; SQL Server query
  optimisation and production monitoring with Dynatrace.

## Projects

| Project | What it is |
|---|---|
| **From clinical specifications to executable rules** · *MSc thesis (10/10)* | Compiler from natural-language clinical specifications to typed ASTs via structured prompting, with a deterministic executor over OMOP CDM. Retrieve-then-rerank concept mapping (MedEmbed + LLM reranker): 94.1 % accuracy@1 over 100 concepts. Benchmark of 11 LLMs across 6 dimensions. *Paper in preparation.* |
| [**biomedical_info_retrieval**](https://github.com/alvarogmendez/biomedical_info_retrieval) | Fine-tuned BERT, BioBERT and BiomedBERT to filter polyphenol literature: 2,371 abstracts, best F1 0.989 and ROC-AUC 0.9996 (BiomedBERT). |
| [**gml_nn**](https://github.com/alvarogmendez/gml_nn) · *BSc thesis (9.6/10)* | Multilayer-perceptron library written from scratch in C: backpropagation, 6 activation functions, SGD / mini-batch with momentum, model save/load. [Thesis](https://oa.upm.es/82476/) |
| [**magic_square_generator**](https://github.com/alvarogmendez/magic_square_generator) | Two-phase evolutionary algorithm with local rectification (Xie & Kang, 2003) that builds magic squares up to order 40. |
| [**JSPDL**](https://github.com/alvarogmendez/JSPDL) | Compiler front-end for a JavaScript subset in Python: DFA lexer, LL(1) parser, scoped symbol tables and type checking. |
| **alvarogmendez.es** | Static site served from a Raspberry Pi at home, with hardened containers, CI to GHCR and live homelab status. |

## Skills

- **LLMs & agents:** BAML (structured outputs), prompt engineering, RAG, CrewAI, LangGraph, LLM evaluation, Ollama; Gemini, Anthropic, OpenAI and DeepSeek APIs
- **ML & NLP:** PyTorch, Hugging Face, Keras, TensorFlow, genetic and memetic algorithms
- **Programming:** Python (Flask, FastAPI), C, C# / .NET, Java
- **Data & infrastructure:** PostgreSQL, SQL Server, OMOP CDM, GDPR in clinical data, Docker, Git, Linux · AWS Certified Cloud Practitioner

## Education

- **MSc in Artificial Intelligence** — Universidad Politécnica de Madrid, 2025–2026 · GPA 9.05/10 · thesis 10/10
- **BSc in Computer Engineering** — Universidad Politécnica de Madrid, 2019–2024 · thesis 9.6/10
- **Erasmus exchange, Computer Science** — Warsaw University of Technology, 2022–2023

Spanish (native) · English (C1)
