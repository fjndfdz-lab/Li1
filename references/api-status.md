# Seedance 2.0 API and Platform Status

last_verified: 2026-05-27
confidence: public-source snapshot as of the verification date; not a guarantee of access, pricing, model IDs, upload limits, authorization behavior, or regional availability on every surface

## Confirmed From Public Sources

- ByteDance's official Seedance 2.0 page describes a unified multimodal audio-video architecture that supports text, image, audio, and video inputs.
- ByteDance's launch post says Seedance 2.0 can use up to 9 images, 3 video clips, 3 audio clips, plus natural-language instructions.
- Official material says references can guide visual composition, camera language, motion rhythm, visual effects, and sound characteristics.
- Official material describes video extension and editing as supported creative workflows.
- Official material describes 15-second multi-shot audio-video output and dual-channel audio.
- The arXiv model card is useful for model-family context, including 4-15 second audio-video generation, native 480p/720p framing in the paper, and a Fast variant.
- Volcengine/Ark docs publish video-generation API navigation for create, query, list, and cancel/delete task flows, but exact schemas, prices, model IDs, regions, and limits must be rechecked live.
- Partner workflow docs such as ComfyUI expose T2V, R2V, and FLF2V workflow vocabulary, but those docs are surface-specific.

## Operational Wording

Use this wording unless newer primary sources say otherwise:

> As of 2026-05-27, public ByteDance sources describe Seedance 2.0 as a unified multimodal audio-video generation model with text, image, audio, and video inputs. Official launch material says references can include up to 9 images, 3 video clips, and 3 audio clips, and can guide composition, camera language, motion rhythm, visual effects, and sound. Volcengine/Ark and BytePlus/ModelArk surfaces publish video-generation documentation, but access, model IDs, pricing, file limits, regional availability, and portrait authorization remain surface-specific and must be rechecked before production use.

## Model Naming Rule

- Use `Seedance 2.0` for the official video model line.
- Use `Seedance 2.0 Fast` only when the active surface exposes a Fast variant.
- Do not call `Seedance 2.0 Pro` the official video-model name without a current source. Treat it as ambiguous wrapper or community wording.
- Do not confuse `Seed2.0 Pro` or Doubao/Seed general model names with Seedance video generation.

See [`model-name-map.md`](model-name-map.md).

## Claim Boundaries

- Say that API availability, pricing, model IDs, upload limits, entitlement rules, rate limits, and regional availability must be checked against current primary sources.
- Avoid claiming that an API is globally available or unavailable unless a current primary source says so.
- Avoid claiming that face or portrait uploads are universally supported or universally blocked unless a current primary source says so.
- Separate model capability from product-surface behavior. Dreamina/Jimeng, Doubao, Volcengine/Ark, BytePlus/ModelArk, ComfyUI, and third-party wrappers can differ.
- Treat third-party wrapper prices and model aliases as wrapper-specific, not official.

## Known Limit Categories

Official/provider material and field observations point to these areas as fragile:

- detail stability,
- hyper-realism,
- dynamic vitality,
- multi-subject consistency,
- text rendering,
- complex editing,
- audio distortion,
- multi-speaker lip-sync,
- product/logo preservation,
- real-person authorization and surface gating.

## Real-Person, Portrait, and Voice Rule

Real-person face, portrait, and voice workflows require authorization, legal/ethical compliance, and platform-specific support. Do not infer permission from an uploaded asset. Do not help imitate a public figure, private person, celebrity, or voice without a clearly authorized workflow that complies with applicable rules and user consent requirements.

## Primary Sources To Recheck

- https://seed.bytedance.com/en/seedance2_0
- https://seed.bytedance.com/en/blog/seedance-2-0-official-launch
- https://arxiv.org/abs/2604.14148
- https://www.volcengine.com/docs/82379/1330310?redirect=1&lang=zh
- https://www.volcengine.com/docs/82379/1520757?lang=zh
- https://docs.byteplus.com/en/docs/ModelArk/2291680
- https://docs.comfy.org/zh/tutorials/partner-nodes/bytedance/seedance-2-0
