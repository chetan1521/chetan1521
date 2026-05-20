```
╔══════════════════════════════════════════════════════════╗
║                                                          ║
║        INITIALIZING AGENTIC AI ENGINEER...               ║
║        > SYSTEM ONLINE. AGENT READY.                     ║
║                                                          ║
╚══════════════════════════════════════════════════════════╝
```

<h1 align="center">CHETAN C.</h1>
<p align="center"><b>Agentic AI Engineer · Bangalore, India</b></p>

<p align="center">
  <a href="https://linkedin.com/in/chetan-c-1ba71123b"><img src="https://img.shields.io/badge/LinkedIn-chetan--c-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:chetangowda1521@gmail.com"><img src="https://img.shields.io/badge/Email-chetangowda1521-00d4ff?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://chetan1521.github.io"><img src="https://img.shields.io/badge/Portfolio-chetan1521.github.io-8b5cf6?style=for-the-badge&logo=github&logoColor=white"/></a>
  <img src="https://img.shields.io/badge/📍-Bangalore%2C%20India-22c55e?style=for-the-badge"/>
</p>

---

## `> whoami`

```python
chetan = {
    "role":       "Agentic AI Engineer",
    "focus":      ["LangGraph Agents", "RAG Systems", "LLM Fine-tuning", "MCP Chatbots"],
    "scale":      "10M+ RAG docs · LangGraph · NVIDIA NIM · Groq · Qdrant · Neo4j",
    "ships_to":   "PRODUCTION — always.",
    "currently":  "Building MedMind — open-source medical research AI ecosystem.",
}
```

---

## `> ls ./projects`

### 🔬 [medical-research-agent](https://github.com/chetan1521/medical-research-agent)
*LangGraph agent connecting live clinical trials + PubMed RAG + fine-tuned biomedical SLM*

Multi-tool LangGraph agent that plans, selects tools, and synthesises grounded answers for medical research questions — querying a live clinical trial database, running hybrid RAG over 10M+ PubMed abstracts, and reasoning with a locally fine-tuned biomedical SLM. NVIDIA NIM for synthesis, Groq for fast planning.

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![NVIDIA NIM](https://img.shields.io/badge/NVIDIA_NIM-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square&logo=groq&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

---

### 🏥 [clinical-trial-crawler](https://github.com/chetan1521/clinical-trial-crawler)
*LangGraph autonomous agent crawling ClinicalTrials.gov + WHO ICTRP — zero selectors, LLM navigation*

Autonomous browser agent that crawls 500K+ clinical trials with zero hand-written selectors. Groq Llama-3.1-8B drives navigation decisions, NVIDIA NIM extracts structured trial schemas via JSON mode, Playwright intercepts raw API payloads — all orchestrated by a LangGraph StateGraph with Redis checkpointing.

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square&logo=groq&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-45ba4b?style=flat-square&logo=playwright&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

---

### 📚 [medrag-paper-assistant](https://github.com/chetan1521/medrag-paper-assistant)
*LangGraph RAG agent over 10M+ PubMed abstracts · hybrid BM25 + Qdrant · Neo4j · <2s latency*

Production RAG system with hybrid sparse + dense retrieval in parallel, Reciprocal Rank Fusion, local BAAI/bge cross-encoder reranking, and Neo4j AuraDB citation graph expansion. Qdrant self-hosted, BAAI/bge embeddings local, NVIDIA NIM for generation.

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-008CC1?style=flat-square&logo=neo4j&logoColor=white)
![NVIDIA NIM](https://img.shields.io/badge/NVIDIA_NIM-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Latency](https://img.shields.io/badge/Latency-%3C2s-00d4ff?style=flat-square)

---

### 🧬 [biomedical-slm-finetune](https://github.com/chetan1521/biomedical-slm-finetune)
*QLoRA fine-tuning on PubMedQA + MedQA → GGUF → FastAPI · GPU (Colab T4 / Kaggle P100)*

End-to-end pipeline to fine-tune small LMs on open biomedical datasets using QLoRA (4-bit base loading) on GPUs. Dataset prep from HuggingFace → LoRA training → W&B tracking → GGUF quantization via llama.cpp → OpenAI-compatible FastAPI server. Produced model powers medical-research-agent.

![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![LoRA/PEFT](https://img.shields.io/badge/LoRA%2FPEFT-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Colab](https://img.shields.io/badge/Colab_T4-F9AB00?style=flat-square&logo=googlecolab&logoColor=white)
![llama.cpp](https://img.shields.io/badge/llama.cpp-gray?style=flat-square)
![W&B](https://img.shields.io/badge/W%26B-FFBE00?style=flat-square&logo=weightsandbiases&logoColor=black)

---

## `> cat ./tech_stack.json`

| Layer | Technologies |
|---|---|
| **Agent Orchestration** | LangGraph · LangChain · MCP (Model Context Protocol) |
| **LLM / AI** | Amazon Bedrock · Vertex AI · Claude (Anthropic) · GPT-4 · Gemini · Ollama (local) · LLama |
| **RAG & Retrieval** | Qdrant · Pinecone · BM25 · Neo4j · BAAI/bge embeddings · Cross-encoder reranking |
| **Fine-tuning** | LoRA/PEFT · QLoRA · bitsandbytes · llama.cpp · GGUF · HuggingFace Transformers |
| **Cloud & MLOps** | GCP / Vertex AI · Azure · AWS Bedrock · Docker · FastAPI · Redis · Weights & Biases |
| **Programming & Data** | Python · SQL · Playwright · MongoDB · Streamlit · ReactJS |

---

## `> cat ./stats`

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=chetan1521&show_icons=true&theme=tokyonight&bg_color=060a12&title_color=00d4ff&icon_color=00d4ff&text_color=c9d1d9&border_color=00d4ff&hide_border=false" height="165"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=chetan1521&layout=compact&theme=tokyonight&bg_color=060a12&title_color=00d4ff&text_color=c9d1d9&border_color=00d4ff&hide_border=false" height="165"/>
</p>

---

## `> cat ./certifications`

```
✓  Google Cloud Generative AI Academy
✓  Develop GenAI Apps with Gemini and Streamlit  —  Google
✓  Agentic AI in Practice                         —  IBM TechXchange
✓  Prompt Design in Vertex AI                     —  Google
```

---

## `> ./connect.sh`

```
┌──────────────────────────────────────────────────────┐
│                                                      │
│   Open to:  Agentic AI · LLM Engineer · AI Systems   │
│   Remote:   ✓   |   Base: Bangalore, India          │
│                                                      │
│   📧  chetangowda1521@gmail.com                     │
│   🔗  linkedin.com/in/chetan-c-1ba71123b            │
│                                                      │
└──────────────────────────────────────────────────────┘
```

> *"I don't just build AI models. I ship AI systems."*
