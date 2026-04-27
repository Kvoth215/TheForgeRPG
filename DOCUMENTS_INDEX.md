# 📋 FORGE RPG — Complete Documents Index
**Version 1.0 | Last Updated: 2025**

This index provides a complete annotated guide to every file in the FORGE RPG repository. Use it to find exactly what you need, whether you're a first-time facilitator, a researcher, or an administrator seeking compliance documentation.

---

## 🗂️ How to Use This Index

Each entry includes:
- **File path** and name
- **Purpose** — what this document does
- **Who needs it** — primary audience
- **When to use it** — timing in the program
- **Page/word count** estimate
- **Dependencies** — what to read first

---

## 📌 Root Level Files

### `README.md`
- **Purpose:** Project overview, quick-start guide, comparison to other systems, license info
- **Who needs it:** Everyone — start here
- **When to use it:** Before anything else
- **Est. length:** ~2,500 words
- **Dependencies:** None

### `DOCUMENTS_INDEX.md`
- **Purpose:** This file — complete annotated navigation guide
- **Who needs it:** All facilitators; useful for onboarding new team members
- **When to use it:** Whenever you're looking for a specific resource
- **Dependencies:** README.md

### `CONTRIBUTING.md`
- **Purpose:** Guidelines for educators, researchers, and designers who want to improve FORGE RPG
- **Who needs it:** Contributors, educators who want to create new modules
- **When to use it:** When you want to add content or report an issue
- **Dependencies:** README.md

### `LICENSE.md`
- **Purpose:** Full text of the CC BY-SA 4.0 license
- **Who needs it:** Administrators, grant writers, anyone reproducing materials
- **When to use it:** Before distributing materials to other schools or districts
- **Dependencies:** None

### `CHANGELOG.md`
- **Purpose:** Version history of the project
- **Who needs it:** Returning users; researchers tracking iterations
- **When to use it:** When checking if materials have been updated

---

## 📚 `docs/` — Core Documentation

### `docs/01_WHAT_IS_A_TTRPG.md`
- **Purpose:** Plain-language explanation of tabletop role-playing games for professionals who have never played one. Addresses common myths, explains the Game Master role, and describes how sessions work in practice.
- **Who needs it:** Social workers, school psychologists, or administrators unfamiliar with TTRPGs
- **When to use it:** Before reading any other document. Also useful to share with skeptical parents or administrators.
- **Est. length:** ~3,000 words + FAQ section
- **Key sections:**
  - What happens in a typical session?
  - Why is this different from video games?
  - Isn't D&D dangerous? (Addressing the "Satanic Panic" myth with research)
  - What does the facilitator actually do?
  - Parent FAQ

---

### `docs/02_FACILITATOR_GUIDE.md`
- **Purpose:** The comprehensive operational guide for school social workers running FORGE RPG groups. The backbone of the program.
- **Who needs it:** All facilitators — read before running Session Zero
- **When to use it:** During program planning; reference throughout the year
- **Est. length:** ~8,000 words
- **Key sections:**
  - Facilitator qualifications and preparation
  - Recruiting and screening students
  - Setting up your space
  - Managing group dynamics specific to middle schoolers
  - Handling disclosure during play
  - Session structure: the 5-part FORGE Session Arc
  - Adapting for students with IEPs, 504s, and trauma histories
  - Working with co-facilitators and paraprofessionals
  - Communicating with parents, teachers, and administrators
  - Documentation and progress monitoring
  - When to pause or end the program early
- **Dependencies:** `docs/01_WHAT_IS_A_TTRPG.md`

---

### `docs/03_THERAPEUTIC_FRAMEWORK.md`
- **Purpose:** The clinical and theoretical foundation of FORGE RPG. Explains the evidence-based mechanisms by which TTRPGs produce therapeutic change, and how FORGE operationalizes each mechanism.
- **Who needs it:** Social workers, school psychologists, program evaluators, grant writers
- **When to use it:** Before program implementation; when presenting to administration or IRBs
- **Est. length:** ~6,000 words
- **Key sections:**
  - Therapeutic distance and the "as-if" space
  - Narrative therapy integration (White & Epston)
  - Social Learning Theory (Bandura) — modeling through characters
  - Cognitive-Behavioral mechanisms — thought-action-consequence loops
  - Play therapy theory in adolescent contexts
  - DIR/Floortime principles adapted for group settings
  - Self-Determination Theory (autonomy, competence, relatedness)
  - Positive Psychology and the VIA Character Strengths framework
  - Trauma-informed care: the SAMHSA six principles applied to TTRPGs
  - FORGE Theory of Change (logic model overview)
