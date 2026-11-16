<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <img src="assets/banner-light.svg" width="100%" alt="Tayeb Kahia. AI Engineer: LLMs, RAG and AI Agents, ML, Edge AI. Building AI systems that are reliable, safe and production-ready.">
</picture>

<p align="center">
  <a href="https://tayeb-kahia.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-0f766e?style=for-the-badge" alt="Portfolio"></a>
  <a href="https://tayeb-kahia.vercel.app/tayeb_kahia_cv.pdf"><img src="https://img.shields.io/badge/CV%20(PDF)-0f766e?style=for-the-badge" alt="CV (PDF)"></a>
  <a href="mailto:tayeb.kahia.ai@gmail.com"><img src="https://img.shields.io/badge/Email-30363d?style=for-the-badge" alt="Email"></a>
</p>

I build AI systems and measure them, from fine-tuning and evaluating models to shipping them as tested, containerized services. I hold a State Engineer and Master's degree in AI and Data Science from ESI-SBA. I publish the results that missed their target next to the ones that hit it.

## Projects

<a href="https://github.com/TayebKahia/voice-swarm-edge">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/voice-swarm-edge-dark.svg">
    <img src="assets/voice-swarm-edge-light.svg" width="100%" alt="Voice-Swarm-Edge: on-device voice control for a simulated drone swarm with a fine-tuned small language model. 27.9 tokens/s on a Raspberry Pi 5, 0.935 exact match on 200 commands, 100% schema-valid outputs.">
  </picture>
</a>

<a href="https://github.com/TayebKahia/grounded-docs">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/grounded-docs-dark.svg">
    <img src="assets/grounded-docs-light.svg" width="100%" alt="Grounded Docs: RAG assistant for web and Slack that answers only from a team's documents. 0 hallucinated answers in 42 not-found trials, 94.0% outcome accuracy, p95 latency 5.77 s.">
  </picture>
</a>

<a href="https://github.com/TayebKahia/mailroom-showcase">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/mailroom-dark.svg">
    <img src="assets/mailroom-light.svg" width="100%" alt="Mailroom: email agent that drafts replies and waits for human approval. 0 of 30 prompt-injection attacks succeeded, 0 unapproved writes, 96.0% category accuracy on 50 held-out threads.">
  </picture>
</a>

<sub>Each card links to its repository. Conditions: the drones are simulated and the commands come from one speaker; Grounded Docs and Mailroom were evaluated on synthetic data, Mailroom on a pre-release build against fake services. Each repository has the full method and the misses.</sub>

## Also

- [**mailroom-mcp**](https://github.com/TayebKahia/mailroom-mcp): an MCP server for Mailroom, [published on PyPI](https://pypi.org/project/mailroom-mcp/). Seven read and redraft tools; none can approve or send.
- [**WhatsApp Support Gateway**](https://github.com/TayebKahia/whatsapp-support-gateway): a FastAPI webhook gateway for order tracking and returns, with signature verification, duplicate-message protection and handover to a human agent.
- [**CareerConnect**](https://github.com/TayebKahia/CareerConnect): a career recommendation engine built with graph neural networks and Sentence Transformers, as lead of a team of five.

## Skills

| Area | What I use |
| :-- | :-- |
| **LLM engineering** | RAG (hybrid search, pgvector, reciprocal rank fusion), tool calling, structured outputs, MCP servers, guardrails, prompt-injection defenses, human-in-the-loop approval, evaluation |
| **ML and edge AI** | PyTorch, Hugging Face Transformers, LoRA fine-tuning, quantization (GGUF, llama.cpp), grammar-constrained decoding, speech recognition |
| **Backend and data** | Python, SQL, FastAPI, Pydantic, PostgreSQL, REST, OAuth 2.0, WebSockets |
| **Operations and quality** | Docker, GitHub Actions, Grafana and SLOs, k6 load testing, pytest, mypy, Ruff |
