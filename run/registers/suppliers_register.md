# Supplier Register

Current state of third-party suppliers. One row per supplier. Update rows in place when status changes.

Suppliers below were seeded from the third-party API catalogue of the [vLLM Semantic Router](https://github.com/vllm-project/semantic-router) project (`src/semantic-router/pkg/catalog/zz_generated_catalog.go`). Only external model-API providers and supporting SaaS services are listed; self-hosted runtimes (Ollama, vLLM, SGLang, LM Studio, NVIDIA Triton, Docker Model Runner, Lemonade, Xinference, AMD ATOM) are excluded as they are not third parties. Mark a supplier Active only once it is actually enabled in production configuration.

| Supplier ID | Supplier | Department | Description | Certifications | Last reviewed | Next review | Status | Notes |
|-------------|----------|------------|-------------|---------------|---------------|-------------|--------|-------|
| SUP-001 | OpenAI | Engineering | OpenAI Chat Completions and Responses API (api.openai.com). Native protocol. | — | — | — | Candidate | Frontier reasoning lane (gpt-5.x). Native `openai` provider. |
| SUP-002 | Anthropic | Engineering | Anthropic Messages API (api.anthropic.com) via x-api-key. Native protocol. | — | — | — | Candidate | High-care legal/compliance/health lane (claude-opus). Native `anthropic` provider; header `anthropic-version: 2023-06-01`. |
| SUP-003 | Google Gemini | Engineering | Google Gemini generative language API (generativelanguage.googleapis.com). Native protocol. | — | — | — | Candidate | Complex-domain lane (gemini-3.1-pro) and low-cost lane (gemini-2.5-flash-lite). Native `gemini` provider. |
| SUP-004 | Google Vertex AI | Engineering | Google Vertex AI managed model endpoint. Native protocol. | — | — | — | Candidate | Enterprise Google deployment path; base URL is deployment-specific. |
| SUP-005 | Azure OpenAI | Engineering | Azure OpenAI Service (deployment-specific endpoint). Native protocol. | — | — | — | Candidate | Microsoft-hosted OpenAI; base URL is deployment-specific. |
| SUP-006 | Amazon Bedrock | Engineering | Amazon Bedrock managed model service. Native protocol. | — | — | — | Candidate | AWS-hosted model access; base URL is account/region-specific. |
| SUP-007 | Microsoft Foundry | Engineering | Microsoft Foundry managed model service. Native protocol. | — | — | — | Candidate | Azure-hosted model access. |
| SUP-008 | Meta | Engineering | Meta Model API (api.meta.ai). Native protocol. | — | — | — | Candidate | Native `meta` provider. |
| SUP-009 | Mistral AI | Engineering | Mistral AI OpenAI-compatible API (api.mistral.ai). | — | — | — | Candidate | European provider. |
| SUP-010 | DeepSeek | Engineering | DeepSeek OpenAI-compatible API (api.deepseek.com). | — | — | — | Candidate | |
| SUP-011 | Cohere | Engineering | Cohere compatibility API (api.cohere.com/compatibility/v1). | — | — | — | Candidate | |
| SUP-012 | xAI | Engineering | xAI OpenAI-compatible API (api.x.ai). | — | — | — | Candidate | Grok models. |
| SUP-013 | Perplexity | Engineering | Perplexity OpenAI-compatible API (api.perplexity.ai). | — | — | — | Candidate | |
| SUP-014 | Together AI | Engineering | Together AI OpenAI-compatible API (api.together.ai). | — | — | — | Candidate | |
| SUP-015 | Fireworks AI | Engineering | Fireworks AI OpenAI-compatible API (api.fireworks.ai/inference/v1). | — | — | — | Candidate | |
| SUP-016 | Groq | Engineering | Groq OpenAI-compatible API (api.groq.com/openai/v1). | — | — | — | Candidate | Low-latency inference. |
| SUP-017 | Cerebras | Engineering | Cerebras OpenAI-compatible API (api.cerebras.ai). | — | — | — | Candidate | Low-latency inference. |
| SUP-018 | SambaNova | Engineering | SambaNova OpenAI-compatible API (api.sambanova.ai). | — | — | — | Candidate | |
| SUP-019 | Hugging Face | Engineering | Hugging Face inference router (router.huggingface.co). Also model/asset downloads from huggingface.co. | — | — | — | Candidate | Model catalog and embedding/classifier downloads; assess data residency of Hub downloads. |
| SUP-020 | OpenRouter | Engineering | OpenRouter aggregated model gateway (openrouter.ai/api/v1). | — | — | — | Candidate | Aggregator — sub-processors vary by routed model. |
| SUP-021 | NVIDIA NIM | Engineering | NVIDIA NIM inference API (integrate.api.nvidia.com). | — | — | — | Candidate | |
| SUP-022 | DeepInfra | Engineering | DeepInfra OpenAI-compatible API (api.deepinfra.com). | — | — | — | Candidate | |
| SUP-023 | FriendliAI | Engineering | FriendliAI serverless API (api.friendli.ai/serverless/v1). | — | — | — | Candidate | |
| SUP-024 | MiniMax | Engineering | MiniMax native API (api.minimax.io). | — | — | — | Candidate | |
| SUP-025 | Moonshot AI | Engineering | Moonshot OpenAI-compatible API (api.moonshot.ai). | — | — | — | Candidate | |
| SUP-026 | DashScope (Alibaba) | Engineering | DashScope international OpenAI-compatible mode (dashscope-intl.aliyuncs.com). | — | — | — | Candidate | Alibaba Cloud. |
| SUP-027 | Baidu Qianfan | Engineering | Baidu Qianfan OpenAI-compatible API (api.baiduqianfan.ai). | — | — | — | Candidate | |
| SUP-028 | Baidu AI Studio | Engineering | Baidu AI Studio LLM API (aistudio.baidu.com). | — | — | — | Candidate | |
| SUP-029 | Volcengine Ark | Engineering | Volcengine (ByteDance) Ark API (ark.cn-beijing.volces.com). Native protocol. | — | — | — | Candidate | |
| SUP-030 | Xiaomi MiMo API | Engineering | Xiaomi MiMo native API (api.xiaomimimo.com). | — | — | — | Candidate | |
| SUP-031 | Z.ai | Engineering | Z.ai OpenAI-compatible API (api.z.ai). | — | — | — | Candidate | |
| SUP-032 | StepFun | Engineering | StepFun OpenAI-compatible API (api.stepfun.ai). | — | — | — | Candidate | |
| SUP-033 | Novita AI | Engineering | Novita AI OpenAI-compatible API (api.novita.ai). | — | — | — | Candidate | |
| SUP-034 | Reka AI | Engineering | Reka AI OpenAI-compatible API (api.reka.ai). | — | — | — | Candidate | |
| SUP-035 | Sakana AI | Engineering | Sakana AI OpenAI-compatible API (api.sakana.ai). | — | — | — | Candidate | |
| SUP-036 | Sarvam AI | Engineering | Sarvam AI OpenAI-compatible API (api.sarvam.ai). | — | — | — | Candidate | |
| SUP-037 | Upstage | Engineering | Upstage native API (api.upstage.ai). | — | — | — | Candidate | |
| SUP-038 | Writer | Engineering | Writer OpenAI-compatible API (api.writer.com). | — | — | — | Candidate | |
| SUP-039 | Nebius AI Studio | Engineering | Nebius AI Studio OpenAI-compatible API (api.studio.nebius.com). | — | — | — | Candidate | |
| SUP-040 | Featherless AI | Engineering | Featherless AI OpenAI-compatible API (api.featherless.ai). | — | — | — | Candidate | |
| SUP-041 | Celeris | Engineering | Celeris inference API (inference.celeris.ai). | — | — | — | Candidate | |
| SUP-042 | Inception | Engineering | Inception OpenAI-compatible API (api.inceptionlabs.ai). | — | — | — | Candidate | |
| SUP-043 | Aion Labs | Engineering | Aion Labs OpenAI-compatible API (api.aionlabs.ai). | — | — | — | Candidate | |
| SUP-044 | Agnes AI | Engineering | Agnes AI OpenAI-compatible API (apihub.agnes-ai.com). | — | — | — | Candidate | |
| SUP-045 | Apodex AI | Engineering | Apodex AI OpenAI-compatible API (api.apodex.ai). | — | — | — | Candidate | |
| SUP-046 | CometAPI | Engineering | CometAPI OpenAI-compatible gateway (api.cometapi.com). | — | — | — | Candidate | Aggregator. |
| SUP-047 | CompactifAI | Engineering | CompactifAI OpenAI-compatible API (api.compactif.ai). | — | — | — | Candidate | |
| SUP-048 | Cloudflare Workers AI | Engineering | Cloudflare Workers AI model inference. OpenAI-compatible. | — | — | — | Candidate | Base URL is account-specific. |
| SUP-049 | Vercel AI Gateway | Engineering | Vercel AI Gateway (ai-gateway.vercel.sh). OpenAI-compatible. | — | — | — | Candidate | Aggregator. |
| SUP-050 | Redis (managed cache) | Engineering | Managed Redis cache service backing response cache, if deployed as SaaS (e.g. Redis Cloud). | — | — | — | Candidate | Only if not self-hosted. Dependency: redis/go-redis. |
| SUP-051 | Valkey (managed cache) | Engineering | Managed Valkey cache service, if deployed as SaaS. | — | — | — | Candidate | Only if not self-hosted. Dependency: valkey-io/valkey-glide. |
| SUP-052 | Milvus / Zilliz Cloud | Engineering | Managed vector store service backing knowledge bases, if deployed as Zilliz Cloud. | — | — | — | Candidate | Only if not self-hosted. Dependency: milvus-io/milvus-sdk-go. |
| SUP-053 | Qdrant Cloud | Engineering | Managed Qdrant vector store, if deployed as SaaS. | — | — | — | Candidate | Only if not self-hosted. Dependency: qdrant/go-client. |
| SUP-054 | PostgreSQL (managed DB) | Engineering | Managed PostgreSQL storing router replay records (config: store_backend=postgres). | — | — | — | Candidate | Only if not self-hosted. Dependency: lib/pq. |
| SUP-055 | OpenTelemetry / OTLP backend | Engineering | Managed OTLP telemetry backend (e.g. Honeycomb, Datadog, Grafana Cloud) receiving traces. | — | — | — | Candidate | Only if exporter enabled. Dependency: go.opentelemetry.io/otel. |
| SUP-056 | Sentry | Engineering | Sentry error tracking service, if SDK enabled in runtime. | — | — | — | Candidate | Only if activated. Dependency: getsentry/sentry-go present. |

---

## Changelog

| Version | Date | Owner | Approver | Changes |
|---------|------|-------|----------|---------|
| 1.0 | TBD | COO | CEO | Initial version |
| 1.1 | TBD | ISMS Owner | ISMS Owner | Seeded third-party LLM API providers and supporting SaaS services from the vLLM Semantic Router provider catalogue. All entries marked Candidate pending supplier security review per supplier_security_review_template.md. |
