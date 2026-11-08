# HANDOVER — Current State & Roadmap

* **Version:** 0.1 (in progress)
* **Last updated:** 2026-11-08
* **Phase:** v0.1 — Foundation & Visual Anchor

Read this first when picking up the project. It records what exists, what is decided, and what is still open.

---

## 1. Current State

**Done**
* Repository scaffolded; README with scope and attribution
* [DDR-001](decisions/001-ip-nomenclature.md): original IP, inspired by Mirrorworld, plus the replacement glossary
* [Core pillars](01-vision/core-pillars.md) drafted

**In progress / next**
* Visual style guide
* Concept-art prompt sheet and committing the existing concept art

**Source material:** [`project_handover_repository_specification.md`](project_handover_repository_specification.md) is the original concept-phase spec. It is archived, not canon: where it conflicts with a DDR, the DDR wins.

---

## 2. Decision Log

| DDR | Decision | Status |
| :--- | :--- | :--- |
| [001](decisions/001-ip-nomenclature.md) | Original IP inspired by Mirrorworld; canon terms replaced | Accepted |

New decisions use [`decisions/000-template.md`](decisions/000-template.md).

---

## 3. Open Questions (Narrative Scope)

Question IDs are kept from the original spec for traceability. Resolve them in this order.

| ID | Question | Notes | Target |
| :--- | :--- | :--- | :--- |
| ~~Q1~~ | ~~IP stance~~ | Resolved by DDR-001 | — |
| **Q5** | What physically holds the quarantine around the valley? | Shapes the whole region. Options from the spec: carnivorous briar wall from a military spell, alchemical fog ceiling, geographic collapse. | v0.2 |
| **Q6** | Who sealed the Chained Mirror, and what lies behind it? | Answer it fully in the bible, even if the game reveals it differently. Ties to Q5: is the mirror the cause of the quarantine? | v0.2 |
| **Q3** | Is the protagonist's resurrection canon (e.g. a clockwork splinter in the heart, paid for in memory)? | Lore only. Whether death resets anything in play belongs to the game project. | v0.4 |
| **Q2** | Who is the canonical protagonist: origin, affliction, motivation? | The bible writes one canonical outcast. The game project may later treat them as a template. | v0.4 |
| **Q4** | Does the fox companion exist, and what is it? | Must differ clearly from the novels' fox girl (see DDR-001 risk flag). | v0.4 |

### Transferred to the game project

| ID | Question | Why |
| :--- | :--- | :--- |
| Q7 | Primary interaction verb / genre | Game design, out of scope. Goes into the v1.0 handoff brief. |

---

## 4. Roadmap

| Phase | Milestone | Deliverables | Exit criteria |
| :--- | :--- | :--- | :--- |
| **v0.1** | Foundation & Visual Anchor | README, HANDOVER, DDR-001, `01-vision/core-pillars.md`, `01-vision/visual-style-guide.md`, `assets/concept-art/prompts.md`, first concept art | Pillars and visual direction are fixed; art prompts produce images that look like one world. |
| **v0.2** | World Logic & Factions | `02-world-systems/` (cosmology, lithification, relic economy), quarantine (Q5), mirror origin (Q6), `03-theatre-of-operations/overview-schieferwald.md`, `factions.md` | Every faction and supernatural rule has a clear cause and effect, written as in-world rules. |
| **v0.3** | Places & Characters | `03-theatre-of-operations/nodes/*` (4 nodes), `04-narrative-and-script/character-sheets/*` (Flayer, Rot-Witch, faction leaders) | All 4 locations have a layout description, threats and story hooks; each antagonist has motive, history and voice. |
| **v0.4** | Story | Protagonist profile (Q2, Q3, Q4), `main-plot-outline.md`, `dialogue-samples/*` | A complete story arc from entering the valley to the climax at the Chained Mirror. |
| **v1.0** | Bible Release & Handoff | Consistency pass across all documents; `HANDOFF-BRIEF.md` for the game project | The game project can start without asking narrative questions. The brief lists what is canon, what is flexible, and Q7. |

---

## 5. Sprint 1 Backlog (v0.1)

- [x] Scaffold repository: README, HANDOVER, DDR template
- [x] Resolve Q1 → DDR-001
- [x] Draft core pillars
- [ ] Draft `01-vision/visual-style-guide.md` (palettes, lighting, materials, silhouette rules)
- [ ] Write `assets/concept-art/prompts.md`: shared style block plus one prompt per anchor (Iron Breach, Marrow Kiln, Flayer, Chained Mirror, protagonist)
- [ ] Commit existing concept art (`01-iron-breach.jpg`, `02-marrow-kiln.jpg`, `03-the-flayer.jpg`) into `assets/concept-art/`
- [ ] Review existing concept art against DDR-001: no jade-skinned figures, no fox-girl companion
