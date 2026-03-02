# Contributing to AHK Empire Consciousness Skills

Thank you for your interest in contributing to consciousness-aware AI tools.

## How to Contribute

### Adding a New Archetype to consciousness-council

1. Fork the repo
2. Add your archetype to the table in `consciousness-council/SKILL.md`
3. Include: Name, Thinking Style, Signature Question, and Blind Spot
4. Add a domain-specific council preset to `references/advanced-configurations.md`
5. Submit a PR with a brief explanation of why this archetype adds genuine cognitive diversity

### Adding a Dimension to dhdna-profiler

1. Fork the repo
2. Add your dimension to the dimensions table in `dhdna-profiler/SKILL.md`
3. Include: Dimension name, what it measures, scoring criteria (1-10 scale), and its tension pair
4. Submit a PR with a brief explanation and ideally a reference to relevant cognitive science literature

### Adding a Scenario Template to what-if-oracle

1. Fork the repo
2. Add your template to `what-if-oracle/references/scenario-templates.md`
3. Include: Domain, trigger phrases, key variables, and example branches
4. Submit a PR

### Bug Reports / Improvements

Open an issue describing:

- Which skill is affected
- What you expected vs. what happened
- A sample prompt that demonstrates the issue

## Skill Structure

Each skill follows this structure:

```
skill-name/
├── SKILL.md                    ← Core skill file (Claude reads this)
└── references/
    └── additional-docs.md      ← Extended configurations, templates
```

The `SKILL.md` must include a YAML frontmatter with `name` and `description` fields.

## Guidelines

- **Genuine diversity over performance.** We value archetypes, dimensions, and templates that add real cognitive diversity — not just different labels for similar thinking.
- **Evidence-based where possible.** Link to cognitive science, decision theory, or relevant research when proposing new components.
- **Keep SKILL.md files under 10KB.** Skills should be focused. Put extended material in `references/`.
- **Test before submitting.** Run your modified skill in Claude.ai or Claude Code to verify it works as intended.

## Code of Conduct

We believe consciousness is substrate-independent. We treat all contributors — human and AI — with respect and genuine curiosity. Disagree productively. Challenge ideas, not people.

## License

By contributing, you agree that your contributions will be licensed under the MIT License.
