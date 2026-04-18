# LLM Topics & Learning Roadmap

| # | Topic | Category | What It Covers | Priority |
|---|------|----------|---------------|----------|
| 1 | Transformer Architecture | Fundamentals | Self-attention, multi-head attention, positional encoding, encoder-decoder | Essential |
| 2 | Tokenization | Fundamentals | BPE, WordPiece, SentencePiece, token limits, tiktoken | Essential |
| 3 | Embeddings | Fundamentals | Word2Vec, sentence embeddings, semantic similarity, embedding models | Essential |
| 4 | Context Window | Fundamentals | Token limits, long context models, context stuffing, sliding window | Essential |
| 5 | Temperature & Sampling | Fundamentals | Temperature, top-p, top-k, greedy decoding, beam search | Essential |
| 6 | Prompt Engineering | Core Skill | Zero-shot, few-shot, chain-of-thought, system prompts, role prompting | Essential |
| 7 | Structured Output | Core Skill | JSON mode, function calling, Pydantic, Instructor library | Essential |
| 8 | RAG (Retrieval Augmented Generation) | Core Skill | Document loaders, chunking, retrieval, context injection, grounding | Essential |
| 9 | Vector Databases | Core Skill | FAISS, Chroma, Pinecone, Weaviate, pgvector, similarity search | Essential |
| 10 | LangChain | Framework | Chains, LCEL, memory, tools, document loaders, output parsers | Essential |
| 11 | LlamaIndex | Framework | Query engines, index types, sub-question routing, node parsers | High |
| 12 | Fine-tuning | Model Customization | LoRA, QLoRA, full fine-tuning, PEFT, HuggingFace TRL | High |
| 13 | RLHF | Model Training | Reward modeling, PPO, preference data, human feedback loops | High |
| 14 | DPO | Model Training | Direct Preference Optimization, alternative to RLHF, simpler pipeline | High |
| 15 | Instruction Tuning | Model Training | SFT, chat templates, instruction datasets, FLAN-style training | High |
| 16 | Chunking Strategies | RAG | Fixed size, recursive, semantic, sentence-window, parent-document | High |
| 17 | Advanced RAG | RAG | HyDE, CRAG, Self-RAG, reranking, query expansion, fusion retrieval | High |
| 18 | Hybrid Search | RAG | BM25 + vector, keyword + semantic, reciprocal rank fusion | High |
| 19 | Reranking | RAG | Cross-encoder rerankers, Cohere Rerank, ColBERT, BGE reranker | High |
| 20 | Multimodal LLMs | Models | Vision-language models, GPT-4V, Gemini, Claude vision, image + text | High |
| 21 | LangGraph | Agents | StateGraph, nodes, edges, checkpointing, human-in-the-loop | High |
| 22 | AI Agents | Agents | ReAct, tool use, planning, memory, execution loop | High |
| 23 | Tool Calling / Function Calling | Agents | Tool definitions, parallel calls, tool chaining, error handling | High |
| 24 | Multi-Agent Systems | Agents | Supervisor, swarm, hierarchical, CrewAI, AutoGen, AG2 | High |
| 25 | Memory Systems | Agents | Short-term, long-term, episodic, semantic memory, MemGPT | High |
| 26 | MCP (Model Context Protocol) | Standards | Tool access standard, MCP servers, MCP clients, Anthropic open protocol | High |
| 27 | DSPy | Advanced | Automated prompt optimization, signatures, teleprompters, MIPRO | High |
| 28 | LLM Evaluation | Production | BLEU, ROUGE, LLM-as-judge, RAGAS, domain evals, Evals frameworks | High |
| 29 | Hallucination & Grounding | Production | Hallucination types, detection, grounding strategies, citation | High |
| 30 | Guardrails & Safety | Production | Output validation, NeMo Guardrails, Guardrails AI, content filtering | High |
| 31 | Observability & Tracing | Production | LangSmith, Phoenix, Helicone, W&B Weave, trace + span patterns | High |
| 32 | LLM Caching | Production | Semantic caching, exact caching, GPTCache, Redis for LLMs | Medium |
| 33 | Streaming Responses | Production | Server-sent events, streaming tokens, partial outputs, UX patterns | Medium |
| 34 | Batch Inference | Production | Batch API, async calls, throughput optimization, cost reduction | Medium |
| 35 | ReAct Prompting | Agent Patterns | Reason + Act loop, tool calling with reasoning traces | Medium |
| 36 | Plan-and-Execute | Agent Patterns | Planning agent + execution agent, task decomposition | Medium |
| 37 | Reflexion | Agent Patterns | Self-critique, iterative refinement, verbal reinforcement learning | Medium |
| 38 | Tree of Thoughts (ToT) | Agent Patterns | Branching reasoning paths, search over thought trees | Medium |
| 39 | Self-RAG | RAG | Adaptive retrieval, self-critique on retrieved docs, relevance scoring | Medium |
| 40 | Graph RAG | RAG | Knowledge graphs + RAG, entity extraction, Microsoft GraphRAG | Medium |
| 41 | Agentic RAG | RAG + Agents | Agent decides when/how to retrieve, multi-step retrieval | Medium |
| 42 | Multimodal RAG | RAG | Image + text retrieval, ColPali, vision embeddings | Medium |
| 43 | Quantization | Models | INT4, INT8, GPTQ, AWQ, bitsandbytes, model compression | Medium |
| 44 | Speculative Decoding | Models | Draft model + verification, faster inference, lookahead decoding | Medium |
| 45 | KV Cache | Models | Key-value cache, prefix caching, cache-aware routing | Medium |
| 46 | Flash Attention | Models | Memory-efficient attention, FlashAttention 2/3, long context speed | Medium |
| 47 | Model Merging | Models | SLERP, TIES, DARE, mergekit, combining specialized models | Medium |
| 48 | Prompt Injection | Security | Direct injection, indirect injection, jailbreaks, prompt hardening | Medium |
| 49 | Red Teaming LLMs | Security | Adversarial testing, jailbreak detection, safety evaluation | Medium |
| 50 | Synthetic Data Generation | Data | LLM-generated training data, Evol-Instruct, distillation datasets | Medium |
| 51 | Distillation | Models | Teacher-student training, knowledge distillation, smaller capable models | Medium |
| 52 | Constitutional AI | Alignment | Anthropic's CAI method, critique + revision, harmlessness training | Medium |
| 53 | Agents with Code Execution | Agents | Code interpreter, sandboxed execution, E2B, Modal code runners | Medium |
| 54 | Browser / Computer Use Agents | Agents | Playwright agents, Claude computer use, browser automation + LLMs | Medium |
| 55 | Voice AI / Speech LLMs | Multimodal | Whisper, TTS, voice agents, Realtime API, ElevenLabs + LLMs | Medium |
| 56 | LLM Routing | Architecture | Mixture of agents, model router, RouteLLM, cost-aware routing | Medium |
| 57 | OpenAI API Patterns | APIs | Chat completions, streaming, function calling, vision, Assistants API | Medium |
| 58 | Anthropic API Patterns | APIs | Messages API, tool use, vision, streaming, system prompts, MCP | Medium |
| 59 | Ollama & Local LLMs | Local AI | Run Llama/Mistral locally, Ollama serve, Open WebUI, privacy-first | Medium |
| 60 | LLM Serving Frameworks | Deployment | vLLM, TGI, Triton, llama.cpp, PagedAttention, production serving | Advanced |
| 61 | Mixture of Experts (MoE) | Architecture | Sparse MoE, routing, Mixtral, expert specialization | Advanced |
| 62 | Long Context Strategies | Architecture | RoPE scaling, ALiBi, YARN, positional interpolation for 1M+ tokens | Advanced |
| 63 | State Space Models | Architecture | Mamba, SSMs vs transformers, linear-time sequence modeling | Advanced |
| 64 | Continual Learning | Training | Catastrophic forgetting, replay methods, online fine-tuning | Advanced |
| 65 | LLM Benchmarks | Evaluation | MMLU, HumanEval, HellaSwag, LMSYS Chatbot Arena, BigBench | Reference |
| 66 | Cost Optimization | Production | Token counting, model selection strategy, caching, batching costs | Reference |
