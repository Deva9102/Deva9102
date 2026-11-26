<h1 align="center">Hi 👋, I'm Devadarshini Pazhanivel Thenmozhi</h1>
<h3 align="center">
AI & Machine Learning Engineer | MS AI @ Northeastern University | Agentic AI, LLM Systems & Applied ML
</h3>

<p align="center">
  <img src="https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExdGhvdjVyZ2VrNWU3ZjVpbzZ6MTFwazdjcjBzOG9oazk5MHNsM3U5bSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/L1R1tvI9svkIWwpVYr/giphy.gif" alt="coding-gif" width="420"/>
</p>

---

## 👩‍💻 About Me

I’m a **graduate AI student at Northeastern University** with hands-on experience building **end-to-end, production-grade AI systems** across agentic AI, large language models, NLP, and machine learning.

I enjoy working at the intersection of **data, models, and systems** — taking ideas from experimentation to deployment with a strong focus on **reliability, evaluation, and real-world impact**.

- 🎓 MS in Artificial Intelligence — Northeastern University  
- 🔬 Research Assistant — **Gyori Lab for Computational Biomedicine**  
- 🏆 **2nd Place – Boston 311 AI System**, Google Cambridge  
- 📄 Co-author of an **IEEE research paper** on ML-based anomaly detection  
- 🔍 Interested in **agentic AI, LLM evaluation, ML systems, and data-driven decision systems**

