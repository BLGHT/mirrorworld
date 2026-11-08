# Project Handover & Repository Specification: *Project Schieferwald* (Pitch Bible)

* **Version:** 0.1.0 (Pre-Production / Concept Phase)
* **Status:** Active — Establishing Baseline & Resolving Core Decisions
* **Focus:** Narrative-First World-Building & Proof of Concept (PoC) Script

---

## 1. Executive Summary & High Concept

**Logline:** Set in a brutal, rotting dark-fantasy interpretation of Cornelia Funke’s *Mirrorworld*, an unnamed outcast navigates a quarantined borderland where archaic siege-industrialization violently collides with parasitic, vengeful folklore.

Instead of locking into a mechanical genre immediately, this project follows an **IP-driven pre-production pipeline**. The objective of this repository is to build a modular **Pitch Bible and Narrative Proof of Concept (PoC)** set within a single contained region (**The Schieferwald / Slate-Weald**) that can later be mapped onto an Action-RPG, CRPG, or Survival/Extraction gameplay loop.

---

## 2. Recommended GitHub Repository Structure

```text
project-schieferwald/
├── README.md                        # Project overview, elevator pitch, and navigation index
├── HANDOVER.md                      # Current state, open questions, and active roadmap
├── assets/
│   ├── concept-art/                 # Generated visual anchors (Iron Breach, Flayer, etc.)
│   └── diagrams/                    # Faction relationship graphs, map layouts, state flows
├── 01-vision/
│   ├── core-pillars.md              # Aesthetic, thematic, and tonal invariants
│   └── visual-style-guide.md        # Color palettes, lighting rules, material contrasts
├── 02-world-systems/
│   ├── cosmology-and-magic.md       # Rules of Old Blood vs. Cold Iron
│   ├── lithification-curse.md       # Mechanics and narrative progression of the Stone Curse
│   └── relic-economy.md             # Cursed artifacts, harvesting, and physiological toll
├── 03-theatre-of-operations/
│   ├── overview-schieferwald.md     # Geography and quarantine conditions of the valley
│   ├── factions.md                  # Smelter Syndicate, Court of Rot, Mirror-Cutters
│   └── nodes/                       # Individual location specs
│       ├── 01-iron-breach.md
│       ├── 02-marrow-kiln.md
│       ├── 03-open-air-tannery.md
│       └── 04-chained-mirror.md
├── 04-narrative-and-script/
│   ├── protagonist-profile.md       # Origin, affliction, and motivation
│   ├── main-plot-outline.md         # Three-act structure for the PoC vertical slice
│   ├── character-sheets/            # NPCs and Bosses (The Flayer, The Rot-Witch)
│   └── dialogue-samples/            # Tone-setting scripts and item descriptions
├── 05-ludonarrative-eval/
│   └── genre-prototypes.md          # Mapping world systems to ARPG, CRPG, or Extraction loops
└── decisions/
    └── 001-ip-nomenclature.md       # Design Decision Records (DDRs) logging key choices
```

---

## 3. Project Baseline (Current State v0.1)

### 3.1 Core Thematic Pillars
1. **Archaic Industrialism vs. Feral Folklore:** Not polished Victorian steampunk, but mud, cold iron, black powder, wooden siege cranes, and open smelting pits tearing into a primeval forest that fights back with blood curses, thorns, and mutations.
2. **Magic as Body Horror:** Fairy tales are biological, contagious, and transactional. Witches breed mold and bone-rot; tailors stitch living skin; petrification slowly turns flesh into brittle mineral.
3. **Systemic Moral Greyness:** Neither the encroaching mining operations, the desperate human military, nor the ancient, sadistic creatures of the woods represent "good." Survival requires exploiting all three.

### 3.2 Cosmology & World Systems
* **Cold Iron vs. Old Blood:** Iron, coal smoke, and industrial slag deaden ancient fairy magic, driving woodland creatures into mutated frenzy. Conversely, primal curses corrode machinery, rust weapons, and warp flesh.
* **The Stone Curse (Lithification):** Petrification acts as a mutagenic affliction. Flesh turns to slate, onyx, or jade—granting immense physical resilience and immunity to rot, while slowly stripping away agility, warmth, and sanity.
* **The Relic Economy:** Magical artifacts (glass slippers, blood-spindles, skin-cloaks) are hazardous anomalies harvested from apex horrors. Using them always exacts a physical or psychological toll.

### 3.3 The PoC Theatre of Operations: *The Schieferwald (Slate-Weald)*
A quarantined mountain valley cut off from the wider war after a catastrophic siege.

| Node ID | Name | Visual & Atmospheric Identity | Narrative Function |
| :--- | :--- | :--- | :--- |
| **Node 01** | **The Iron Breach** (*Die Eiserne Belagerung*) | Muddy trenches, wooden siege cranes, primitive blast furnaces, and iron drills chewing into ancient, bleeding root systems. | Industrial foothold. Neutral/hostile hub where human deserters and rogue engineers strip-mine the valley. |
| **Node 02** | **The Marrow Kiln** (*Das Knusperhaus*) | Parasitic hut built from petrified, tar-black gingerbread, mortared with bone, teeth, and coagulated glaze, surrounded by hanging iron cages. | Territory of the **Rot-Witch**. Represents predatory folklore feeding on starving soldiers and scavengers. |
| **Node 03** | **The Open-Air Tannery** (*Werkstatt des Häuters*) | Claustrophobic gorge strung with chains, meat hooks, stretched hides, and a soot-choked stove where **The Flayer** stitches living dermis. | Boss arena and high-risk narrative node. The Flayer trades in cursed skins and hunts both stone-skinned and human prey. |
| **Node 04** | **The Chained Mirror** (*Der Versiegelte Spiegel*) | Shattered, overgrown cathedral ruin housing a massive silver mirror bound in heavy iron plates and chains. | Central plot objective of the PoC—the only potential escape route out of the quarantined valley, or the source of its corruption. |

