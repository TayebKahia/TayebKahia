<img src="assets/banner.svg" width="100%" alt="Tayeb Kahia. AI Engineer: LLMs, RAG and AI Agents, ML, Edge AI. Building AI systems that are reliable, safe and production-ready. Open to AI Engineer and ML Engineer roles, remote or on-site. Blida, Algeria. Quotes checked word for word: Grounded Docs drops any quote that isn't in the source document. The model can't send email: Mailroom's agent has no write tools; a person approves every reply. Runs offline on a Raspberry Pi 5: Voice-Swarm-Edge parses voice commands with no cloud or internet. 1,381 and 1,519 tests: Grounded Docs and Mailroom, in Docker, with CI on every change.">

<p>
  <a href="https://tayeb-kahia.vercel.app/"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/btn-portfolio-dark.svg"><img src="assets/btn-portfolio-light.svg" height="40" alt="Portfolio"></picture></a>&nbsp;
  <a href="https://tayeb-kahia.vercel.app/tayeb_kahia_cv.pdf"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/btn-cv-dark.svg"><img src="assets/btn-cv-light.svg" height="40" alt="Download CV"></picture></a>&nbsp;
  <a href="mailto:tayeb.kahia.ai@gmail.com"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/btn-email-dark.svg"><img src="assets/btn-email-light.svg" height="40" alt="Email"></picture></a>
</p>

I build AI systems and measure them, from fine-tuning and evaluating models to shipping them as tested, containerized services. Every result below says how it was measured.

## Projects

<a href="https://tayeb-kahia.vercel.app/projects/voice-swarm-edge">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/voice-swarm-edge-dark.svg">
    <img src="assets/voice-swarm-edge-light.svg" width="100%" alt="Voice-Swarm-Edge: voice commands for five simulated drones, parsed on a Raspberry Pi 5 by a fine-tuned small language model with no cloud. 27.9 tokens/s with Qwen2.5-0.5B (Q4_K_M) on three actively cooled Raspberry Pi 5 CPU cores. 0.935 exact match on 200 recorded commands, scored on reference transcripts, one speaker. 78 of 78 keyword-spotter triggers for hold and abort cancelled the in-flight decode.">
  </picture>
</a>

[Project page](https://tayeb-kahia.vercel.app/projects/voice-swarm-edge) · [Repository](https://github.com/TayebKahia/voice-swarm-edge)

<a href="https://tayeb-kahia.vercel.app/projects/grounded-docs">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/grounded-docs-dark.svg">
    <img src="assets/grounded-docs-light.svg" width="100%" alt="Grounded Docs: a Q&A assistant for the web and Slack that answers only from a team's own documents and verifies every quote in code. 0 hallucinated answers in 42 trials where the right answer was not found. 94.0% outcome accuracy over 168 answers. p95 latency 5.77 s, questions asked one at a time. $0.62 API cost per 1,000 questions at gpt-6-luna list prices.">
  </picture>
</a>

[Project page](https://tayeb-kahia.vercel.app/projects/grounded-docs) · [Repository](https://github.com/TayebKahia/grounded-docs) · [Demo video (6.5 min)](https://github.com/TayebKahia/grounded-docs#-demo-video)

<a href="https://tayeb-kahia.vercel.app/projects/mailroom">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/mailroom-dark.svg">
    <img src="assets/mailroom-light.svg" width="100%" alt="Mailroom: an agent for a shared Gmail inbox that drafts replies and actions, and sends nothing until a person approves. 0 of 30 prompt-injection emails succeeded. 0 unapproved writes, counted from the fake services' write logs. 96.0% category accuracy, 48 of 50 threads.">
  </picture>
</a>

[Project page](https://tayeb-kahia.vercel.app/projects/mailroom) · [Repository](https://github.com/TayebKahia/mailroom-showcase) · [Demo video (3.5 min)](https://github.com/TayebKahia/mailroom-showcase#demo) · [mailroom-mcp on PyPI](https://pypi.org/project/mailroom-mcp/)

<sub>The drones are simulated and the commands come from one speaker. Grounded Docs and Mailroom were evaluated on synthetic data, Mailroom on a pre-release build against fake services. None of these systems has real users or a hosted deployment.</sub>

## Other work

**[mailroom-mcp](https://github.com/TayebKahia/mailroom-mcp)** · 2026<br>
An MCP server for Mailroom, published on PyPI under the MIT license. Seven read and redraft tools; none can approve or send. [PyPI](https://pypi.org/project/mailroom-mcp/) · [Source](https://github.com/TayebKahia/mailroom-mcp)

**[WhatsApp Support Gateway](https://github.com/TayebKahia/whatsapp-support-gateway)** · 2026<br>
Backend work: a FastAPI webhook gateway for order tracking and returns. Rule-based, no LLM. Signature verification, duplicate-message protection and live handover to a human agent; 105 tests, Docker, CI.

**[CareerConnect](https://github.com/TayebKahia/CareerConnect)** · 2025<br>
A career recommendation engine built with graph neural networks and Sentence Transformers, as lead of a team of five.

## Skills

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/skills-dark.svg">
  <img src="assets/skills-light.svg" width="100%" alt="LLM engineering: RAG, hybrid search, embeddings, reciprocal rank fusion, pgvector, prompt engineering, structured outputs, tool calling, MCP servers, guardrails, prompt-injection defenses, human-in-the-loop approval, LLM evaluation. ML and edge AI: PyTorch, Hugging Face Transformers, LoRA fine-tuning, quantization (GGUF, llama.cpp), grammar-constrained decoding, ONNX Runtime, speech recognition, scikit-learn, graph neural networks, statistical testing. Backend and data: Python, SQL, FastAPI, Pydantic, PostgreSQL, REST and OpenAPI, OAuth 2.0 and OIDC, WebSockets. Operations and quality: Docker, CI/CD with GitHub Actions, Grafana, SLOs and burn-rate alerts, k6 load testing, pytest, mypy, Ruff, uv, PyPI publishing.">
</picture>

## Background

**2021 to 2026 · École Supérieure en Informatique de Sidi Bel Abbès (ESI-SBA), Algeria**<br>
State Engineer and Master's degree in Computer Science, major in AI and Data Science. Theses: “Voice-Control for Drone Swarms Formation via Small LLM Models” and “Comparative Evaluation of Quantised Small Language Models for Grammar-Constrained Command Parsing on Edge Hardware”.

**2024 · Algérie Télécom (RMS Center), Blida**<br>
Network and security intern: enterprise networking and security.

**Languages**<br>
Arabic (native), English (fluent), French (proficient).

## Get in touch

I am based in Blida, Algeria. Email is the fastest way to reach me, and the [CV](https://tayeb-kahia.vercel.app/tayeb_kahia_cv.pdf) has the same projects on one page.

**[tayeb.kahia.ai@gmail.com](mailto:tayeb.kahia.ai@gmail.com)**
