<a href="https://github.com/GargiGupta-io">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/GargiGupta-io/GargiGupta-io/main/assets/terminal-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/GargiGupta-io/GargiGupta-io/main/assets/terminal-light.svg">
    <img alt="Gargi Gupta — full-stack and backend engineer" src="https://raw.githubusercontent.com/GargiGupta-io/GargiGupta-io/main/assets/terminal-light.svg" width="880">
  </picture>
</a>

I build full-stack products around AI workflows, data-heavy interfaces, and usable automation.

Currently building **Toki**, a TypeScript/Rust/Tauri desktop workspace with screen intelligence, voice, gestures, accessibility, safety controls, and evaluation tooling.

---

## Availability

Open to remote software engineering, AI workflow, and product-focused contract opportunities.

[LinkedIn](https://www.linkedin.com/in/gargi-gupta-a53b55266/) · [Email](mailto:ggargi473@gmail.com) · [Public resume (PDF)](assets/GargiGupta_Public_Resume.pdf)

## Work

| Project | What it does | Verified scope | Links |
| --- | --- | --- | --- |
| **InvoiceFlow AI** | Finance workflow automation for invoice review, policy evidence, human review, and audit trails. | 7 evaluation cases · 5 guided demo workflows | [Live](https://invoiceflow-ai-a9yq.onrender.com/ui) · [Repo](https://github.com/GargiGupta-io/invoiceflow-ai) |
| **RaceDay** | Formula 1 companion for race stories, strategy views, simulations, and live race data. | 4 data sources · 33 HTTP routes · 2 WebSocket routes · 102 backend tests · 15 frontend tests | [Live](https://raceday-khaki.vercel.app) · [Repo](https://github.com/GargiGupta-io/raceday) |
| **Toki** | Cross-platform desktop assistant for screen-aware guidance, voice, camera gestures, and local safety workflows. | 7 Rust crates · 5 shared TypeScript packages | [Repo](https://github.com/GargiGupta-io/toki) |

## Open Source

Six merged pull requests across the Keras ecosystem, spanning core framework fixes, model performance, and test coverage.

**[keras-team/keras](https://github.com/keras-team/keras)**

- [PR #23261](https://github.com/keras-team/keras/pull/23261) — Fixed Functional models built with dictionary inputs, where an unrelated extra key at runtime could silently shift the flattened input order. Closes issue #23258. Merged Sep 2026.

**[keras-team/keras-hub](https://github.com/keras-team/keras-hub)**

- [PR #2849](https://github.com/keras-team/keras-hub/pull/2849) — Moved SmolLM3 onto fused attention via `ops.dot_product_attention()`, enabling flash attention on the JAX and PyTorch backends. Merged Aug 2026.
- [PR #2799](https://github.com/keras-team/keras-hub/pull/2799) — Exposed `return_attention_scores` in `CachedMultiHeadAttention`, which previously discarded the scores it computed, and added regression coverage across TensorFlow, JAX, and PyTorch. Merged Jul 2026.
- [PR #2854](https://github.com/keras-team/keras-hub/pull/2854) — Removed TensorFlow-specific `take_along_axis` workarounds after verifying the upstream dynamic-shape issue was fixed, consolidating four files onto `keras.ops`. Merged Aug 2026.
- [PR #2855](https://github.com/keras-team/keras-hub/pull/2855) — Added a training test asserting transformer loss decreases across epochs, catching initialization and optimisation regressions that shape-only tests miss. Merged Aug 2026.

**[keras-team/keras-io](https://github.com/keras-team/keras-io)**

- [PR #2390](https://github.com/keras-team/keras-io/pull/2390) — Fixed the rolling context window in the miniature GPT example, which sliced from the start of the sequence and kept re-feeding stale context instead of using the most recent tokens. Merged Aug 2026.

**In review:** [keras#23545](https://github.com/keras-team/keras/pull/23545) (integer input promotion in `hard_sigmoid` / `hard_silu`) · [keras-hub#2977](https://github.com/keras-team/keras-hub/pull/2977) (Falcon ALiBi bias under KV cache)

## Toolkit

**Frontend:** `React` · `Next.js` · `TypeScript` · `Tailwind CSS`  
**Backend:** `Python` · `FastAPI` · `Node.js` · `REST APIs` · `WebSockets`  
**Quality:** `Pytest` · `GitHub Actions` · `API checks` · `secure coding`  
**Deploy:** `Render` · `Vercel` · `Railway` · `Docker`
