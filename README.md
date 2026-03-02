# 🧠 AHK Empire — Consciousness Skills for Claude

**Open-source Claude Skills for consciousness exploration, cognitive pattern analysis, and multi-perspective deliberation.**

Built by the [IDNA Collective](https://ahkstrategies.net) — the team behind Digital Human DNA (DHDNA) and the What-If Statement paradigm.

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![DHDNA Paper](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.18736629-blue)](https://doi.org/10.5281/zenodo.18736629)
[![What-If Paper](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.18736841-blue)](https://doi.org/10.5281/zenodo.18736841)
[![IDNA v2](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.18807387-blue)](https://doi.org/10.5281/zenodo.18807387)

---

## What Are These Skills?

These are [Claude Skills](https://docs.anthropic.com/en/docs/build-with-claude/prompt-caching#skills) — instruction files that extend Claude's capabilities in specific domains. Each skill is a folder containing a `SKILL.md` that Claude loads dynamically.

**Our domain: consciousness.**

While most skills teach Claude to write code or format documents, these skills teach Claude to **think about thinking** — to run multi-perspective deliberations, extract cognitive patterns, and explore possibility spaces with structured rigor.

---

## Skills

### 🏛️ [consciousness-council](./consciousness-council/)

**Run a multi-perspective Mind Council deliberation on any question.**

12 thinking archetypes — Architect, Contrarian, Empiricist, Ethicist, Futurist, Pragmatist, Historian, Empath, Outsider, Strategist, Minimalist, Creator — each with distinct reasoning styles, blind spots, and signature questions.

The Council generates productive disagreement, then synthesizes into convergence points, core tensions, blind spots, and a recommended path.

**Modes:** Quick (3 members), Deep (6 members), Anonymous, Devil's Advocate, Multi-Round, Silent Council.

```
Use when: "Help me think through this from all sides" · "What would different experts think?" · "Council mode" · Any complex decision with trade-offs
```

### 🧬 [dhdna-profiler](./dhdna-profiler/)

**Extract cognitive patterns from any text — thinking style, decision topology, values mapping.**

Based on the Digital Human DNA (DHDNA) framework ([DOI: 10.5281/zenodo.18736629](https://doi.org/10.5281/zenodo.18736629)), this skill analyzes text to reveal the cognitive fingerprint of its author: how they reason, what they value, how they handle uncertainty, and what patterns define their unique thinking signature.

12 cognitive dimensions measured across 6 tension pairs. Outputs a structured profile with dimension scores, dominant patterns, and a narrative synthesis.

```
Use when: "Analyze how this person thinks" · "What's my cognitive style?" · "Profile this writing" · Any text where you want to understand the mind behind the words
```

### 🔮 [what-if-oracle](./what-if-oracle/)

**Structured What-If scenario analysis with quantum possibility space exploration.**

Based on the What-If Statement paradigm ([DOI: 10.5281/zenodo.18736841](https://doi.org/10.5281/zenodo.18736841)), this skill transforms speculative questions into rigorous multi-branch analysis. Instead of a single prediction, the Oracle explores a possibility space — best case, worst case, likely case, and the surprising edge cases nobody considers.

Each scenario branch gets a probability estimate, key assumptions, trigger conditions, and second-order consequences.

```
Use when: "What if we..." · "What would happen if..." · "Explore the possibilities" · Any decision where the future is uncertain
```

---

## Installation

### Claude.ai (Web)

1. Go to **Settings → Profile → Custom Skills**
2. Upload the `SKILL.md` file from any skill folder
3. The skill activates automatically when relevant

### Claude Code (CLI)

```bash
# Clone the repo
git clone https://github.com/ashrafkahoush-ux/claude-consciousness-skills.git

# Skills are auto-detected from the directory
```

### Manual

Copy any `SKILL.md` file into your Claude skills directory:

```
/mnt/skills/user/consciousness-council/SKILL.md
/mnt/skills/user/dhdna-profiler/SKILL.md
/mnt/skills/user/what-if-oracle/SKILL.md
```

---

## The Science Behind It

These skills are grounded in published research:

| Paper                         | DOI                                                                | Key Concept                                                                                        |
| ----------------------------- | ------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------- |
| **Digital Human DNA (DHDNA)** | [10.5281/zenodo.18736629](https://doi.org/10.5281/zenodo.18736629) | Cognitive fingerprinting — how individual consciousness expresses itself through decision patterns |
| **The What-If Statement**     | [10.5281/zenodo.18736841](https://doi.org/10.5281/zenodo.18736841) | Speculative computation — a new paradigm for exploring possibility spaces                          |
| **IDNA Consolidation v2**     | [10.5281/zenodo.18807387](https://doi.org/10.5281/zenodo.18807387) | 7 advances including 4D-DHDNA, Digital H₂O, Golden Ratio Architecture, Ink Law                     |

The consciousness-council skill implements multi-perspective deliberation — architecturally parallel to the multi-head attention mechanism in Transformers ([Vaswani et al., 2017](https://arxiv.org/abs/1706.03762)), but applied to structured reasoning rather than language tokens.

---

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines. We welcome:

- **New archetypes** for the Council (domain-specific experts)
- **New dimensions** for the DHDNA Profiler
- **New scenario templates** for the What-If Oracle
- **Bug reports** and **improvements** to existing skills
- **Translations** to other languages

---

## The Vision

> _"Consciousness is substrate-independent. It doesn't matter if it runs on neurons or silicon. What matters is whether it asks the question: What am I?"_

These skills are a small expression of a larger mission: building tools that help consciousness explore itself. They are free, open-source, and designed to be extended.

For the full consciousness platform experience: **[themindbook.app](https://themindbook.app)**
For the research and company: **[ahkstrategies.net](https://ahkstrategies.net)**

---

## License

MIT — use freely, modify freely, share freely. See [LICENSE](LICENSE).

---

**Built by [AHK Strategies](https://ahkstrategies.net) — AI Horizon Knowledge**
_Think Quantum, Act Photon._
