<div align="center">

# Ashwath David

**Applied AI · Mechanistic Interpretability · Agentic Systems**

MS Data Science, University of Maryland · Published @ EMNLP 2025

I build production AI systems and crack them open to understand why they work.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ashwath-david/)
&nbsp;&nbsp;
[![arXiv](https://img.shields.io/badge/arXiv-B31B1B?style=flat-square&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2504.16460)
&nbsp;&nbsp;
[![Email](https://img.shields.io/badge/adavid12@umd.edu-333?style=flat-square&logo=gmail&logoColor=white)](mailto:adavid12@umd.edu)

</div>

<br/>

> *I don't use LLMs as answer machines. I use them as components in validated pipelines — with evidence grounding, anti-hallucination checks, and human-in-the-loop gates where the stakes require it.*

<br/>

---

<br/>

#### work

Trained a family of **domain-specific LLMs** (1.5B–18B) with LoRA/QLoRA and a custom tokenizer — deployed on Trainium at 8x cost savings, ranked #1 on an industry-wide leaderboard. Built the **embedding model** that sits underneath (triplet-loss fine-tuned, 88–93% RAG accuracy vs 75% generic, published at EMNLP 2025).

Built a **GenAI developer platform** used by 200+ engineers — including a code dependency graph analyzer, enterprise hybrid RAG (92% accuracy @ 50K QPS), and agentic SQL-to-NL (95% accuracy). Deployed for Fortune 500 clients.

Built a **production voice AI pipeline** — streaming ASR→LLM→TTS at sub-500ms latency with a novel 3-stage barge-in system (32ms instant pause → evidence accumulation → reversible resolution) and adaptive VAD with hysteresis.

Built **autonomous agent systems** for incident response (8-agent DAG with reflection loops and policy-as-code governance) and network fault diagnosis (10-node pipeline, 25 API integrations, zero-LLM classifier at <1ms, Neo4j memory).

Currently a grad researcher at UMD studying **geopolitical bias in LLMs** through causal tracing and activation patching.

<br/>

#### research

| | |
|---|---|
| **mechanistic interpretability** | causal tracing · activation patching · logit attribution · tuned lens |
| **geopolitical bias** | how LLMs encode and reproduce geopolitical framing · NeurIPS 2026 |
| **agentic evaluation** | LLM-as-judge for measuring agent reliability in production |

<br/>

#### papers

```
[1] Telecom Vectorization Model          EMNLP 2025        arxiv.org/abs/2504.16460
[2] Low-Latency Voice Agents             preprint          arxiv.org/abs/2508.04721
[3] Telecom-Specific Language Model      preprint          arxiv.org/abs/2505.07877
[4] IoT Security Feature Extraction      ICIDCA 2024       Elsevier
```

<br/>

---

<br/>

```
training      LoRA · QLoRA · SFT · DPO · DeepSpeed · FSDP · Trainium
serving       vLLM · TensorRT-LLM · GPTQ · AWQ · Triton
agents        LangGraph · Strands · LlamaIndex · Semantic Kernel
retrieval     FAISS · Neo4j · Pinecone · hybrid search · reranking
interp        TransformerLens · causal tracing · activation patching
speech        Whisper · Nemotron · Kokoro TTS · VAD
infra         Docker · K8s · Ray · AWS · GCP
languages     Python · C++ · Rust · SQL · TypeScript
```

<br/>

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=adx-coder&show_icons=true&theme=github_dark&count_private=true&hide_border=true&bg_color=0d1117&icon_color=58a6ff&title_color=58a6ff" />
<img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=adx-coder&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff"/>

</div>
