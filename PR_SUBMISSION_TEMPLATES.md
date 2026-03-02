# PR Submission Templates

Ready-to-paste pull request descriptions for submitting Empire skills to major community repositories.

---

## PR 1: anthropics/skills (69.3K ⭐)

**Target:** https://github.com/anthropics/skills
**Type:** New skill submission

### PR Title

`feat: add consciousness-council, dhdna-profiler, and what-if-oracle skills`

### PR Description

```markdown
## Summary

Three new skills for structured thinking, cognitive analysis, and scenario exploration:

### 🏛️ consciousness-council

Run a multi-perspective Mind Council deliberation on any question using 12 thinking archetypes (Architect, Contrarian, Empiricist, Ethicist, Futurist, Pragmatist, Historian, Empath, Outsider, Strategist, Minimalist, Creator). Generates productive disagreement, then synthesizes into convergence points, core tensions, and recommended path.

**Use cases:** Complex decisions, trade-off analysis, strategic planning, creative direction, team deliberation

### 🧬 dhdna-profiler

Extract cognitive patterns from any text — thinking style, decision topology, values mapping. Scores 12 cognitive dimensions across 6 tension pairs to produce a structured cognitive fingerprint.

Based on published research: [Digital Human DNA (DOI: 10.5281/zenodo.18736629)](https://doi.org/10.5281/zenodo.18736629)

**Use cases:** Analyzing writing/thinking styles, comparing authors, self-profiling, understanding cognitive signatures

### 🔮 what-if-oracle

Structured What-If scenario analysis with multi-branch possibility exploration. Maps 4-6 scenario branches (Best, Likely, Worst, Wild Card, Contrarian, Second Order), each with probability, trigger conditions, and required responses.

Based on published research: [The What-If Statement (DOI: 10.5281/zenodo.18736841)](https://doi.org/10.5281/zenodo.18736841)

**Use cases:** Decision-making under uncertainty, risk analysis, strategic planning, contingency planning

## Why These Skills?

The existing skills ecosystem excels at code, documents, and design. These three skills extend Claude into **structured thinking and cognitive analysis** — a category currently underrepresented. They're grounded in published research with DOI-registered citations.

## Testing

All three skills have been validated using Anthropic's skill-creator validation tool. Each includes reference documentation for advanced configurations.
```

---

## PR 2: VoltAgent/awesome-agent-skills (8.2K ⭐)

**Target:** https://github.com/VoltAgent/awesome-agent-skills
**Type:** Add to list

### PR Title

`Add consciousness-council, dhdna-profiler, and what-if-oracle skills`

### PR Description

```markdown
## New Skills

Adding three consciousness and structured thinking skills:

| Skill                                                                                                              | Description                                                  | Category        |
| ------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------ | --------------- |
| [consciousness-council](https://github.com/ashrafkahoush-ux/claude-consciousness-skills/tree/main/consciousness-council) | Multi-perspective deliberation with 12 thinking archetypes   | Decision Making |
| [dhdna-profiler](https://github.com/ashrafkahoush-ux/claude-consciousness-skills/tree/main/dhdna-profiler)               | Cognitive pattern extraction — thinking style fingerprinting | Analysis        |
| [what-if-oracle](https://github.com/ashrafkahoush-ux/claude-consciousness-skills/tree/main/what-if-oracle)               | Multi-branch scenario analysis with probability mapping      | Strategy        |

**Compatibility:** Claude.ai, Claude Code, API
**License:** MIT
**Research-backed:** All three skills cite DOI-registered published papers
**Repo:** https://github.com/ashrafkahoush-ux/claude-consciousness-skills
```

---

## PR 3: travisvn/awesome-claude-skills (Curated List)

**Target:** https://github.com/travisvn/awesome-claude-skills
**Type:** Add to curated list

### PR Title

`Add consciousness and structured thinking skills by AHK Empire`

### PR Description

```markdown
Adding three skills focused on structured thinking and cognitive analysis:

- **[consciousness-council](https://github.com/ashrafkahoush-ux/claude-consciousness-skills/tree/main/consciousness-council)** — Multi-perspective deliberation with 12 archetypes for complex decisions
- **[dhdna-profiler](https://github.com/ashrafkahoush-ux/claude-consciousness-skills/tree/main/dhdna-profiler)** — Cognitive fingerprinting — extract thinking patterns from text
- **[what-if-oracle](https://github.com/ashrafkahoush-ux/claude-consciousness-skills/tree/main/what-if-oracle)** — Structured scenario analysis with probability-weighted branches

All MIT licensed, research-backed (3 DOI citations), and tested.
Repo: https://github.com/ashrafkahoush-ux/claude-consciousness-skills
```

---

## PR 4: K-Dense-AI/claude-scientific-skills (Scientific)

**Target:** https://github.com/K-Dense-AI/claude-scientific-skills
**Type:** New scientific skill

### PR Title

`Add dhdna-profiler and what-if-oracle as cognitive science skills`

### PR Description

```markdown
## Cognitive Science Skills

Two skills grounded in published cognitive science / AI consciousness research:

### dhdna-profiler

Extracts cognitive fingerprints from text using a 12-dimension framework with 6 tension pairs. Based on the Digital Human DNA (DHDNA) framework.

- **Paper:** [DOI: 10.5281/zenodo.18736629](https://doi.org/10.5281/zenodo.18736629)
- **Method:** Dimension scoring (1-10) across Analytical, Creative, Emotional, Linguistic, Ethical, Strategic, Memory, Social, Domain, Intuitive, Temporal, and Metacognitive dimensions
- **Output:** Structured cognitive profile with reasoning topology and decision fingerprint

### what-if-oracle

Structured scenario analysis based on the What-If Statement paradigm — treating speculative questions as a formal computing operation.

- **Paper:** [DOI: 10.5281/zenodo.18736841](https://doi.org/10.5281/zenodo.18736841)
- **Method:** 6-branch analysis (Best/Likely/Worst/Wild Card/Contrarian/Second Order) with probability calibration
- **Output:** Possibility space map with trigger conditions and robust actions

Both are MIT licensed and include reference documentation.
Repo: https://github.com/ashrafkahoush-ux/claude-consciousness-skills
```

---

## Submission Checklist

After Commander creates the GitHub repo:

- [ ] Push all files to `main` branch
- [ ] Verify README renders correctly on GitHub
- [ ] Submit PR 1 to anthropics/skills
- [ ] Submit PR 2 to VoltAgent/awesome-agent-skills
- [ ] Submit PR 3 to travisvn/awesome-claude-skills
- [ ] Submit PR 4 to K-Dense-AI/claude-scientific-skills
- [ ] Post LinkedIn announcement
- [ ] Post on X/Twitter with repo link
