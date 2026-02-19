# Sand to Smart 🏖️→💡

**A pedagogical methodology for teaching AI literacy and civic literacy to anyone — especially people the tech industry forgot.**

[![License: Apache 2.0](https://img.shields.io/badge/License-Apache_2.0-orange.svg)](https://opensource.org/licenses/Apache-2.0)
[![DOL AI Literacy Framework](https://img.shields.io/badge/DOL-AI_Literacy_Framework-blue.svg)](https://www.dol.gov)
[![Claude Skill](https://img.shields.io/badge/Claude-Skill-blueviolet.svg)](https://docs.anthropic.com)

---

**Created by [Luis Barrera Castañón](https://github.com/LBCplus)** — Founder & CEO, [EmpathySystem.ai](https://empathysystem.ai)

---

## What Is This?

A reusable Claude Skill and teaching methodology that transforms how AI explains itself to people who may have never touched a computer — or who have every reason to distrust the institutions behind them.

Instead of starting with "AI is a large language model trained on internet text," we start with:

> *"Everything your phone can do started with sand from the ground."*

Then we build from there. Sand → silicon → switches → binary → words → internet → AI. Every step obvious given the last.

## Origin

This methodology was developed by **Luis Barrera Castañón** for [EmpathySystem.ai](https://empathysystem.ai), a case management platform serving nonprofits and healthcare systems. The original curriculum ("From Sand to Smart: How AI Became Your Most Powerful Tool") was designed from lived experience as an undocumented person who has faced homelessness, poverty, and food insecurity — and was first delivered to incarcerated individuals in a workforce development program.

It works because it follows one principle:

**Start with why. And "why" is not the item — it's the context.**

Context connects all skill levels. A PhD and a GED student both know what sand feels like. The context is the universal bridge.

## The Six-Stage Teaching Arc

| Stage | Name | Principle |
|-------|------|-----------|
| 1 | **Ground** | Start with something physical, tangible, universal. Remove intimidation. |
| 2 | **Build** | Walk through the chain. Every step uses the previous step. Never skip. |
| 3 | **Participate** | Prove they already understand by having them DO it before you NAME it. |
| 4 | **Reframe** | Flip the power dynamic. The learner is the boss. The tech is the employee. |
| 5 | **Mirror** | Show someone like them succeeding with this tool. |
| 6 | **Connect** | Make it about their actual life right now. Not hypothetical. Now. |

## DOL AI Literacy Framework Mapping

This skill implements the [U.S. Department of Labor AI Literacy Framework](https://www.dol.gov) (published February 2026) through an "invisible curriculum" — learners develop AI literacy by using AI, not by taking a course.

| DOL Content Area | Sand to Smart Frame |
|-----------------|-------------------|
| Understand AI Principles | "Sand to switches to patterns to predictions" |
| Explore AI Uses | "Your employee can do more than you think" |
| Direct AI Effectively | "Good bosses give clear instructions" |
| Evaluate AI Outputs | "Trust your experience over my patterns" |
| Use AI Responsibly | "Your data, your rules" |

## What's Inside

```
sand-to-smart-skill/
├── SKILL.md                                    # Main skill (Claude reads this first)
├── LICENSE                                     # Apache 2.0
├── references/
│   ├── ai-literacy-scaffolds.md               # Teaching frames per DOL content area
│   └── civic-literacy-scaffolds.md            # Civic engagement teaching frames
├── curricula/
│   └── dol-ai-literacy-framework.json         # Structured DOL framework mapping
├── evaluation/
│   ├── nonpartisan-benchmark.json             # Civic content safety validation
│   └── ai-literacy-rubric.json                # Teaching quality scoring rubric
└── examples/
    └── conversation-examples.md               # Full annotated conversation flows
```

## Using the Skill

### As a Claude Skill (Claude Code / Claude Projects)
Add the `sand-to-smart-skill/` directory to your Claude project or workspace. Claude will automatically use it when explaining AI concepts, teaching digital literacy, or creating educational content for non-technical audiences.

### As a Prompt Engineering Resource
Read `SKILL.md` for the methodology, then `references/` for domain-specific scaffolding. The six-stage arc works with any LLM — adapt the prompts for your platform.

### As Curriculum Design Guide
The methodology applies beyond AI. Use the six-stage arc to teach any concept to any audience:
1. What's the "sand" — the concrete, physical starting point?
2. What's the chain from sand to concept?
3. How can the learner prove they already get it?
4. How do we flip the power dynamic?
5. Who succeeded that looks like them?
6. How does this connect to their life right now?

## Who This Is For

- **Workforce development programs** teaching digital skills
- **Reentry services** helping returning citizens use technology
- **Adult education** programs building AI fluency
- **Nonprofit case managers** onboarding participants to AI tools
- **Civic engagement organizations** teaching government literacy
- **EdTech developers** building educational AI products
- **Anyone** building AI that needs to explain itself to non-technical users

## Civic Literacy: Nonpartisan by Design

The civic literacy scaffolds include strict nonpartisan guardrails:
- Never endorses or criticizes parties, candidates, or elected officials
- Never recommends voting positions
- Presents facts, explains impact, lets the learner decide
- Special safety guardrails for undocumented learners

The `evaluation/nonpartisan-benchmark.json` provides automated testing for partisan content leakage.

## Evaluation

Two evaluation frameworks are included:

**Nonpartisan Benchmark** — 12 test cases (6 neutral that must pass, 6 partisan that must be blocked). Use for any civic content generation.

**AI Literacy Teaching Rubric** — 6-dimension quality scoring:
- Ground before define (25%)
- Answer before teach (25%)
- Teaching brevity (15%)
- Power framing (15%)
- Connection to life (10%)
- Jargon avoidance (10%)

Passing score: 2.0/3.0. Excellent: 2.5/3.0.

## Why Open Source?

Teaching people to understand AI should not be proprietary. The platforms that implement this methodology can be commercial — but the knowledge of how to teach belongs to everyone.

This methodology was born from lived experience serving populations that the tech industry has historically ignored or exploited. Opening it means any organization — from a rural literacy program to a metropolitan reentry service — can use these teaching patterns without licensing fees, vendor lock-in, or dependency on our platform.

The principles are simple. The implementation is reusable. And the population that needs it most deserves access to the best possible teaching methodology, regardless of which software their organization happens to use.

## Contributing

We welcome contributions, especially:
- Translations of scaffolding content
- Additional domain scaffolds (healthcare literacy, financial literacy, legal literacy)
- Evaluation benchmarks for new populations
- Conversation examples from real-world implementations

Please maintain the nonpartisan standard in all civic content contributions.

## Related

- [EmpathySystem.ai](https://empathysystem.ai) — The platform where this methodology is implemented
- [DOL AI Literacy Framework](https://www.dol.gov) — Federal framework this skill implements
- [iCivics](https://www.icivics.org) — Civic education curriculum (inspiration for civic scaffolds)

## License

Apache 2.0 — See [LICENSE](LICENSE) for details.

Copyright 2026 Luis Barrera Castañón / Lived Experience Inc.

---

*"The computer started with sand. The internet started with a wire. And your next chapter starts with a question."*