- **Dependencies:** `research/RESEARCH_FOUNDATION.md` (recommended)

---

### `docs/04_CORE_RULES.md`
- **Purpose:** The complete, simplified game rules for FORGE RPG. Designed to be learned in one session by facilitators, and introduced to students over 2–3 sessions. Rules are intentionally lighter than D&D 5e to reduce barriers.
- **Who needs it:** All facilitators; can be shared with students (Student Summary Card is in `handouts/`)
- **When to use it:** During facilitator preparation; Session 1–2
- **Est. length:** ~5,000 words
- **Key sections:**
  - Core Resolution Mechanic (the d20 check, simplified)
  - The HEART Attributes (Head, Empathy, Agility, Resolve, Teamwork) — each maps to SEL
  - Calm Points system — the emotion regulation mechanic
  - Advantage and Disadvantage — simplified from D&D 5e
  - The Help Action — how collaboration is mechanically rewarded
  - Conflict resolution (social and physical encounters)
  - Leveling up and character growth
  - Facilitator fiat: when to bend the rules
  - Rules for emotional safety: in-game vs. out-of-game communication
- **Dependencies:** `docs/01_WHAT_IS_A_TTRPG.md`

---

### `docs/05_SEL_TRACKING_SYSTEM.md`
- **Purpose:** A complete progress monitoring system aligned with CASEL's five SEL competencies. Allows facilitators to collect structured data on student growth for IEP documentation, program evaluation, and grant reporting.
- **Who needs it:** Social workers, program coordinators, grant managers
- **When to use it:** Before program starts (baseline); every 4 sessions (progress); at program end (summative)
- **Est. length:** ~4,000 words + data forms
- **Key sections:**
  - Overview of CASEL's five competencies and FORGE alignment
  - Behavioral anchors for each competency (observable, measurable)
  - Session observation protocol (what to watch for)
  - The FORGE Student Growth Scale (Likert rubric, 1–4)
  - Pre/Post student self-assessment tool
  - Teacher perception survey (for triangulation)
  - Aggregate data reporting template for administrators
  - Connecting SEL data to IEP goal progress
  - Sample data visualizations
- **Dependencies:** `docs/02_FACILITATOR_GUIDE.md`

---

### `docs/06_SESSION_ZERO_GUIDE.md`
- **Purpose:** A complete script and guide for the mandatory first session (Session Zero), which establishes group agreements, introduces safety tools, builds rapport, and begins character creation — without any gameplay pressure.
- **Who needs it:** All facilitators; essential before the first adventure session
- **When to use it:** Before Session 1 of any module
- **Est. length:** ~3,500 words + activity sheets
- **Key sections:**
  - Why Session Zero matters (research on group cohesion)
  - The 5 activities of Session Zero (with time guides for 45-min periods)
  - Activity 1: The Name Circle (community-building)
  - Activity 2: Group Agreements co-creation
  - Activity 3: Safety Tools introduction (X-Card, Open Door)
  - Activity 4: "What Kind of Hero Are You?" — character archetype exploration
  - Activity 5: The World-Building Invitation — students help design the setting
  - Facilitator debriefing questions
  - What to do if a student refuses to participate
- **Dependencies:** `tools/SAFETY_TOOLS.md`

---

### `docs/07_GROUP_COMPOSITION_GUIDE.md`
- **Purpose:** Clinical guidance for which students are appropriate for FORGE RPG groups, how to screen referrals, how to compose groups for maximum therapeutic effect, and contraindications.
- **Who needs it:** School social workers, counselors, child study team members
- **When to use it:** During referral screening; when planning groups
- **Est. length:** ~3,000 words
- **Key sections:**
  - Who benefits most from FORGE RPG (research-based inclusion criteria)
  - Referral screening checklist
  - Contraindications and clinical caution flags
  - Mixing diagnoses: what the research says
  - Group composition by presenting concern
  - Individual vs. group format decision tree
  - Balancing gender, cultural backgrounds, and social dynamics
  - Managing students who are already in conflict with each other