📫 Reach me at: **pazhanivelthenmozh.d@northeastern.edu**  
🌐 Portfolio: [https://devadarshinipazhanivelthenmozhi.netlify.app](https://devadarshinipazhanivelthenmozhi.netlify.app)

---

## 💼 Experience

### 🔬 Research Assistant – AI and Data Systems · Gyori Lab, Northeastern University
*Jun 2026 – Present*

I build a production **PU-learning** classification pipeline for biomedical literature triage, implementing the Spy technique and bagging-based PU learning from the research literature. Through a controlled ablation study across embedding models, 9 classifier architectures and PU algorithms, I improved balanced accuracy from **69.6% → 88.5%** on curated data and **78% → 82%** on real-world data, and validated the approach across **6 independent public benchmarks**. I also integrated 9 document-parsing backends (OCR, vision-language models, cloud APIs) into an OpenAI-powered LLM extraction pipeline, identifying an extractor **14% more accurate** with no GPU dependency.

### 🤖 Artificial Intelligence Intern · ProjectPathAI
*Jan 2026 – May 2026*

I built a multi-stage **Corrective RAG** pipeline in LangGraph that improved answer relevance by **20%** over baseline RAG, backed by hybrid search (BM25, dense retrieval and reranking) and semantic caching to reduce latency. I also productionized a behavioral inference model with drift detection, bias analysis and threshold calibration to keep it reliable as user inputs changed.


---

## 🚀 Featured Projects

### ⚡ US Grid Outage Analytics
🔗 **Repo:** https://github.com/Deva9102/us-grid-outage-analytics  
**Tech:** SQL, Python, Databricks, dbt, DuckDB, Power BI, GitHub Actions  

- Built an end-to-end analytics pipeline turning **~100M messy federal outage readings** (4 public sources, 2022–2025) into **602K storm-attributed outage events** and reliability rankings for every US county, state, and major utility.  
- Identified and resolved **70+ data-quality issues**, each documented with evidence and impact, and protected the pipeline with **120+ automated quality checks** and **115+ tests** in CI.  
- Found that hurricane outages last a **median 77 hours vs. 28** for thunderstorms, informing where utilities should stage repair crews.  
- Built with **Claude Code**, using structured prompt templates and guardrails, reviewing and testing every AI-generated change.

---

### 🏥 PolicyLens: Evidence-Grounded LLM Decision Support
🔗 **Repo:** https://github.com/OneTrickBreach/Policy-Lens-Project  
**Tech:** Python, BGE-M3, Nemotron, Gemma, scikit-learn  

- Team capstone: an LLM pipeline that retrieves chart evidence for **Medicare prior authorization** (LCD L34220), citing the exact supporting sentence for each of 10 criteria and routing uncertain cases to a nurse — never auto-denying.  
- Built an evaluation framework with 600 synthetic patients, planted failure modes, blind gold labels (Cohen's kappa), and Wilson confidence intervals.  
- A fine-tuned verifier cut disagreement from **43.8% → 7.9%**; a label audit caught a **17%** error rate hidden behind a passing headline check.

---

### 🤖 Multi-Agent Metabolic Interpretation System
🔗 **Repo:** https://github.com/Deva9102/Multi-Agent-Metabolic-Interpretation-System  
**Tech:** Python, LangGraph, MCP, LLM Agents  

- Multi-agent system that interprets continuous glucose monitor data: a Router agent fans out to specialist agents (glucose, meal, bloodwork, gut health), with an **MCP server** exposing tools, resources, and prompts.  
- Red-teamed a guardrail combining deterministic rules with an **LLM-as-judge** Critic, cutting data misattributions from **14% → 1.37%**.

---

### 🏙️ End-to-End Boston 311 AI System (Dashboard & Chatbot)
🔗 **Repo:** https://github.com/sharonjennifer/boston-311-ai-system  
**Tech:** BigQuery, SQL, LightGBM, Airflow, FastAPI, QLoRA, RAG, FAISS, Docker, Cloud Run  

- Built an **AI-powered conversational interface** for natural-language access to Boston’s 311 data using a fine-tuned **SQLCoder (QLoRA)** model.  
- Engineered **ETL pipelines** with Airflow and BigQuery to create analytics-ready gold tables powering a **priority-scoring dashboard**.  
- Implemented **predicted priority scores**, SLA tracking, and neighborhood-level equity analysis.  
- Deployed the system on **Cloud Run** with CI/CD and monitoring hooks.

---

### 🧠 NL2SQL using Retrieval-Augmented T5
🔗 **Repo:** https://colab.research.google.com/drive/19TwRrhN5DkwhiiSiHfrVtIaWTjq_166a  
**Tech:** PyTorch, Hugging Face, LangChain, T5, FAISS  

- Optimized a **T5-base** model for natural language → SQL translation on the Spider dataset, achieving **54.96% execution accuracy**.  
- Built a **retrieval-augmented pipeline** to improve schema grounding and reduce hallucinations on structured datasets.

---

### 💼 Candidate Recommendation Engine
🔗 **Repo:** https://github.com/Deva9102/candidate_recommendation_engine  
**Tech:** Python, NLP, Sentence Transformers, Qwen2.5 (4-bit, llama.cpp), Streamlit, scikit-learn  

- Developed an AI-driven resume ranking system using **feature extraction, similarity scoring, and transformer-based embeddings**.  
- Ran a locally-hosted **4-bit quantized LLM** with KV-cache decoding to explain each match in about **1.1 seconds**, with hallucination guardrails.  
- Enabled transparent candidate–JD matching with interpretable scores and an interactive analytics interface.

---

### 🩺 Fetal Health Risk Prediction & Patient Clustering
🔗 **Repo:** https://github.com/Deva9102/Fetal-Health-Prediction-and-Clustering  
**Tech:** Random Forest, XGBoost, PCA, UMAP, SHAP  

- Analyzed **2,126 CTG records** and built ML models to predict fetal health risk.  
- Applied dimensionality reduction and clustering to generate **clinically interpretable patient groups**.

---

### ⚽ AI-Powered Sports Video Highlight Generation
🔗 **Repo:** https://github.com/aatmaj28/Soccer-Highlight-Generation  
**Tech:** ResNet50, GRU, Attention, Computer Vision  

- Developed a deep learning system to automatically identify and rank key moments from full-length soccer matches.  
- Implemented temporal segmentation and stitching logic to generate personalized highlight reels.

---

## 🛠️ Tech Stack

**Languages:** Python, SQL, R, Java, C, JavaScript  
**Agentic AI & LLMs:** LangGraph, LangChain, MCP, RAG, Hybrid Search, Prompt Engineering, Fine-Tuning (QLoRA, LoRA), LLM-as-Judge & Guardrails, Quantization  
**ML & AI:** Machine Learning, Deep Learning, NLP, Computer Vision, Anomaly Detection, Explainable AI  
**Data Science & Engineering:** EDA, Feature Engineering, Statistical Analysis, Model Evaluation, Databricks, dbt, DuckDB, BigQuery, Airflow, Power BI  
**Libraries:** PyTorch, TensorFlow, scikit-learn, Hugging Face Transformers, Sentence-Transformers, FAISS, NumPy, Pandas  
**Platforms & Tools:** GCP (Vertex AI, BigQuery, Cloud Run), AWS, Docker, FastAPI, Redis, Celery, MLflow, GitHub Actions, Git, GitHub, Jupyter, VS Code, Claude Code, Cursor

---

## 🤝 Let’s Connect

<p align="center">
  <a href="https://www.linkedin.com/in/devadarshinipazhthen" target="_blank">
    <img src="https://img.shields.io/badge/-LinkedIn-blue?style=for-the-badge&logo=linkedin"/>
  </a>
  <a href="mailto:pazhanivelthenmozh.d@northeastern.edu">
    <img src="https://img.shields.io/badge/-Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://devadarshinipazhanivelthenmozhi.netlify.app" target="_blank">
    <img src="https://img.shields.io/badge/-Portfolio-000000?style=for-the-badge&logo=netlify&logoColor=white"/>
  </a>
</p>
