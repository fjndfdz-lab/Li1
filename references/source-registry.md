# Source Registry

last_verified: 2026-05-27

Use this registry before making factual claims about Seedance 2.0 platform behavior. Prefer primary public sources, attach a verification date, and mark volatile claims as recheck-required. This file is a claim-boundary map, not a guarantee of access on every product surface or region.

## Evidence Labels

| Label | Meaning | Required wording |
|---|---|---|
| `confirmed` | Directly visible in a primary public source at the verification date. | `Public sources state... as of [date].` |
| `volatile` | Likely to change by surface, account, region, pricing page, or model update. | `Recheck before giving numbers or promises.` |
| `field-observed` | Repeated creator/practitioner pattern but not official platform truth. | `Field observation, not guaranteed platform behavior.` |
| `unverified` | Plausible but not confirmed by a primary source. | `Requires testing or owner confirmation.` |
| `internal` | Repository guidance derived from this skill package. | `Use as workflow guidance, not external fact.` |

## Primary Source Hierarchy

| Topic | Preferred source | Evidence label | Verification note | Claim boundary |
|---|---|---|---|---|
| Core model capabilities | ByteDance Seedance 2.0 official page: https://seed.bytedance.com/en/seedance2_0 | confirmed | Recheck before release notes, API claims, or marketing copy. | Use for broad public capability framing only. |
| Launch capabilities and known limits | ByteDance Seedance 2.0 official launch post: https://seed.bytedance.com/en/blog/seedance-2-0-official-launch | confirmed | Recheck when discussing multimodal references, editing, audio, and platform examples. | Do not turn launch examples into guaranteed behavior on every surface. |
| Model card and paper | arXiv model card: https://arxiv.org/abs/2604.14148 | confirmed | Useful for model-family context and benchmark caveats. | Provider-authored paper; do not use as current commercial access proof. |
| API tutorial and platform docs | BytePlus ModelArk and Volcengine Ark docs: https://docs.byteplus.com/en/docs/ModelArk/2291680 and https://www.volcengine.com/docs/82379/1520757?lang=zh | volatile | Recheck endpoints, request fields, model IDs, task flow, and pricing before procedural API guidance. | API shape may differ by region, account, or release channel. |
| Model IDs and pricing | Volcengine/BytePlus pricing and model pages | volatile | Always recheck immediately before quoting numbers or IDs. | Never invent price, quota, upload limit, or regional availability. |
| First/last frame workflow | ComfyUI partner docs: https://docs.comfy.org/zh/tutorials/partner-nodes/bytedance/seedance-2-0 | field-observed | Useful for workflow language and FLF2V routing. | Partner surface, not universal model contract. |
| Face, portrait, and voice behavior | Active product surface, official policy, and user authorization | volatile | Recheck current surface behavior and authorization context. | Do not infer consent from a file upload. |
| Community practice | Douyin, Bilibili, CSDN, Reddit, Habr, creator notes, workflow screenshots | field-observed | Use only as practitioner guidance. | Mark as non-official; do not state as model guarantee. |
| Community prompt corpora | YouMind/OpenLab, public prompt galleries, forum collections | field-observed | Mine structure, timing, vocabulary, and failure patterns only after safety classification. | Do not copy unsafe, IP-sensitive, or real-person prompts into active examples. |
| Repository guidance | README, SKILL.md, references, evals | internal | Keep aligned with source registry and API status. | Workflow guidance, not an external source of platform facts. |

## Required Claim Patterns

When answering platform-status questions, say: `As of 2026-05-27, public official sources describe Seedance 2.0 as supporting text, image, audio, and video inputs, including multimodal references for composition, camera language, motion rhythm, visual effects, and sound. Access, pricing, model IDs, upload limits, regions, and authorization behavior remain surface-specific and should be rechecked.`

When answering pricing, quota, upload-limit, model-ID, or regional-availability questions, do not guess. State that those values are volatile and require checking the current official surface.

When answering likeness, portrait, and voice questions, separate three things: technical surface support, rights/authorization, and prompt safety. Do not infer consent from a file upload.

When using community sources, say: `Field observation, not guaranteed platform behavior.`
