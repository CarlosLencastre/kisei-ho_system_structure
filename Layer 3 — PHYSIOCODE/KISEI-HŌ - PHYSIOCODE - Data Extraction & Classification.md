# KISEI-HŌ — PHYSIOCODE - Data Extraction & Classification
(Core File — Official Version)

**Version:** 1.1
**Date:** August 2026

**Governed by:** KISEI-HŌ - Master Document.md

---

## Document Purpose
This file defines the initial stages of the PHYSIOCODE pipeline, focusing on raw data intake and classification.It is governed by the Master Document and must remain aligned with:- Structural & Energetic Tables (BTL definitions, classification)- Energetic Framework (Flow States, Kyo/Jitsu patterns)- PHYSIOCODE Clinical Architecture- Glossary v1.1 (BTL terminology, symbols)- Translation Rules v1.1 (clinical terms transformation)

---

## 📌 Language Rules v1.1
**All system files are in ENGLISH:**- File names: English- File content: English- Code: English- Therapist outputs: PT-PT- Client outputs: PT-PT or EN (based on anamnesis)- **Anamnesis:** Clinical, biomechanical, diagnostic, emotional terms **PERMITTED**
**Clinical terms in anamnesis are permitted** and must be transformed via Translation Rules pipeline before appearing in any output.

---

## 1. Source of Data
All clinical processing begins with the Physiocode & Anamnesis [client name].pdf.This file determines:- the language of all client-facing outputs (PT-PT or EN)- the structural data (angles, deviations, regions)- the energetic data (states, symbols, relationships)- the axis data (Centre, Root, Firmament, Ki Flow)- the session context (history, symptoms, notes)- **Body Tension Line (BTL) findings**- **Kyo/Jitsu assessment data**- **Energetic Flow State assessments**
**Clinical terms are permitted in the anamnesis** (herniated disc, sciatica, scoliosis, chronic pain, etc.).These are transformed via Translation Rules before appearing in narrative outputs.
All .md system files remain in English.

---

## 2. Data Extraction (Step 1)
Extract all raw data from the Physiocode & Anamnesis file:- Structural deviations- Energetic states- Axis behaviour- Session notes- Language setting for output- **Body Tension Line (BTL) findings** — identify physical tension pathways across the body- **Kyo/Jitsu assessment data** — identify deficiency or excess patterns in tissue, organ, or energetic channel- **Energetic Flow State assessments** — assess quality and movement of energy through meridians
**Rule: No interpretation occurs at this stage.****Rule: BTL findings are preserved in raw form for Pattern Integration.****Rule: Kyo/Jitsu patterns are flagged but not yet classified.**

---

## 3. Structural Processing (Step 2)
Using the Structural & Energetic Tables:- Convert angles → direction (+/-)- Convert angles → amplitude (mild / moderate / marked)- Classify structural meaning- Identify protective patterns- Identify compensatory patterns- **Identify Body Tension Line (BTL) involvement** — determine which BTL pathway is affected (Anterior, Posterior, Lateral, or Spiral)- **Describe BTL tension patterns** — map tension from origin to insertion along the BTL
**BTL Identification Rules:**- Anterior BTL: Jaw → Chest → Hip flexors- Posterior BTL: Skull → Spine → Heels- Lateral BTL: Ear → Side body → Foot- Spiral BTL: Diagonal crossing pattern
Dependencies:- Structural & Energetic Tables- Glossary v1.1 (BTL definitions)

---

