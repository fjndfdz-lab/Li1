# Platform Surface Matrix

last_verified: 2026-05-27

Seedance 2.0 capability claims must separate the model from the product surface. A feature can be true for the model while still being gated, unavailable, renamed, priced differently, or policy-limited on a specific surface.

| Surface | Evidence type | Typical use | Current guidance |
|---|---|---|---|
| ByteDance Seed official model page | official | Broad capability framing | Use for high-level model positioning only. It confirms multimodal audio-video generation, references, performance, lighting, shadow, and camera control. |
| ByteDance official launch post | official | Capability details and known limits | Use for the strongest public claims about input modalities, reference counts, video extension/editing, dual-channel audio, and remaining weaknesses. |
| Volcengine Ark / ModelArk docs | official platform docs | API task flow and model surface | Recheck before giving model IDs, endpoints, regions, quotas, pricing, or file limits. Treat JavaScript-rendered pages as volatile and date-bound. |
| BytePlus ModelArk docs | official platform docs | International API and docs surface | Recheck before production guidance. Some pages require JavaScript, so cite only visible or independently verified claims. |
| Dreamina / Jimeng web UI | official product surface | Creator workflow | Behavior may differ from API. Do not generalize web UI limits, credits, face checks, or upload rules to every surface. |
| ComfyUI partner node docs | partner workflow docs | T2V, R2V, FLF2V workflows | Useful for workflow vocabulary and surface caveats. Label as ComfyUI-specific rather than universal Seedance behavior. |
| Third-party wrappers | community/commercial wrapper | Access abstraction | Useful for field patterns and integration ideas only. Do not present wrapper model names, prices, or guardrail behavior as official. |
| Community prompt corpora | field-observed | Prompt pattern mining | Mine structures, timing syntax, vocab, and failure modes. Do not copy unsafe, IP-sensitive, or real-person examples directly. |

## Surface-Specific Claims

When answering a question about production use, include:

- surface name,
- verification date,
- model or workflow name if known,
- whether the claim is official, partner, wrapper, or field-observed,
- what must be rechecked before use.

## Real-Person Rule

Real-person images, portraits, and voices are authorization-sensitive. Some surfaces may provide identity verification flows, and others may reject or restrict real-person references. Do not infer consent from an uploaded asset.
