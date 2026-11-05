<p align="center">
  <a href="https://tokport.io/?utm_source=github&utm_medium=org_profile">
    <img src="https://tokport.io/opengraph-image?v=2" alt="TokPort — Affordable Image & Video Generation API" width="720">
  </a>
</p>

<h3 align="center">One OpenAI-compatible API for image & video generation</h3>

<p align="center">
  GPT Image · Nano Banana · Seedream · Seedance · Kling · Qwen Image · Wan · HappyHorse · MiniMax
</p>

<p align="center">
  <a href="https://tokport.io/?utm_source=github&utm_medium=org_profile"><b>🌐 tokport.io</b></a> ·
  <a href="https://tokport.io/docs?utm_source=github&utm_medium=org_profile">Docs</a> ·
  <a href="https://tokport.io/pricing?utm_source=github&utm_medium=org_profile">Pricing</a> ·
  <a href="https://tokport.io/models?utm_source=github&utm_medium=org_profile">Models</a> ·
  <a href="https://tokport.io/register?utm_source=github&utm_medium=org_profile">Get an API key →</a>
</p>

---

**[TokPort](https://tokport.io/?utm_source=github&utm_medium=org_profile)** is a pay-as-you-go API gateway for the latest image and video models. Use the OpenAI SDK you already have: change the base URL and you can call 30+ models from OpenAI, Google, ByteDance, Alibaba, Kuaishou, xAI and more.

- **OpenAI-compatible:** `/v1/images/generations`, `/v1/images/edits` and `/v1/videos` follow the OpenAI schema
- **Transparent pricing:** prepaid USD balance, billed per image, per second of video or per clip. [See live rates](https://tokport.io/pricing?utm_source=github&utm_medium=org_profile)
- **One key, every model:** switch models by changing a single string

## Quickstart

```bash
curl https://api.tokport.io/v1/images/generations \
  -H "Authorization: Bearer $TOKPORT_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{"model": "gpt-image-2", "prompt": "a lighthouse at dusk, watercolor", "size": "1024x1024"}'
```

```python
from openai import OpenAI

client = OpenAI(base_url="https://api.tokport.io/v1", api_key="YOUR_TOKPORT_KEY")
image = client.images.generate(model="seedream-5-pro", prompt="a lighthouse at dusk, watercolor")
```

Create a key at **[tokport.io/register](https://tokport.io/register?utm_source=github&utm_medium=org_profile)**. Then read the [quickstart](https://tokport.io/docs?utm_source=github&utm_medium=org_profile), the [SDK guides](https://tokport.io/docs/clients?utm_source=github&utm_medium=org_profile) or the [MCP setup](https://tokport.io/docs/mcp?utm_source=github&utm_medium=org_profile).

## Popular models

| Image | Video |
| --- | --- |
| [GPT Image 2](https://tokport.io/models/gpt-image-2?utm_source=github&utm_medium=org_profile) | [Seedance 2.5](https://tokport.io/models/seedance-2-5?utm_source=github&utm_medium=org_profile) |
| [Nano Banana 3 Pro](https://tokport.io/models/nano-banana-3-pro?utm_source=github&utm_medium=org_profile) | [Seedance 2.0](https://tokport.io/models/seedance-2-0?utm_source=github&utm_medium=org_profile) |
| [Seedream 5 Pro](https://tokport.io/models/seedream-5-pro?utm_source=github&utm_medium=org_profile) | [Kling 3.0](https://tokport.io/models/kling-3-0?utm_source=github&utm_medium=org_profile) |
| [Qwen Image 3.0](https://tokport.io/models/qwen-image-v3?utm_source=github&utm_medium=org_profile) | [Wan 3.0 Video](https://tokport.io/models/wan3-video?utm_source=github&utm_medium=org_profile) |
| [Grok Image 2.0](https://tokport.io/models/grok-image-2-0?utm_source=github&utm_medium=org_profile) | [HappyHorse 1.1](https://tokport.io/models/happyhorse-1-1?utm_source=github&utm_medium=org_profile) |
| [Z-Image Turbo](https://tokport.io/models/z-image-turbo-fast?utm_source=github&utm_medium=org_profile) | [MiniMax H3](https://tokport.io/models/minimax-h3-768p?utm_source=github&utm_medium=org_profile) |

→ [Full model catalog](https://tokport.io/models?utm_source=github&utm_medium=org_profile) · [Compare gateways & models](https://tokport.io/compare?utm_source=github&utm_medium=org_profile) · [Use cases](https://tokport.io/use-cases?utm_source=github&utm_medium=org_profile)

## Free tools

- [Cost calculator](https://tokport.io/tools/cost-calculator?utm_source=github&utm_medium=org_profile): estimate your monthly spend
- [Aspect ratio calculator](https://tokport.io/tools/aspect-ratio-calculator?utm_source=github&utm_medium=org_profile)
- [Prompt generator](https://tokport.io/tools/prompt-generator?utm_source=github&utm_medium=org_profile)

## For AI agents & LLMs

- [`llms.txt`](https://tokport.io/llms.txt): a machine-readable overview of every model and endpoint
- [OpenAPI spec](https://tokport.io/api/openapi): covers all models

---

<p align="center"><a href="https://tokport.io/?utm_source=github&utm_medium=org_profile"><b>tokport.io</b></a>: affordable image & video generation API</p>