- **Dependencies:** `docs/03_THERAPEUTIC_FRAMEWORK.md`

---

### `docs/08_CRISIS_RESPONSE_PROTOCOL.md`
- **Purpose:** A clear, step-by-step protocol for responding to disclosures, emotional crises, and safety concerns that may arise during FORGE RPG sessions. Includes mandatory reporter guidance specific to Pennsylvania.
- **Who needs it:** All facilitators — required reading before any session
- **When to use it:** Reference before each session; follow immediately in any crisis
- **Est. length:** ~2,500 words + laminated quick-reference card format
- **Key sections:**
  - Why TTRPG sessions can surface disclosures (the therapeutic distance phenomenon)
  - The PAUSE Protocol (5 steps for in-session crises)
  - Recognizing in-game metaphor vs. real-world disclosure
  - Pennsylvania mandated reporter requirements
  - Suicide/self-harm disclosure procedures
  - Abuse/neglect disclosure procedures
  - Peer conflict escalation during play
  - After-session documentation
  - Parent/guardian notification procedures
  - Quick Reference Card (laminate and keep at table)
- **Dependencies:** Must be read independently; no prerequisites

---

### `docs/09_PA_COMPLIANCE_GUIDE.md`
- **Purpose:** Complete documentation of how FORGE RPG aligns with Pennsylvania education law, regulations, and best-practice frameworks. Includes templates for compliance documentation.
- **Who needs it:** Social workers, administrators, compliance officers, grant writers
- **When to use it:** During program proposal; for annual reporting
- **Est. length:** ~5,000 words + document templates
- **Key sections:**
  - ESSA Title IV-A alignment and documentation requirements
  - PA Safe Schools Act — social-emotional component alignment
  - Chapter 14 (Special Education) — IEP social skill goal language templates
  - Chapter 16 (Gifted Education) — social-emotional applications
  - Chapter 49 (Educator Certification) — how FORGE counts for PD credit hours
  - PBIS integration — using FORGE data in school-wide PBIS systems
  - MTSS documentation templates
  - Student consent and parent notification templates
  - FERPA/HIPAA considerations for session notes
  - Sample administrative approval memo
- **Dependencies:** `docs/02_FACILITATOR_GUIDE.md`

---

### `docs/10_GRANT_FUNDING_GUIDE.md`
- **Purpose:** A practical guide to securing funding for FORGE RPG programs, with specific focus on Pennsylvania grant sources and pre-written boilerplate language for common grant applications.
- **Who needs it:** Social workers, grant writers, building principals, business administrators
- **When to use it:** During budget planning; when submitting grants
- **Est. length:** ~4,500 words + grant language templates
- **Key sections:**
  - Federal funding sources (Title IV-A, IDEA, Title I)
  - Pennsylvania-specific sources (PA Safe Schools, mental health block grants, Classrooms for the Future)
  - Private foundation opportunities (national and PA-specific)
  - Budget justification templates
  - Pre-written program description paragraphs
  - Evidence base summary for grant narratives
  - Logic model template (inputs → activities → outputs → outcomes)
  - Evaluation plan language
  - Letters of support templates
  - Common grant reviewer questions and answers
- **Dependencies:** `docs/09_PA_COMPLIANCE_GUIDE.md`, `research/THEORY_OF_CHANGE.md`

---

## 🔬 `research/` — Academic Foundations

### `research/RESEARCH_FOUNDATION.md`
- **Purpose:** The complete annotated bibliography supporting FORGE RPG's design. Over 40 peer-reviewed sources organized by therapeutic mechanism. This is the "proof" document that establishes FORGE RPG as evidence-based practice.
- **Who needs it:** Social workers defending the program to skeptics; grant writers; researchers
- **When to use it:** When presenting to administration; when writing grants; when asked "Is this real therapy?"
- **Est. length:** ~8,000 words
- **Sections:**
  - Part 1: Foundational Research (TTRPGs and mental health)
  - Part 2: Social Skills and Peer Relationships
  - Part 3: Emotion Regulation and Self-Management
  - Part 4: Trauma, Adverse Childhood Experiences, and Narrative
  - Part 5: School-Based Mental Health Interventions
  - Part 6: Game-Based Learning and Academic Engagement
  - Part 7: Cultural Responsiveness in Group Therapy
  - Part 8: Contraindications and Ethical Considerations
  - Summary Table: Therapeutic Mechanism → Research Support → FORGE Design Feature

