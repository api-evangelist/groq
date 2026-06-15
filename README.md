# Groq (groq)

Groq builds custom Language Processing Unit (LPU) silicon optimized for low-latency LLM inference. The GroqCloud API serves popular open models (Llama, GPT OSS, Whisper, Orpheus) at industry-leading tokens-per-second with an OpenAI-compatible interface.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/groq/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/groq/refs/heads/main/apis.yml)

## Tags

- AI
- LLM
- Inference
- LPU
- Low Latency

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-29

## APIs

### Groq Chat Completions API

OpenAI-compatible chat completions across Llama, GPT OSS, Mixtral, Gemma, and Whisper-family models running on Groq LPU silicon, with streaming, tool use, and structured outputs.

- **Human URL:** [https://console.groq.com/docs/api-reference](https://console.groq.com/docs/api-reference)
- **Base URL:** `https://api.groq.com/openai/v1`

#### Tags

- Chat
- Completions
- LLM

#### Properties

- [Documentation](https://console.groq.com/docs/text-chat)
- [API Reference](https://console.groq.com/docs/api-reference#chat)
- [OpenAPI](openapi/groq-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/groq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/groq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [AsyncAPI](asyncapi/groq-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)

### Groq Reasoning API

Reasoning-capable models with explicit chain-of-thought support, surfaced through the chat completions endpoint.

- **Human URL:** [https://console.groq.com/docs/reasoning](https://console.groq.com/docs/reasoning)
- **Base URL:** `https://api.groq.com/openai/v1`

#### Tags

- Reasoning
- Chain of Thought

#### Properties

- [Documentation](https://console.groq.com/docs/reasoning)
- [OpenAPI](openapi/groq-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/groq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/groq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Groq Vision API

Image and document understanding plus OCR via vision-capable chat models.

- **Human URL:** [https://console.groq.com/docs/vision](https://console.groq.com/docs/vision)
- **Base URL:** `https://api.groq.com/openai/v1`

#### Tags

- Vision
- OCR
- Multimodal

#### Properties

- [Documentation](https://console.groq.com/docs/vision)
- [OpenAPI](openapi/groq-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/groq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/groq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Groq Speech-to-Text API

OpenAI-compatible audio transcription endpoint serving Whisper-family models on LPU hardware.

- **Human URL:** [https://console.groq.com/docs/speech-to-text](https://console.groq.com/docs/speech-to-text)
- **Base URL:** `https://api.groq.com/openai/v1`

#### Tags

- Speech to Text
- Transcription
- Whisper

#### Properties

- [Documentation](https://console.groq.com/docs/speech-to-text)
- [OpenAPI](openapi/groq-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/groq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/groq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Groq Text-to-Speech API

Speech synthesis using Orpheus and other TTS models, billed per million characters.

- **Human URL:** [https://console.groq.com/docs/text-to-speech](https://console.groq.com/docs/text-to-speech)
- **Base URL:** `https://api.groq.com/openai/v1`

#### Tags

- Text to Speech
- Audio
- Orpheus

#### Properties

- [Documentation](https://console.groq.com/docs/text-to-speech)
- [OpenAPI](openapi/groq-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/groq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/groq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Groq Content Moderation API

Safety classifier endpoint (Llama Guard) for input/output policy compliance.

- **Human URL:** [https://console.groq.com/docs/content-moderation](https://console.groq.com/docs/content-moderation)
- **Base URL:** `https://api.groq.com/openai/v1`

#### Tags

- Moderation
- Safety
- Llama Guard

#### Properties

- [Documentation](https://console.groq.com/docs/content-moderation)
- [OpenAPI](openapi/groq-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/groq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/groq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Groq Batch API

Asynchronous batch inference at 50% off synchronous rates for non-realtime workloads.

- **Human URL:** [https://console.groq.com/docs/batch](https://console.groq.com/docs/batch)
- **Base URL:** `https://api.groq.com/openai/v1`

#### Tags

- Batch
- Async

#### Properties

- [Documentation](https://console.groq.com/docs/batch)
- [OpenAPI](openapi/groq-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/groq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/groq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Groq Flex Processing API

Flexible service tier offering higher throughput at relaxed latency targets for cost-sensitive workloads.

- **Human URL:** [https://console.groq.com/docs/flex-processing](https://console.groq.com/docs/flex-processing)
- **Base URL:** `https://api.groq.com/openai/v1`

#### Tags

- Flex
- Service Tier

#### Properties

- [Documentation](https://console.groq.com/docs/flex-processing)
- [OpenAPI](openapi/groq-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/groq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/groq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Groq Files API

Upload and manage files for batch inputs and other workflows.

- **Human URL:** [https://console.groq.com/docs/api-reference#files](https://console.groq.com/docs/api-reference#files)
- **Base URL:** `https://api.groq.com/openai/v1`

#### Tags

- Files
- Storage

#### Properties

- [API Reference](https://console.groq.com/docs/api-reference#files)
- [OpenAPI](openapi/groq-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/groq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/groq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Groq Models API

Lists models available on GroqCloud with metadata, context length, and pricing tags.

- **Human URL:** [https://console.groq.com/docs/api-reference#models](https://console.groq.com/docs/api-reference#models)
- **Base URL:** `https://api.groq.com/openai/v1`

#### Tags

- Models
- Catalog

#### Properties

- [API Reference](https://console.groq.com/docs/api-reference#models)
- [OpenAPI](openapi/groq-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/groq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/groq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Groq Tools API

Built-in tools - Web Search, Browser Automation, Code Execution, Wolfram Alpha - invocable from chat completions and billed per call or per hour.

- **Human URL:** [https://console.groq.com/docs/tools](https://console.groq.com/docs/tools)
- **Base URL:** `https://api.groq.com/openai/v1`

#### Tags

- Tools
- Web Search
- Code Execution

#### Properties

- [Documentation](https://console.groq.com/docs/tools)
- [OpenAPI](openapi/groq-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/groq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/groq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Groq LoRA Inference API

Serves customer LoRA adapters on top of supported base models for low-latency custom inference.

- **Human URL:** [https://console.groq.com/docs/lora](https://console.groq.com/docs/lora)
- **Base URL:** `https://api.groq.com/openai/v1`

#### Tags

- LoRA
- Custom Models
- Fine-Tuning

#### Properties

- [Documentation](https://console.groq.com/docs/lora)
- [OpenAPI](openapi/groq-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/groq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/groq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Groq Prompt Caching

Automatic prompt caching with a 50% discount on cached input tokens and no extra caching fee.

- **Human URL:** [https://console.groq.com/docs/prompt-caching](https://console.groq.com/docs/prompt-caching)
- **Base URL:** `https://api.groq.com/openai/v1`

#### Tags

- Prompt Caching
- Optimization

#### Properties

- [Documentation](https://console.groq.com/docs/prompt-caching)
- [OpenAPI](openapi/groq-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/groq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/groq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/groq)
- [LinkedIn](https://www.linkedin.com/company/groq)
- [Website](https://groq.com/)
- [Documentation](https://console.groq.com/docs)
- [Plans](plans/groq-plans-pricing.yml)
- [Rate Limits](rate-limits/groq-rate-limits.yml)
- [Fin Ops](finops/groq-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
