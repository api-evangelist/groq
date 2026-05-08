# Groq (groq)

Groq builds custom Language Processing Unit (LPU) silicon optimized for low-latency LLM inference. The GroqCloud API serves popular open models (Llama, GPT OSS, Whisper, Orpheus) at industry-leading tokens-per-second with an OpenAI-compatible interface.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/groq/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=groq-api-evangelist&utm_content=repo)

## Type

- **x-type:** company

## Tags:

 - AI, LLM, Inference, LPU, Low Latency

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

| API | Description |
|---|---|
| Groq Chat Completions API | OpenAI-compatible chat across Llama / GPT OSS / Mixtral / Gemma on LPU silicon. |
| Groq Reasoning API | Reasoning-capable models with chain-of-thought support. |
| Groq Vision API | Image understanding and OCR via vision-capable chat models. |
| Groq Speech-to-Text API | OpenAI-compatible Whisper transcription on LPU. |
| Groq Text-to-Speech API | TTS via Orpheus and other voices, billed per 1M characters. |
| Groq Content Moderation API | Llama Guard safety classifier. |
| Groq Batch API | Async batch inference at 50% discount. |
| Groq Flex Processing API | Higher-throughput, relaxed-latency tier at reduced cost. |
| Groq Files API | File upload/management for batch and other workflows. |
| Groq Models API | Lists available models with metadata and pricing tags. |
| Groq Tools API | Built-in tools: Web Search, Browser Automation, Code Execution, Wolfram Alpha. |
| Groq LoRA Inference API | Serves customer LoRA adapters on supported base models. |
| Groq Prompt Caching | Automatic prompt caching with 50% discount on cached input tokens. |

## Common Properties

- [Website](https://groq.com/)
- [Documentation](https://console.groq.com/docs)
- [Plans](plans/groq-plans-pricing.yml) — API Commons Plans 0.1
- [RateLimits](rate-limits/groq-rate-limits.yml) — API Commons Rate Limits 0.1
- [FinOps](finops/groq-finops.yml) — FOCUS-aligned FinOps Framework 1.0

## Artifacts

| Artifact | Path | Notes |
|---|---|---|
| Plans | `plans/groq-plans-pricing.yml` | Pay-as-you-go per-token / per-character / per-hour rates + Batch / Flex / Enterprise. |
| Rate Limits | `rate-limits/groq-rate-limits.yml` | Per-account RPM/RPD/TPM/TPD/ASH/ASD enforced via 429. Per-model values pending. |
| FinOps | `finops/groq-finops.yml` | FOCUS-aligned, usage-based: tokens (input/cached/output), TTS chars, STT hours, tool calls/hours, batch, flex. |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