## 4. Energetic Processing (Step 3)
Using the Energetic Framework:- Classify energetic states (e.g., Normal Flow, Blockage, Excess/Deficiency)- Assign symbols (→, ⨂, ◎, ⊖)- Identify regional energetic patterns- **Assess Energetic Flow States** — determine if energy movement is Smooth Flow, Stagnant Flow, Rebellious Flow, Deficient Flow, or Excess Flow- **Identify Kyo/Jitsu patterns** — classify tissue, organ, or channel state as Kyo (deficiency) or Jitsu (excess)
**Kyo (虚) — Deficiency Pattern:**- Characterized by: hypotonia, depression, weakness on palpation, empty pulse, chronic patterns, cold sensation- Structural indicators: soft, weak, atrophic tissue- Energetic indicators: ⊖ (deficiency symbol), deficient flow
**Jitsu (実) — Excess Pattern:**- Characterized by: hypertonia, tension, fullness on palpation, strong pulse, acute patterns, heat sensation- Structural indicators: tense, resistant, swollen tissue- Energetic indicators: ◎ (excess symbol), excess flow
**Flow State Classification:**| State | Description | Symbol ||-------|-------------|--------|| Smooth Flow | Unobstructed energy movement | → || Stagnant Flow | Partial or complete obstruction | ⨂ || Rebellious Flow | Counter-flow or reverse movement | ⨂ (reversed) || Deficient Flow | Insufficient energy movement | ⊖ || Excess Flow | Congested or overactive movement | ◎ |
Dependencies:- Energetic Framework- Glossary v1.1 (Flow States, Kyo/Jitsu definitions, symbols)

---

## 5. Axis Processing (Step 4)
Using the Energetic Framework:- Assess Centre (spine, core)- Assess Root (lower body connection to ground)- Assess Firmament (upper body connection to space)- Identify axis interactions- **Assess axis correlation with BTL and Flow States** — determine how axis behaviour relates to tension pathways and energy movement- **Assess axis correlation with Kyo/Jitsu patterns** — determine which axis regions show deficiency or excess
Dependencies:- Energetic Framework- Glossary v1.1 (axis terminology)

---

## 6. BTL Processing (Step 5)
**NEW STEP for v1.1 — Body Tension Line Integration**
Using Structural & Energetic Tables and Glossary v1.1:- Map BTL pathways across the body- Identify tension accumulations at BTL junctions- Correlate BTL findings with structural deviations- Correlate BTL findings with energetic states- Correlate BTL findings with Kyo/Jitsu patterns- Prepare BTL data for Pattern Integration
**BTL Mapping Rules:**1. Identify primary BTL involvement (Anterior, Posterior, Lateral, or Spiral)2. Map tension from BTL origin to insertion3. Identify junction points (where BTL crosses joints or crosses other BTLs)4. Correlate with energetic Flow States along the BTL5. Correlate with Kyo/Jitsu patterns at BTL locations
**BTL-Energetic Correlation:**| BTL Location | Flow State | Kyo/Jitsu | Interpretation ||--------------|------------|-----------|----------------|| Upper anterior (chest) | Stagnant Flow | Jitsu | Energy held in upper chest, tension accumulation || Lower posterior (lumbar) | Deficient Flow | Kyo | Energy movement reduced in lower back, depletion || Lateral (side body) | Rebellious Flow | Mixed | Energy moves against natural direction |
Dependencies:- Structural & Energetic Tables- Energetic Framework- Glossary v1.1 (BTL definitions, Flow States)

---

## 7. Output Structure
After Data Extraction & Classification, the following classified data is available:
**Structural Data:**- Classified deviations (direction + amplitude)- Protective and compensatory patterns- **BTL involvement and tension mapping**
**Energetic Data:**- Classified states with symbols- Regional patterns- **Flow State assessments**- **Kyo/Jitsu pattern classifications**
**Axis Data:**- Centre, Root, Firmament assessment- Axis interactions- **Correlation with BTL and Flow States**- **Correlation with Kyo/Jitsu patterns**
**Clinical Data:**- Original anamnesis data (clinical terms preserved)- Notes and observations
**All outputs pass to Pattern Integration for global pattern identification.**

---

## 8. Integration With Pattern Integration
The classified data from Steps 1-5 flows directly to `KISEI-HŌ - PHYSIOCODE - Pattern Integration.md`.
Pattern Integration will:- Combine structural and BTL data- Integrate energetic and Flow State data- Correlate Kyo/Jitsu patterns across regions- Identify global patterns and systemic relationships

---

## 9. Version History
| Version | Date | Changes ||---------|------|---------|| 1.0 | June 2026 | Initial release — 4-step data extraction pipeline || 1.1 | August 2026 | Added Step 5 (BTL Processing), Flow State classification, Kyo/Jitsu pattern classification, clinical terms in anamnesis documented, Glossary v1.1 alignment, language rules v1.1 |

---
**End of Data Extraction & Classification v1.1**