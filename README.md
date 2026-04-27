# 🏰 FORGE RPG
### *Fantasy Outcomes for Relationships, Growth & Empowerment*
**A Therapeutic Role-Playing Game System for School Social Workers**

[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)
[![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](CONTRIBUTING.md)
[![Research Grounded](https://img.shields.io/badge/evidence-research--based-blue)](research/RESEARCH_FOUNDATION.md)
[![PA Compliant](https://img.shields.io/badge/PA-MTSS%20%7C%20PBIS%20Aligned-red)](docs/09_PA_COMPLIANCE_GUIDE.md)

---

> *"Play is the work of children. Story is how humans make meaning."*
> — adapted from Jean Piaget & Jerome Bruner

---

## What is FORGE RPG?

**FORGE RPG** is a free, open-source, research-grounded therapeutic role-playing game system designed specifically for **school social workers, counselors, and licensed therapists** working with middle school students (ages 11–15).

Unlike proprietary systems, FORGE RPG is:

- 🔓 **Completely free and open-source** (CC BY-SA 4.0)
- 📚 **Grounded in published academic research** — every mechanic maps to a cited evidence base
- 🏫 **Built for schools** — aligned with MTSS Tiers 2 & 3, PBIS, ESSA Title IV-A, and IEP/504 frameworks
- 🛡️ **Safety-first** — built-in emotional safety tools designed for vulnerable student populations
- 🌍 **Culturally responsive** — character options and narrative guidance honoring diverse backgrounds
- 🧠 **Trauma-informed** — structured around Trauma-Sensitive Schools principles
- 🎯 **Goal-oriented** — every session ties to measurable Social-Emotional Learning (SEL) competencies

FORGE RPG targets a broader population than existing systems, supporting students experiencing:
- Anxiety and depression
- Social isolation and peer rejection
- ADHD and executive function challenges
- Trauma and adverse childhood experiences (ACEs)
- Autism spectrum traits (social communication)
- Emotional dysregulation
- Low self-efficacy and negative self-concept

---

## Why FORGE? The Research Case

A growing body of peer-reviewed literature supports tabletop role-playing games (TTRPGs) as therapeutic tools:

| Research Area | Key Finding | Citation |
|---|---|---|
| Perspective-taking | TTRPGs significantly increase theory of mind skills | Rosselet & Stauffer (2013) |
| Anxiety reduction | RPG-based intervention reduced social anxiety symptoms | Blackmon (1994); Lem & Dowling (2021) |
| Self-efficacy | Character play increases self-efficacy via mastery experiences | Bandura (1997); Baer et al. (2022) |
| Emotion regulation | Narrative distance ("the character feels X") supports affect regulation | Stuckey & Nobel (2010) |
| Social skills | TTRPG groups improved social competence scores vs. control | Lim & Lee (2021) |
| Trauma processing | Metaphorical storytelling reduces trauma symptom severity | Gersie (1997); Malchiodi (2011) |
| Academic engagement | Game-based learning increases school engagement and attendance | Mayer (2019) |
| Resilience | Collaborative storytelling builds psychological resilience | Ungar (2011) |

See [`research/RESEARCH_FOUNDATION.md`](research/RESEARCH_FOUNDATION.md) for the complete annotated bibliography with 40+ citations.

---

## Quick Start

### For Social Workers New to TTRPGs

1. **Read first:** [`docs/01_WHAT_IS_A_TTRPG.md`](docs/01_WHAT_IS_A_TTRPG.md) — a plain-language introduction
2. **Understand the theory:** [`research/RESEARCH_FOUNDATION.md`](research/RESEARCH_FOUNDATION.md)
3. **Set up your group:** [`docs/02_FACILITATOR_GUIDE.md`](docs/02_FACILITATOR_GUIDE.md)
4. **Run Session Zero:** [`docs/06_SESSION_ZERO_GUIDE.md`](docs/06_SESSION_ZERO_GUIDE.md)
5. **Play your first adventure:** [`modules/01_THE_BRIDGE_BETWEEN_WORLDS/`](modules/01_THE_BRIDGE_BETWEEN_WORLDS/)

### For Educators with TTRPG Experience

Jump straight to the therapeutic overlay:
- [`docs/03_THERAPEUTIC_FRAMEWORK.md`](docs/03_THERAPEUTIC_FRAMEWORK.md)
- [`docs/05_SEL_TRACKING_SYSTEM.md`](docs/05_SEL_TRACKING_SYSTEM.md)
- [`tools/SAFETY_TOOLS.md`](tools/SAFETY_TOOLS.md)

---

## Repository Structure

```
FORGE-RPG/
│
├── README.md                          ← You are here
├── DOCUMENTS_INDEX.md                 ← Full annotated index of all files
├── CONTRIBUTING.md                    ← How to contribute
├── LICENSE.md                         ← CC BY-SA 4.0
├── CHANGELOG.md                       ← Version history
│
├── docs/                              ← Core documentation
│   ├── 01_WHAT_IS_A_TTRPG.md
│   ├── 02_FACILITATOR_GUIDE.md
│   ├── 03_THERAPEUTIC_FRAMEWORK.md
│   ├── 04_CORE_RULES.md
│   ├── 05_SEL_TRACKING_SYSTEM.md
│   ├── 06_SESSION_ZERO_GUIDE.md
│   ├── 07_GROUP_COMPOSITION_GUIDE.md
│   ├── 08_CRISIS_RESPONSE_PROTOCOL.md
│   ├── 09_PA_COMPLIANCE_GUIDE.md
│   └── 10_GRANT_FUNDING_GUIDE.md
│
├── research/                          ← Academic foundations
│   ├── RESEARCH_FOUNDATION.md         ← Full annotated bibliography (40+ sources)
│   └── THEORY_OF_CHANGE.md           ← Logic model for program evaluation
│
├── character-sheets/                  ← Printable & digital character materials
│   ├── ARCHETYPE_GUIDE.md
│   ├── archetype_the_guardian.pdf
│   ├── archetype_the_seeker.pdf
│   ├── archetype_the_trickster.pdf
│   ├── archetype_the_healer.pdf
│   ├── archetype_the_scholar.pdf
│   └── blank_character_sheet.pdf
│
├── modules/                           ← Adventure modules
│   ├── ADVENTURE_MODULE_TEMPLATE.md   ← Create your own
│   ├── 01_THE_BRIDGE_BETWEEN_WORLDS/  ← Introductory module (Levels 1-3)
│   │   ├── MODULE_OVERVIEW.md
│   │   ├── ENCOUNTER_GUIDE.md
│   │   ├── NPC_ROSTER.md
│   │   └── FACILITATOR_NOTES.md
│   └── 02_THE_STORM_WITHIN/           ← Emotion regulation module (Levels 2-4)
│       ├── MODULE_OVERVIEW.md
│       ├── ENCOUNTER_GUIDE.md
│       └── FACILITATOR_NOTES.md
│
├── handouts/                          ← Student-facing materials
│   ├── RULE_SUMMARY_CARD.md
│   ├── EMOTION_WHEEL_HANDOUT.md
│   ├── MY_CHARACTER_MY_STRENGTHS.md
│   └── GROUP_AGREEMENTS_TEMPLATE.md
│
└── tools/                             ← Facilitator tools
    ├── SAFETY_TOOLS.md                ← X-Card, Lines/Veils, Debrief protocols
    ├── SESSION_PLANNER_TEMPLATE.md
    ├── PROGRESS_MONITORING_FORM.md
    ├── PARENT_GUARDIAN_LETTER.md
    └── ADMINISTRATOR_ONE_PAGER.md
```

---

## Core Design Principles

### 1. The FORGE Framework
Every session is structured around five **FORGE** pillars, each mapping to CASEL SEL competencies:

| FORGE Pillar | SEL Competency | Game Element |
|---|---|---|
| **F**ocus | Self-Awareness | Character creation & reflection |
| **O**thers | Social Awareness | Collaborative decision-making |
| **R**egulation | Self-Management | Emotion mechanics & "Calm Points" |
| **G**rowth | Responsible Decision-Making | Consequences & learning from failure |
| **E**mpathy | Relationship Skills | NPC interactions & perspective-taking challenges |

### 2. Therapeutic Distance
FORGE uses the principle of **therapeutic distance** — the "as-if" space between player and character — to allow students to:
- Practice difficult emotions without direct personal exposure
- Try on new behavioral patterns safely
- Receive feedback through narrative rather than direct criticism

### 3. Trauma-Informed Design
Every mechanic has been evaluated against the **SAMHSA Six Principles of Trauma-Informed Care**:
- Safety, Trustworthiness & Transparency, Peer Support, Collaboration, Empowerment, Cultural Sensitivity

---

## Group Structure

**Recommended group size:** 3–5 students + 1 facilitator
**Session length:** 45–60 minutes (school period compatible)
**Program duration:** 8–16 weeks (one module = 8 sessions)
**Referral criteria:** See [`docs/07_GROUP_COMPOSITION_GUIDE.md`](docs/07_GROUP_COMPOSITION_GUIDE.md)

### MTSS Alignment
| Tier | Application | Group Size | Frequency |
|---|---|---|---|
| Tier 2 | Small group intervention for at-risk students | 4–5 students | Weekly |
| Tier 3 | Intensive individual/dyad sessions | 1–2 students | 2x/week |
| Universal | Classroom SEL extension (optional) | Full class | Monthly |

---

## Pennsylvania-Specific Compliance

FORGE RPG was designed with Pennsylvania regulations in mind:

- ✅ **ESSA Title IV-A** — Student Support and Academic Enrichment eligible activity
- ✅ **PA Safe Schools Act** — Social-emotional learning component
- ✅ **Chapter 14** — IEP social skills goal alignment
- ✅ **Chapter 16** — Gifted IEP emotional support applications  
- ✅ **PBIS** — Positive behavioral framework compatible
- ✅ **Chapter 49** — Satisfies school social worker professional development requirements

See [`docs/09_PA_COMPLIANCE_GUIDE.md`](docs/09_PA_COMPLIANCE_GUIDE.md) for documentation templates.

---

## How FORGE Improves on Existing Systems

| Feature | Critical Core | FORGE RPG |
|---|---|---|
| Cost | ~$60 kit | **Free** |
| License | Proprietary | **CC BY-SA 4.0** |
| Population | Primarily autism | **All social-emotional needs** |
| Age range | 9–109 | **Middle school optimized (11–15)** |
| Research citations | Limited | **40+ peer-reviewed sources** |
| Safety tools | Basic | **Comprehensive (X-Card, Lines/Veils, STOP protocol)** |
| SEL tracking | None | **CASEL-aligned progress monitoring** |
| MTSS alignment | None | **Tiers 2 & 3 mapped** |
| IEP compatibility | None | **Goal language included** |
| PA compliance | None | **Full documentation suite** |
| Grant language | None | **Title IV-A templates included** |
| Trauma-informed | Partial | **SAMHSA framework embedded** |
| Cultural responsiveness | Limited | **Diverse archetypes & narrative hooks** |
| Crisis protocols | None | **Full protocol with mandated reporter guidance** |
| Customization | Difficult | **Open template system** |

---

## Contributing

FORGE RPG is a living project. We welcome contributions from:
- School social workers & counselors
- Special education professionals
- TTRPG designers
- Researchers in game-based learning
- Educators with diverse cultural perspectives

See [`CONTRIBUTING.md`](CONTRIBUTING.md) for how to get involved.

---

## License

FORGE RPG is released under the **Creative Commons Attribution-ShareAlike 4.0 International License (CC BY-SA 4.0)**.

You are free to:
- ✅ **Share** — copy and redistribute in any medium or format
- ✅ **Adapt** — remix, transform, and build upon the material
- ✅ **Commercial use** — even commercially (with attribution)

Under the following terms:
- 📌 **Attribution** — You must give appropriate credit and indicate changes
- 📌 **ShareAlike** — Adaptations must use the same license

See [`LICENSE.md`](LICENSE.md) for full terms.

---

## Authors & Acknowledgments

**Lead Author:** Developed in collaboration with Pennsylvania Middle School educators and school social work professionals.

**Research Review:** Based on peer-reviewed literature in game-based therapy, social-emotional learning, and school-based mental health.

**Inspired by:** The groundbreaking work of Game to Grow's *Critical Core*, Wheelhouse Workshop's therapeutic game programming, and the broader *Therapeutic Game Master* community.

**Dedicated to:** Every student who has ever felt like they didn't belong — and every social worker who refused to give up on them.

---

## Citation

If you use FORGE RPG in research or practice, please cite as:

```
FORGE RPG: Fantasy Outcomes for Relationships, Growth & Empowerment.
(2025). A therapeutic tabletop role-playing game system for school social workers.
Retrieved from https://github.com/[your-handle]/FORGE-RPG
License: CC BY-SA 4.0
```

---

## Contact & Community

- 📬 **Issues & Suggestions:** Use GitHub Issues
- 💬 **Discussion:** GitHub Discussions tab
- 🏫 **For PA Schools:** See [`docs/09_PA_COMPLIANCE_GUIDE.md`](docs/09_PA_COMPLIANCE_GUIDE.md)

---

*FORGE RPG is not a replacement for licensed mental health treatment. It is a structured, evidence-informed supplementary intervention tool for use by trained school mental health professionals. Facilitators should maintain appropriate clinical boundaries and mandated reporter obligations at all times.*
