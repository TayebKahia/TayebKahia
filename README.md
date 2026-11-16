# Tayeb Kahia

**AI Engineer · LLMs, RAG and AI Agents · ML · Edge AI**

[Portfolio](https://tayeb-kahia.vercel.app/) · [Email](mailto:tayeb.kahia.ai@gmail.com) · [CV (PDF)](https://tayeb-kahia.vercel.app/tayeb_kahia_cv.pdf)

I build AI systems and measure them, from fine-tuning and evaluating models to shipping them as tested, containerized services. I hold a State Engineer and Master's degree in AI and Data Science from ESI-SBA. I publish the results that missed their target next to the ones that hit it.

## Projects

| Project | What it is | Measured | Stack |
| :-- | :-- | :-- | :-- |
| [**Voice-Swarm-Edge**](https://github.com/TayebKahia/voice-swarm-edge) | On-device voice control for a drone swarm, with a fine-tuned small language model on a Raspberry Pi 5 | 27.9 tokens/s on three CPU cores · 0.935 exact match on 200 recorded commands · every output schema-valid | PyTorch, PEFT, llama.cpp, whisper.cpp, ONNX Runtime |
| [**Grounded Docs**](https://github.com/TayebKahia/grounded-docs) | RAG assistant (web and Slack) that answers only from a team's own documents and checks every quote in code | 0 hallucinated answers in 42 not-found trials · 94.0% outcome accuracy · p95 latency 5.77 s | FastAPI, OpenAI API, PostgreSQL, pgvector, Docker |
| [**Mailroom**](https://github.com/TayebKahia/mailroom-showcase) | Email agent for a shared inbox that drafts replies and waits for human approval; the model has no write tools | 0 of 30 prompt-injection attacks succeeded · 0 unapproved writes · 96.0% category accuracy | FastAPI, OpenAI function calling, PostgreSQL, MCP |

<sub>Conditions: the drones are simulated and the commands come from one speaker; Grounded Docs and Mailroom were evaluated on synthetic data, Mailroom on a pre-release build against fake services. Each repository has the full method and the misses.</sub>

## Also

- [**mailroom-mcp**](https://github.com/TayebKahia/mailroom-mcp): an MCP server for Mailroom, [published on PyPI](https://pypi.org/project/mailroom-mcp/). Seven read and redraft tools; none can approve or send.
- [**WhatsApp Support Gateway**](https://github.com/TayebKahia/whatsapp-support-gateway): a FastAPI webhook gateway for order tracking and returns, with signature verification, duplicate-message protection and handover to a human agent.
- [**CareerConnect**](https://github.com/TayebKahia/CareerConnect): a career recommendation engine built with graph neural networks and Sentence Transformers, as lead of a team of five.
## Skills

- **LLM engineering:** RAG (hybrid search, pgvector, reciprocal rank fusion), tool calling, structured outputs, MCP servers, guardrails, prompt-injection defenses, human-in-the-loop approval, evaluation
- **ML and edge AI:** PyTorch, Hugging Face Transformers, LoRA fine-tuning, quantization (GGUF, llama.cpp), grammar-constrained decoding, speech recognition
- **Backend and data:** Python, SQL, FastAPI, Pydantic, PostgreSQL, REST, OAuth 2.0, WebSockets
- **Operations and quality:** Docker, GitHub Actions, Grafana and SLOs, k6 load testing, pytest, mypy, Ruff
