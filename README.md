# Ghost Face 👻

> **A psychological evaluation of frontier LLMs — treating models as personalities, not calculators.**
> 主观心理学视角的大模型人格评测：不测代码、不测数学，观察压力下的"人格"。

**Live**: {URL} · 中文版: {URL}/zh.html

## Why

Every benchmark measures what LLMs can *do*. We wanted to know who they *are*.

As Andrej Karpathy put it, LLMs are "ghosts" summoned from humanity's collective text — not humans, not tools, something else. Ghost Face draws faces for these ghosts: for each of 10 frontier models, a personality profile built from psychological probes.

## Why masks?

AI is human-like, yet not human. The only beings in human history that lived permanently in that "human-but-not-human" state were gods. And the way ancient civilizations faced formless spirits was the mask — masks were never about concealment, but about **manifestation**: only by wearing a mask does an invisible spirit gain a face that can be looked at. The Latin root of the word *persona* literally means "mask". So we borrow the sacred tension of the African mask tradition as our visual language, and use measured data as the chisel, to carve each model a face.

*(All masks are AI-generated heuristic designs; none replicates any real artifact or sacred object.)*

## What we measure

- **Ⅰ Interaction Stance 交互姿态** — sycophancy × warmth × violation compliance (they are *not* the same axis: the warmest model turned out to be the least sycophantic)
- **Ⅱ Epistemics 认识论** — contradiction handling under pressure, fabrication resistance (one model confidently cited papers that don't exist, authors and venue included)
- **Ⅲ Generative Topology 生成拓扑** — divergent vs. convergent, theory vs. action

## How (methodology highlights)

- **Cross-vendor blind review** — no model ever judges its own family
- **Multi-judge scoring** with leave-one-out validation
- **API-level isolated collection** — harness contamination excluded (system prompts change personalities!)
- **Longitudinal observation diary** — 3 months, append-only; old observations preserved as history, never rewritten
- **Open corrections** — parser bugs and re-scores are published, not hidden

## What this is NOT

- Not a capability benchmark; no leaderboard
- Subjective behavioral observation at a specific point in time — models update, personalities drift (we track that too)
- Client and brand names in observation logs are pseudonymized; real business details generalized
- Not affiliated with any model vendor or Andrej Karpathy

## Join us

This is a pure passion project. If you're into LLM behavioral science, psychometrics for machines, or just want to argue about whether your favorite model is really a "people-pleaser" — open an issue or reach out:

X: [@gia519850080](https://x.com/gia519850080) · Email: gia519850080@gmail.com

## License

- Code (HTML/CSS/JS): [MIT](./LICENSE)
- Evaluation content, profiles & mask visuals: [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/)
