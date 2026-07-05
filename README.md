<h1 align="center">Hey, I'm Aakash </h1>
<h3 align="center">I build things with code. RNNs that remember. CNNs that see. ANNs that approximate. Machine learning, AI automations, productivity tools, anything that saves someone an hour, a day, a week of their life.</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/aakashaldankar/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white"></a>
  <a href="https://github.com/aakashaldankar"><img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white"></a>
  <a href="https://huggingface.co/aakashaldankar"><img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=flat&logo=huggingface&logoColor=black"></a>
  <a href="mailto:aakashaldankar@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white"></a>
</p>


<h3 align="center">A Universe of Atoms </h3>

---

## Things I've built

### 🚨 SRE DeepAgent — an on-call engineer that doesn't sleep

Production incidents used to mean someone opening ten dashboards at 2 a.m., trying to piece together what broke and why. I built a multi-agent system on LangGraph that does that investigation itself, pulls logs, correlates signals, reasons through the incident, and hands back a root cause instead of a pile of raw data.

Mean-time-to-resolution dropped by **~60%** across critical workflows. The best compliment it got was an engineer asking why the alert already had an answer attached.

### 📡 Network Analyzer DeepAgent — from a spreadsheet to live telemetry

Started small: a sample dataset, a hunch that anomaly detection could be automated instead of eyeballed. Ended up extending the same pipeline to ingest live production network telemetry, using Qdrant and agentic RAG to flag anomalies as they happen instead of after someone complains.

The gap between "works on sample data" and "works on the real thing" is where most projects die. This one didn't.

### 💬 AI Sales Assist — a system that closes deals while you're at lunch

This one had actual business risk attached: get it wrong and a customer gets a bad quote. Built with LangGraph routing and tool-calling, it answers customer queries, generates real service quotes against live pricing APIs, and tracks orders all without a human touching it.

Response time went from **8 hours to under 5 minutes**. That's not a rounding error, that's the difference between a customer waiting and a customer buying. Retention and acquisition both moved because of it.

### 🏠 Airbnb Price Predictor — an XGBoost model that actually ships

Training a model is the easy 20%. I wanted the other 80% proper experiment tracking with DVC and MLflow, a FastAPI endpoint on AWS, and a feature that compares a listing against 50 nearby ones so a host knows *why* the price is what it is, not just what it is.

### 📖 KaleidoscopeChat — RAG for a textbook.

An AI tutor that answers questions on NCERT Class 12 English, poem by poem. Built vector search with Qdrant and hierarchical indexing with LlamaIndex so it retrieves at the level of a single poem, not a whole chapter. Groq's LLaMA 3.3-70B handles the answers, wrapped in a Gradio UI.

Small project, but it taught me more about retrieval granularity than any tutorial did.

### 📰 Autonomous Newsletter Generator — three agents arguing their way to a draft

Give it one topic. A Researcher agent digs it up, an Editor agent shapes it, a Designer agent lays it out built on CrewAI, running on LangChain and LLaMA 3.3-70B. Out comes a finished HTML newsletter with live status tracking.

Watching three agents hand work off to each other without stepping on one another is still, months later, one of my favorite demos to run.

### 🍜 BiteVision101 — point a camera at food, get an answer

Fine-tuned EfficientNetB2 on Food-101 — 101 categories, 7.8M parameters — landed at **89% accuracy**. Deployed on Gradio with top-3 predictions and confidence scores, because "probably a burrito" is more honest than a single overconfident guess.

---

## The stack behind all of it

**Agentic AI & Orchestration**
`LangGraph` `LangChain` `LlamaIndex` `CrewAI` `DeepAgents` `MCP` `Agentic RAG` `Knowledge Graphs`

**ML & Deep Learning**
`PyTorch` `TensorFlow` `Hugging Face Transformers` `LoRA/QLoRA` `CNNs` `NLP` `Computer Vision` `XGBoost`

**Voice AI**
`LiveKit Agents` `WebRTC` `STT/TTS` `Deepgram` `ElevenLabs` `VAD` `SIP/Telephony`

**MLOps / LLMOps**
`MLflow` `DVC` `LangSmith` `Docker` `Kubernetes` `CI/CD` `Grafana` `Prometheus` `FastAPI`

**Vector Stores & Data**
`Qdrant` `Milvus` `Chroma` `FAISS` `pgvector` `Redis` `PostgreSQL`

**Cloud & Languages**
`AWS` `Azure OpenAI` `Azure ML` `Python` `SQL`

---

## Certifications worth mentioning

`IBM RAG and Agentic AI` · `IBM Generative AI Engineering` · `Microsoft AI & ML Engineering` · `DeepLearning.AI — NLP & Deep Learning` · `Model Context Protocol Mastery` · `IBM AI Engineering`

---

<p align="center">
  <img height="165" src="https://github-readme-stats-eight-theta.vercel.app/api?username=aakashaldankar&show_icons=true&hide_border=true&bg_color=1B1B2F&title_color=FFB347&icon_color=FFCC70&text_color=E8E8E8&ring_color=FFB347" alt="Aakash's GitHub stats" />
  <img height="165" src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=aakashaldankar&layout=compact&hide_border=true&langs_count=8&bg_color=1B1B2F&title_color=FFB347&text_color=E8E8E8" alt="Aakash's top languages" />
</p>
<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=aakashaldankar&hide_border=true&background=1B1B2F&ring=FFB347&fire=FF6F3C&currStreakLabel=FFCC70&sideLabels=E8E8E8&currStreakNum=FFFFFF&sideNums=E8E8E8&dates=9A9A9A&stroke=FFB347" alt="Aakash's GitHub streak" />
</p>
<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=aakashaldankar&hide_border=true&bg_color=1B1B2F&color=E8E8E8&point=FFB347&line=FF8C42&area=true&area_color=FF8C42" alt="Aakash's contribution graph" />
</p>
<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=aakashaldankar&theme=onedark&no-frame=true&row=1&column=6&margin-w=8" alt="Aakash's GitHub trophies" />
</p>
<!-- <p align="center">
  <img src="https://komarev.com/ghpvc/?username=aakashaldankar&label=Profile+Views&color=FFB347&style=flat" alt="Profile views" />
</p> -->