---

### `research/THEORY_OF_CHANGE.md`
- **Purpose:** A logic model and Theory of Change document for FORGE RPG. Maps program inputs through activities to short-, medium-, and long-term outcomes. Essential for grant applications and program evaluation.
- **Who needs it:** Grant writers, program evaluators, administrators
- **When to use it:** Grant applications; end-of-year reporting; program improvement planning
- **Est. length:** ~2,500 words + visual logic model diagram
- **Key sections:**
  - Problem statement
  - Target population
  - Inputs (resources needed)
  - Activities (what happens in sessions)
  - Outputs (sessions delivered, students served)
  - Short-term outcomes (3–6 months)
  - Long-term outcomes (1–3 years)
  - Assumptions and external factors
  - Measurement indicators for each outcome

---

## 🧙 `character-sheets/` — Character Materials

### `character-sheets/ARCHETYPE_GUIDE.md`
- **Purpose:** Complete guide to the five FORGE archetypes, including the therapeutic rationale for each, which student profiles each supports, and how to guide students toward an appropriate character.
- **Who needs it:** All facilitators
- **When to use it:** Session Zero and Session 1 during character creation
- **Est. length:** ~4,000 words
- **The Five Archetypes:**

| Archetype | Core Strength | SEL Focus | Best for Students Who... |
|---|---|---|---|
| **The Guardian** | Protection, loyalty | Relationship skills | Are protective/caring; struggle with vulnerability |
| **The Seeker** | Curiosity, discovery | Responsible decision-making | Are intellectually engaged; avoid social risk |
| **The Trickster** | Wit, adaptability | Self-awareness | Use humor defensively; need to build genuine connection |
| **The Healer** | Empathy, restoration | Social awareness | Are empathic but self-sacrificing; need self-advocacy skills |
| **The Scholar** | Knowledge, strategy | Self-management | Have high cognitive skills; struggle with emotional regulation |

---

### `character-sheets/archetype_the_guardian.pdf` *(and others)*
- **Purpose:** Printable, fillable character sheets for each archetype. Single page. Designed to be accessible, visually appealing, and usable without reading above a 5th-grade level.
- **Who needs it:** Students
- **When to use it:** Session Zero character creation
- **Design features:**
  - Simplified HEART attributes (no complex math)
  - "My Character Feels..." emotion tracker on the sheet
  - "My Character's Strength Story" reflective prompt
  - Space for a character drawing or symbol
  - Calm Points tracker (visual, like a battery bar)

---

### `character-sheets/blank_character_sheet.pdf`
- **Purpose:** A blank, editable template for students who want to create a fully custom character outside the five archetypes.
- **Who needs it:** Students with strong creative motivation; advanced groups
- **When to use it:** After at least 2 sessions of play with an archetype character

---

## 🗺️ `modules/` — Adventure Modules

