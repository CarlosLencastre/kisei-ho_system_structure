# KISEI-HŌ v1.1 Update Log — Layer 1: Foundation

## Status: Layer 1 complete, pending your validation before Layer 2

---

## 1. Files updated in this pass
- KISEI-HŌ - Glossary.md
- KISEI-HŌ - Narrative & Persona Guidelines.md
- KISEI-HŌ - Translation Rules.md
- KISEI‑HŌ - System Architecture Map.md
- KISEI-HŌ - Safety Rules.md
- KISEI-HŌ - Safety & Compliance.md
- KISEI-HŌ - Narrative & Persona Guidelines.md
- KISEI‑HŌ - Execution Guide.md
- 

## 2. Changes applied
**Glossary**: added the 8 new terms (Advanced Oriental Chiropractic, Sōtai, Energetic Principles, Oriental Structural Terminology, Body Tension Lines, Energetic Flow States, Kyo, Jitsu), no acronyms introduced, governance list now points to Safety & Compliance rather than Safety Rules, added a Term Change Log.

**Narrative & Persona Guidelines**: added a "Conceptual Foundation" section naming Advanced Oriental Chiropractic as the narrative's root without letting that term leak into patient-facing text; folded Kyo/Jitsu into the body-reading criteria; tightened the forbidden-terms list to explicitly include "joint" and "spine curvature" (previously only implied); governance list updated to Safety & Compliance.

**Translation Rules**: added an explicit Section 0 separating the two language rules that were previously only implicit — system files are English-only; only client-facing PDF outputs switch between PT-PT/EN based on the patient's Physiocode data.

---

## 3. Structural issues found that will affect later layers

These aren't something I can quietly patch inside a single file — they need a decision from you before I touch the layers where they live, because the "fix" changes depending on which file you treat as authoritative.

**a) Four files are currently written in Portuguese**: Safety & Compliance, Developer Guide, Execution Guide, System Architecture Map. Global Rule 1 requires all `.md` files to be exclusively English. That means these four need a full translation, not a light edit — I want to confirm you want that done as literal translation (preserving the Portuguese examples like "❌ Incorrecto / ✔️ Correcto" as English "Incorrect / Correct" pairs) before I commit to wording, since nuance matters in a safety document.

**b) Two pipeline models don't match.** Master Document, Output Generator, PHYSIOCODE files and the README all reference an **8-step PHYSIOCODE pipeline** (Data Extraction → Structural → Energetic → Axis → Integrated Pattern Reading → Narrative Translation → Therapeutic Orientation → Safety Validation). Workflow Rules, however, defines a **6-stage pipeline** (Data Acquisition → Mapping → Integrated Analysis → Priority Definition → Plan Construction → Safety & Narrative Integration) with different stage names and internal logic (BTL, priority tiers, phase allocation) that doesn't map 1:1 onto the 8 steps. Section 8.1 of your spec says "confirm official 8-step pipeline" for Workflow Rules — that implies Workflow Rules should be rewritten to express its content *through* the 8-step structure rather than its own 6-stage one. That's a substantive rewrite, not a find-and-replace.

**c) File/layer counts disagree across three files.** README states 29 files / 10 layers. System Overview currently lists 21 files / 7 categories. System Architecture Map currently lists 21 modules / 5 layers and doesn't mention Integrated Exercise Library or Template Postural Rehabilitation Plan at all. Both need restructuring to match README's 10-layer model — I'll use README as source of truth per your reverse-engineering rule, since it's the most recently structured.

**d) Two safety files with overlapping authority.** Safety Rules.md and Safety & Compliance.md both currently claim to govern forbidden language, and Safety & Compliance says it "substitutes in totality" Safety Rules — but Safety Rules is still listed as a live dependency in most other files' headers. Spec Section 5.4 wants Safety Rules marked historical; I'll add a deprecation header pointing to Safety & Compliance, and Layer 5 will need to update every file that currently cites "Safety Rules" in its header to cite "Safety & Compliance" instead.

---

## 4. Proposed next step

Layer 2 (System Architecture: Master Document, System Overview, System Architecture Map, Dependency Diagram, Developer Guide) is where (b) and (c) above actually get resolved — it's the biggest single layer in the spec. Before I draft it: do you want the Portuguese→English translation of Safety & Compliance / Developer Guide / Execution Guide / System Architecture Map done as part of Layer 2/5, or would you rather review Layer 1 first and handle translation as its own separate pass?
