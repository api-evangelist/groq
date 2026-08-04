# Groq (groq)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