### `modules/ADVENTURE_MODULE_TEMPLATE.md`
- **Purpose:** A complete template for creating original FORGE RPG adventure modules. Includes the FORGE-DOTS system (updated from Critical Core's DOTS) for structuring therapeutic encounters.
- **Who needs it:** Facilitators who want to create custom content; contributors
- **When to use it:** After running at least one existing module
- **Est. length:** ~3,000 words
- **The FORGE-DOTS System:**
  - **D**rive — what does the story need the characters to accomplish?
  - **O**bstacle — what challenge stands in the way?
  - **T**herapeutic Target — which SEL competency does this encounter practice?
  - **S**upport — what facilitator moves help if students struggle?
  - **+** Debrief — what reflection questions close the encounter?

---

### `modules/01_THE_BRIDGE_BETWEEN_WORLDS/`
**Module 1: The Bridge Between Worlds** *(Introductory — 8 sessions)*

A new group of travelers finds themselves mysteriously transported to the realm of Aurenvast — a world on the edge of a great divide. Two neighboring kingdoms have forgotten how to talk to each other. Only a group of unlikely heroes can rebuild the bridge.

**Therapeutic Focus:** Building trust, initiating social connection, tolerating uncertainty

**SEL Competencies:** Social Awareness, Relationship Skills, Self-Awareness

**Encounter Arc:**

| Session | Encounter | Therapeutic Target |
|---|---|---|
| 1 | Arrival in Aurenvast | Group cohesion, introductions |
| 2 | The Quiet Village | Noticing others' emotions |
| 3 | The Wall | Identifying barriers to connection |
| 4 | The Messenger Challenge | Active listening |
| 5 | The Misunderstanding | Perspective-taking |
| 6 | The Bridge Materials | Collaboration under pressure |
| 7 | The Final Crossing | Managing anxiety, risk-taking |
| 8 | The Celebration & Reflection | Integrating growth, closure |

**Files:**
- `MODULE_OVERVIEW.md` — setting, story, themes, therapeutic rationale
- `ENCOUNTER_GUIDE.md` — session-by-session facilitator scripts and prompts
- `NPC_ROSTER.md` — named NPCs with relationship-building opportunities
- `FACILITATOR_NOTES.md` — clinical commentary on each encounter

---

### `modules/02_THE_STORM_WITHIN/`
**Module 2: The Storm Within** *(Emotion Regulation Focus — 8 sessions)*

A magical storm threatens to tear apart the realm — but it's powered by the unprocessed emotions of a forgotten spirit. The heroes must journey through different "emotion zones" to help the spirit find peace.

**Therapeutic Focus:** Emotion identification, regulation strategies, distress tolerance

**SEL Competencies:** Self-Awareness, Self-Management, Responsible Decision-Making

**Encounter Arc:**

| Session | Encounter | Therapeutic Target / Emotion Zone |
|---|---|---|
| 1 | Into the Storm | Recognizing emotional weather |
| 2 | The Red Forest (Anger) | Anger as information; de-escalation |
| 3 | The Grey Caves (Sadness) | Validating sadness; not fixing |
| 4 | The Shaking Cliffs (Anxiety) | Grounding; coping strategies |
| 5 | The Frozen Lake (Numbness) | Dissociation awareness (gentle) |
| 6 | The Golden Meadow (Joy) | Savoring; positive affect |
| 7 | The Spirit's Heart | Integration; emotional complexity |
| 8 | After the Storm | Post-module reflection and celebration |

---

## 📄 `handouts/` — Student-Facing Materials

### `handouts/RULE_SUMMARY_CARD.md`
- **Purpose:** A single-page (half-sheet) quick reference for students summarizing the core rules, the HEART attributes, and how Calm Points work. Designed for 5th–7th grade reading level.
- **Who needs it:** Students; print one per student
- **When to use it:** Distribute in Session 1; students keep for the program

### `handouts/EMOTION_WHEEL_HANDOUT.md`
- **Purpose:** A simplified emotion wheel for use during sessions. Helps students name what their character (and sometimes themselves) is feeling. Based on Plutchik's wheel adapted for adolescents.
- **Who needs it:** Students; facilitators (for facilitation prompts)
- **When to use it:** Every session — keep at the table

### `handouts/MY_CHARACTER_MY_STRENGTHS.md`
- **Purpose:** A reflective worksheet connecting students' character's strengths to their own real-world strengths. Builds self-efficacy and positive self-concept. Based on VIA Character Strengths framework.
- **Who needs it:** Students
- **When to use it:** Session 4 and final session (before/after comparison)

### `handouts/GROUP_AGREEMENTS_TEMPLATE.md`
- **Purpose:** A co-created group agreements poster template for Session Zero. Includes 5 pre-written foundational agreements and space for the group to add their own.
- **Who needs it:** Facilitators; students co-create during Session Zero
- **When to use it:** Session Zero

---

## 🛠️ `tools/` — Facilitator Tools

### `tools/SAFETY_TOOLS.md`
- **Purpose:** Complete guide to all emotional and psychological safety tools used in FORGE RPG. Critical for working with vulnerable students.
- **Who needs it:** All facilitators — required reading before Session Zero
- **When to use it:** Before Session Zero; reference for each session
- **Est. length:** ~3,000 words
- **Tools included:**
  - **The X-Card** — immediate pause for uncomfortable content (Stavropoulos, 2012)
  - **The Open Door** — permission to leave without explanation
  - **Lines and Veils** — pre-game content boundaries (Rein-Hagen adapted for schools)
  - **The PAUSE Signal** — non-verbal check-in system
  - **The Lantern Check-In** — start-of-session emotional temperature gauge
  - **The Debrief Protocol** — structured end-of-session closing ritual
  - **The STOP Word** — student-controlled emergency stop
  - **Re-entry Protocol** — how to return after a pause or absence

---

### `tools/SESSION_PLANNER_TEMPLATE.md`
- **Purpose:** A one-page session planning template for each FORGE RPG session. Helps facilitators organize therapeutic goals, key encounters, safety checks, and observation targets before each session.
- **Who needs it:** All facilitators
- **When to use it:** Day before each session

### `tools/PROGRESS_MONITORING_FORM.md`
- **Purpose:** Session-by-session data collection form. Records student participation, observed SEL behaviors, significant moments, and follow-up needs. Compatible with IEP progress monitoring formats.
- **Who needs it:** All facilitators
- **When to use it:** During or immediately after each session

### `tools/PARENT_GUARDIAN_LETTER.md`
- **Purpose:** A customizable letter to send to parents/guardians explaining the FORGE RPG program, addressing common concerns, and requesting participation consent.
- **Who needs it:** Facilitators (to send home); parents/guardians (to read)
- **When to use it:** Before Session Zero
- **Versions included:**
  - Standard letter (English)
  - Simplified letter (3rd-grade reading level)
  - FAQ insert for skeptical parents
  - *(Note: Translation into other languages is encouraged — see CONTRIBUTING.md)*

### `tools/ADMINISTRATOR_ONE_PAGER.md`
- **Purpose:** A concise, professionally formatted one-page program summary for building principals, superintendents, and school boards. Covers program rationale, research basis, logistics, and data.
- **Who needs it:** Facilitators presenting to administration
- **When to use it:** During program proposal; for annual review

---

## 📊 Quick Reference: Reading Order by Role

### I'm a School Social Worker Setting Up My First Group
1. `docs/01_WHAT_IS_A_TTRPG.md`
2. `research/RESEARCH_FOUNDATION.md` (skim for confidence)
3. `docs/02_FACILITATOR_GUIDE.md` ⭐
4. `docs/07_GROUP_COMPOSITION_GUIDE.md`
5. `tools/SAFETY_TOOLS.md` ⭐
6. `docs/08_CRISIS_RESPONSE_PROTOCOL.md` ⭐
7. `docs/06_SESSION_ZERO_GUIDE.md`
8. `docs/04_CORE_RULES.md`
9. `modules/01_THE_BRIDGE_BETWEEN_WORLDS/MODULE_OVERVIEW.md`
10. Run Session Zero!

### I'm Writing a Grant Application
1. `research/RESEARCH_FOUNDATION.md`
2. `research/THEORY_OF_CHANGE.md`
3. `docs/09_PA_COMPLIANCE_GUIDE.md`
4. `docs/10_GRANT_FUNDING_GUIDE.md` ⭐
5. `docs/05_SEL_TRACKING_SYSTEM.md` (for evaluation section)

### I'm Presenting to My Principal
1. `tools/ADMINISTRATOR_ONE_PAGER.md` ⭐ (give them this)
2. `docs/09_PA_COMPLIANCE_GUIDE.md` (have ready for questions)
3. `research/RESEARCH_FOUNDATION.md` (summary table)

### I'm a Student Who Wants to Know More
1. `handouts/RULE_SUMMARY_CARD.md`
2. `character-sheets/ARCHETYPE_GUIDE.md`
3. Talk to your social worker! 🎲

---

*⭐ = Highest priority / Read these first*

---

## Version History

| Version | Date | Changes |
|---|---|---|
| 1.0 | 2025 | Initial release — 2 adventure modules, 5 archetypes, full documentation suite |
| 1.1 | *(planned)* | Module 3: The Forgotten Map (executive function focus); Spanish translations |
| 1.2 | *(planned)* | Digital interactive character sheets; online facilitator community |
| 2.0 | *(planned)* | Peer-reviewed pilot study results integration; expanded research base |

---

*FORGE RPG Documents Index — maintained by the FORGE RPG community. Last reviewed: 2025*
