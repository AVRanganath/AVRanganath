<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,100:1B2735&height=200&section=header&text=A.V.%20Ranganath&fontSize=40&fontColor=F2A541&animation=fadeIn&fontAlignY=35&desc=AI%2FML%20Engineer%20%7C%20Indic%20Language%20Tech%20%7C%20Bengaluru%2C%20India&descAlignY=55&descSize=16&descColor=2DD4BF" width="100%" alt="header banner"/>

### ನಮಸ್ಕಾರ • வணக்கம் • नमस्ते

[![Typing SVG](https://readme-typing-svg.demolab.com/?font=Fira+Code&size=20&pause=1200&color=E6E6E6&center=true&vCenter=true&width=650&height=45&lines=B.Tech%20IT%20Student%20%40%20JSSATEB;Fine-tuning%20LLMs%20for%20Indic%20Languages;Building%20IndicEdgeTok%20-%20a%20morphology-aware%20tokenizer;Tech%20Lead%20%40%20GDG%20OnCampus%20JSSATEB;Turning%20research%20papers%20into%20working%20code)](https://github.com/AVRanganath)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/avranganath)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:a.v.ranganath2005@gmail.com)
![Profile Views](https://komarev.com/ghpvc/?username=AVRanganath&color=2DD4BF&style=for-the-badge&label=Profile%20Views)

</div>

<br>

## 👋 About Me

I'm a final-year B.Tech (Information Science & Engineering) student at **JSS Academy of Technical Education, Bengaluru** (CGPA 8.7), building AI systems for the languages most large models still treat as an afterthought.

- 🔭 Currently deep in **IndicEdgeTok** — a morphology-aware tokenizer + fine-tuned LLM for Kannada, Tamil, and Hindi
- 🧠 Comfortable across the ML stack: fine-tuning (LoRA/QLoRA, Unsloth), local inference (Ollama), and the product layer around the model (Flask, Streamlit)
- 🌱 Leading **GDG OnCampus JSSATEB** as Tech Lead (1,000+ members) and chairing the **IEEE Student Chapter ITS**
- 🏆 4x hackathon/ideathon placements, most recently 1st place at DSATM's national-level hackathon

<br>

## 🛠️ Tech Stack

**Languages**

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

**AI / ML**

![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
![HuggingFace](https://img.shields.io/badge/%F0%9F%A4%97%20HuggingFace-FFD21E?style=for-the-badge)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)
![QLoRA](https://img.shields.io/badge/QLoRA%2FLoRA-6D3FC0?style=for-the-badge)
![Unsloth](https://img.shields.io/badge/Unsloth-1A1A2E?style=for-the-badge)

**Tools & Infra**

![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![GCP](https://img.shields.io/badge/GoogleCloud-%234285F4.svg?style=for-the-badge&logo=google-cloud&logoColor=white)
![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)

<br>

## 🚀 Featured Projects

### 🔤 [IndicEdgeTok](https://github.com/AVRanganath/IndicEdgeTok) — Morphology-Aware Multilingual Tokenizer & LLM *(ongoing)*

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![HF](https://img.shields.io/badge/%F0%9F%A4%97%20Transformers-FFD21E?style=flat-square)
![QLoRA](https://img.shields.io/badge/QLoRA-6D3FC0?style=flat-square)

Designing a morphology-aware tokenizer for Kannada, Tamil, and Hindi with dynamic English code-mix detection — targeting the token-fertility bottleneck that makes Indic text expensive for English-centric LLMs. Adapting a 7–8B open-source base model (Mistral/Llama) through vocabulary expansion, continued pre-training on the **Sangraha** corpus, and QLoRA instruction tuning on **IndicAlign-Instruct**, all on a single A6000 GPU. Benchmarking against IndicSuperTokenizer and Airavata on Indic LLM Arena; tokenizer and fine-tuned weights shipping open-source on Hugging Face.

### 🧬 [Genevision](https://github.com/AVRanganath/Genevision) — Genetic Disorder Risk Prediction Platform

![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)

A 4-layer feed-forward network (256→128→64→32→1, BatchNorm + Dropout) trained on a synthetic Mendelian-genetics dataset spanning 10 disorders, recovering inheritance rules with **MAE 0.0019, R² 0.9998**. Full pipeline built end-to-end — feature engineering across 13 genomic features, early stopping, checkpointing, and serialized preprocessing for reproducible inference. Paired with a fine-tuned DeepSeek-R1 8B model that writes clinical-style PDF reports (ReportLab) and a NetworkX/matplotlib Punnett-square visualizer, served through Streamlit.

### 🆘 [Emency](https://github.com/AVRanganath/Emency) — Real-Time Emergency Disaster SOS Platform

![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=flat-square&logo=sqlite&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)

Real-time disaster monitoring platform ingesting USGS earthquakes, NDMA SACHET alerts, and NASA FIRMS hotspots, deduplicated and enriched against 8 major Indian cities. A 5-agent LLM council (Verifier, Risk Assessor, Composer, Coordinator, Voting Moderator) runs on a locally-hosted 0.6B model, gated by a deterministic weighted-voting formula before anything publishes. Shipped as a Flask + SQLite backend with live alerts and SMS dispatch via the 112/1070 helplines through an email-to-SMS gateway.

> **Note:** these three links point to where the repos will live once pushed — see tip #1 below, this is the first thing to fix.

<br>

## 📊 GitHub Stats

<table>
<tr>
<td width="50%">

![AVRanganath's GitHub stats](https://github-stats-extended.vercel.app/api?username=AVRanganath&show_icons=true&hide_border=true&bg_color=0D1117&title_color=F2A541&icon_color=2DD4BF&text_color=E6E6E6)

</td>
<td width="50%">

![Top Languages](https://github-stats-extended.vercel.app/api/top-langs/?username=AVRanganath&layout=compact&hide_border=true&bg_color=0D1117&title_color=F2A541&text_color=E6E6E6)

</td>
</tr>
</table>

<div align="center">

![GitHub Streak](https://streak-stats.demolab.com/?user=AVRanganath&hide_border=true&background=0D1117&ring=2DD4BF&fire=F2A541&currStreakLabel=F2A541&sideLabels=9CA3AF&currStreakNum=E6E6E6&sideNums=E6E6E6&dates=6B7280)

</div>

<br>

## 🐍 Contribution Graph

<div align="center">

<picture>
  <img alt="contribution snake animation" src="https://raw.githubusercontent.com/AVRanganath/AVRanganath/output/github-contribution-grid-snake.svg" width="100%"/>
</picture>

</div>

<!-- This animates once the snake.yml workflow (included alongside this README) has run in your repo. See the setup steps for the one-time GitHub Action wiring. -->

<br>

## 🏅 Leadership & Recognition

| Role | Organization | Since |
|---|---|---|
| Tech Lead | Google Developer Groups OnCampus, JSSATEB | 2025 |
| Chair | IEEE Student Chapter ITS, JSSATEB | 2026 |

- 🥇 1st Place — National-Level Hackathon, Dayananda Sagar Academy of Technology & Management
- 🥉 3rd Place — National-Level Hackathon, Dayananda Sagar College of Engineering
- 🎯 Track Prize — International-Level Hackathon, REVA University
- 🥇 1st Place — Ideathon, JSSATEB

<br>

<div align="center">

## 📫 Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/avranganath)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:a.v.ranganath2005@gmail.com)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1B2735,100:0D1117&height=120&section=footer" width="100%" alt="footer banner"/>

</div>