### 3.4 Faction Triangle
* **The Smelter Syndicate:** Pragmatic stone-skinned pioneers and human mercenaries focused on extracting magical marrow and rare ore before the valley collapses.
* **The Court of Rot:** Radicalized remnants of the fairy world (the Witch, the Flayer, feral changelings) waging an asymmetric war of terror against anyone carrying iron.
* **The Mirror-Cutters:** Desperate scholars and treasure hunters trying to unseal the Chained Mirror to escape this dying reality.

---

## 4. Critical Open Questions (Decision Backlog)

Resolve these questions in order and document the outcomes in the `/decisions/` directory before drafting final scripts.

### A. IP Boundaries & Legal Abstraction
- [ ] **Q1 — Direct Fan-Adaptation vs. Original IP:** Do we retain Cornelia Funke’s explicit terminology (*Goyl, Kami'en, Austrien, Tailor*) for a non-commercial portfolio PoC, or abstract the nomenclature into an original grimdark universe so the project is 100% commercially publishable?

### B. Protagonist & Player Agency
- [ ] **Q2 — Fixed Character vs. Custom Vessel:** Does the script follow a pre-defined protagonist with a fixed history, or a customizable vessel defined by their starting origin/affliction (e.g., *Slag-Diver*, *Failed Chimera*, *Guild Liquidator*)?
- [ ] **Q3 — The Death & Failure Loop:** Is death a purely mechanical reset, or is resurrection canonized in the lore (e.g., an iron clockwork splinter in the heart that winds the protagonist back up at the cost of their memories/humanity)?
- [ ] **Q4 — Companion Dynamics:** Does the shapeshifting fox companion from the concept art play an active narrative and mechanical role (dual-perspective scouting, dialogue foil), or does the protagonist operate in strict isolation?

### C. World Logic & Narrative Resolution
- [ ] **Q5 — The Quarantine Barrier:** What physically prevents anyone from walking out of the Schieferwald valley? (e.g., a carnivorous briar wall triggered by a military spell, a toxic alchemical fog ceiling, or geographic collapse).
- [ ] **Q6 — The Climax at the Chained Mirror:** Who sealed the mirror in the cathedral ruins, and what happens when the protagonist finally unseals it at the end of the PoC?

### D. Ludonarrative Translation
- [ ] **Q7 — Primary Interaction Verb:** What does the protagonist spend 70% of their time doing in the script?
  - *Option A:* Fighting, parrying, and surviving spatial hazards (*Soulsborne / Action-RPG* focus)
  - *Option B:* Investigating, negotiating, and navigating faction politics (*CRPG / Narrative* focus)
  - *Option C:* Scavenging, ritual crafting, and high-stakes expeditions (*Survival / Extraction* focus)

---

## 5. Immediate Next Steps (Sprint 1 Backlog)

- [ ] **Task 1:** Initialize GitHub repository, create directory skeleton, and commit `HANDOVER.md`.
- [ ] **Task 2:** Upload generated concept art (`01-iron-breach.jpg`, `02-marrow-kiln.jpg`, `03-the-flayer.jpg`) into `assets/concept-art/`.
- [ ] **Task 3:** Resolve **Q1 (IP Stance)** and log in `decisions/001-ip-nomenclature.md`.
- [ ] **Task 4:** Draft `04-narrative-and-script/protagonist-profile.md` by resolving **Q2, Q3, and Q4**.
- [ ] **Task 5:** Expand `03-theatre-of-operations/factions.md` (define leaders, hubs, philosophies, and quest hooks).
- [ ] **Task 6:** Write the first complete NPC/Boss dossier for **The Flayer (`04-narrative-and-script/character-sheets/the-flayer.md`)** based on the completed concept art.

---

## 6. Phased Roadmap

| Phase | Milestone | Core Objective | Key Deliverables | Exit Criteria |
| :--- | :--- | :--- | :--- | :--- |
| **Phase 1** | **v0.1 — Foundation & Visual Anchor** | Establish tone, visual direction, and core world pillars. | `README.md`, `HANDOVER.md`, `01-vision/*`, initial Concept Art batch. | Clear aesthetic baseline; repository initialized. |
| **Phase 2** | **v0.2 — Systemic Lore & Factions** | Define internal logic of magic, technology, and regional politics. | `02-world-systems/*`, `03-theatre-of-operations/factions.md`. | Every faction and supernatural rule has a clear cause-and-effect relationship. |
| **Phase 3** | **v0.3 — Spatial & Character Bible** | Detail the 4 major landmarks and primary antagonists/NPCs. | `03-theatre-of-operations/nodes/*`, `04-narrative-and-script/character-sheets/*`. | All 4 PoC locations have defined layouts, threats, and narrative hooks. |
| **Phase 4** | **v0.4 — The PoC Narrative Script** | Write chronological plot outline and key branching scenes. | `protagonist-profile.md`, `main-plot-outline.md`, `dialogue-samples/*`. | Complete story arc from entering the valley to the climax at the Chained Mirror. |
| **Phase 5** | **v1.0 — Ludonarrative Pitch Deck** | Map completed narrative to a chosen gameplay loop for prototyping. | `05-ludonarrative-eval/genre-prototypes.md`, finalized Pitch Bible release. | Ready to build a playable text prototype, tabletop test, or engine grey-box. |