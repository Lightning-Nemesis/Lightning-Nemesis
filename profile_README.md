<div align="center">

```
 █████╗ ███╗   ███╗██████╗ ██╗████████╗
██╔══██╗████╗ ████║██╔══██╗██║╚══██╔══╝
███████║██╔████╔██║██████╔╝██║   ██║   
██╔══██║██║╚██╔╝██║██╔══██╗██║   ██║   
██║  ██║██║ ╚═╝ ██║██║  ██║██║   ██║   
╚═╝  ╚═╝╚═╝     ╚═╝╚═╝  ╚═╝╚═╝   ╚═╝  
```

### Amrit Mahajan · `Lightning-Nemesis`

**MS Computer Science @ Arizona State University** &nbsp;·&nbsp; GPA 4.0  
AI/ML Engineer · LLM Researcher · Former Data Scientist @ Bajaj Finance

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/amrit-mahajan)
[![Email](https://img.shields.io/badge/Gmail-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:amrit.mahajan007@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Lightning--Nemesis-181717?style=flat-square&logo=github)](https://github.com/Lightning-Nemesis)

</div>

---

## 👨‍💻 About Me

I build and evaluate **large language models** — from multilingual benchmarking to reasoning systems to production RAG pipelines. I have industry experience shipping ML at scale at Bajaj Finance and research experience in LLM evaluation at ASU. Currently interning on the **Gen AI team at Wells Fargo**.

- 🔭 &nbsp;Researching multilingual performance gaps in LLMs across 100+ languages
- 🏢 &nbsp;Previously: Data Scientist @ Bajaj Finance · ML deployed to 40M+ users
- 🎓 &nbsp;B.Tech CS @ VIT Vellore · Merit Scholarship, Top 10 rank
- 🏆 &nbsp;Runner-up @ Voxel51 Visual AI Hackathon · Finalist @ JPMorgan Code For Good

---

## 🚀 Featured Projects

### [`multilingual-llm-benchmark`](https://github.com/Lightning-Nemesis/multilingual-llm-benchmark)
**Identifying LLM Performance Gaps Across Languages**  
Benchmarked OLMo-2-7B across ~100 languages and 10 datasets. Measured the correlation between pre-training token exposure and downstream accuracy, and tested English Chain-of-Thought as a cross-lingual reasoning bridge.

`OLMo-2` &nbsp;`vLLM` &nbsp;`NLLB-200` &nbsp;`Hunyuan-MT` &nbsp;`FastText` &nbsp;`Self-Consistency`

---

### [`star-gsm8k-reasoner`](https://github.com/Lightning-Nemesis/star-gsm8k-reasoner)
**Self-Taught Reasoner for Mathematical Problem Solving**  
Implemented the STaR methodology on LLaMA 3.2-3B — iterative rationale refinement with hint-guided correction, outperforming both vanilla SFT and zero-shot CoT on GSM8K.

`LLaMA-3.2` &nbsp;`vLLM` &nbsp;`TRL` &nbsp;`SFT` &nbsp;`Chain-of-Thought`

---

### `ClickLess AI` *(in progress)*
**Autonomous Grocery Shopping Agent**  
Conversational AI agent that converts natural language into checkout-ready grocery carts using Instacart API, Knowledge Graphs, and LLM orchestration with automated checkout via BrowserUse and Playwright.

`LLM Agents` &nbsp;`Knowledge Graphs` &nbsp;`BrowserUse` &nbsp;`Playwright`

---

## 🛠️ Stack

**AI / LLMs**  
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)

**Languages & Data**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)

**MLOps & Tools**  
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## 📊 Stats

<div align="center">

![Amrit's GitHub Stats](https://github-readme-stats.vercel.app/api?username=Lightning-Nemesis&show_icons=true&theme=dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9&icon_color=58a6ff)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Lightning-Nemesis&layout=compact&theme=dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9)

</div>

---

## 🔬 Research Focus

I work on **multilingual evaluation of large language models** — specifically understanding *why* LLMs fail in non-English languages and whether those failures come from linguistic incomprehension or architectural bias baked in during pre-training.

Currently: MS CS @ ASU &nbsp;|&nbsp; Previously: B.Tech @ VIT Vellore

---

## 🚀 Featured Projects

### [`multilingual-llm-benchmark`](https://github.com/Lightning-Nemesis/multilingual-llm-benchmark)
> **Identifying LLM Performance Gaps Across ~100 Languages**

Comprehensive benchmark evaluating **OLMo-2-7B** across 10 datasets and ~100 languages spanning Math, Commonsense, NLI, Healthcare QA, and General Knowledge.

- Translated datasets via **NLLB-200** and **Hunyuan-MT-7B** (WMT25 winner)
- Self-consistency inference: 20 runs/sample with majority voting
- Measured token exposure in **843B token** pre-training corpus via FastText
- Pre-training Spearman correlation with accuracy: **0.942**
- English Chain-of-Thought experiments across all 100 languages

`OLMo-2` `vLLM` `NLLB` `HuggingFace` `FastText` `Self-Consistency`

---

### [`star-gsm8k-reasoner`](https://github.com/Lightning-Nemesis/star-gsm8k-reasoner)
> **Self-Taught Reasoner for Mathematical Problem Solving**

Implemented the **STaR methodology** to boost LLaMA 3.2-3B-Instruct on GSM8K through iterative rationale refinement — outperforming both vanilla SFT and zero-shot CoT.

| Method | GSM8K Accuracy |
|---|---|
| Zero-Shot CoT (baseline) | 65.30% |
| Vanilla SFT | 45.03% |
| **STaR SFT (ours)** | **73.41%** |

- 10-round iterative correction loop → **97.93% dataset quality**
- Fine-tuned with HuggingFace TRL SFTTrainer on A100 GPU

`LLaMA-3.2` `vLLM` `TRL` `SFT` `Chain-of-Thought` `GSM8K`

---

### [`income-classification-and-segmentation`](https://github.com/Lightning-Nemesis/income-classification-and-segmentation)
> Income prediction and customer segmentation using classical ML pipelines

`scikit-learn` `pandas` `clustering` `classification`

---

### [`smart_parking_system`](https://github.com/Lightning-Nemesis/smart_parking_system)
> IoT-integrated smart parking management system

`Python` `IoT` `Computer Vision`

---

## 🛠️ Tech Stack

**LLMs & NLP**  
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![vLLM](https://img.shields.io/badge/vLLM-4B0082?style=flat-square)
![Transformers](https://img.shields.io/badge/Transformers-orange?style=flat-square)

**Languages**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)

**ML / Data**  
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

---

## 📊 GitHub Stats

<div align="center">

![Amrit's GitHub Stats](https://github-readme-stats.vercel.app/api?username=Lightning-Nemesis&show_icons=true&theme=dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9&icon_color=58a6ff)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Lightning-Nemesis&layout=compact&theme=dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9)

</div>

---

<div align="center">

*"Languages with more tokens in the training corpus exhibit substantially higher downstream accuracy."*  
— from my own research, probably

</div>
