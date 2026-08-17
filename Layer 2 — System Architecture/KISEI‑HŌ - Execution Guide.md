# KISEI-HŌ — Execution Guide
*Technical Execution Manual*
**Version:** 1.1**Date:** August 2026
**Governed by:** KISEI-HŌ - Master Document.md
---
## 1. Document Purpose
This guide defines the deterministic execution order of the **KISEI-HŌ system**.It serves as the technical manual for AI systems (Copilot, GPT, Claude) and therapists, ensuring:- Total consistency between modules- No execution conflicts- Correct sequential pipeline execution- Clear fallback rules- Strict priority and integrity definitions
**This file is governed by the Master Document v1.1 and replaces the previous Dependency Diagram logic.**
**This file must remain aligned with:**- System Architecture Map v1.1- Dependency Diagram v1.1- Developer Guide v1.1- Workflow Rules v1.1
---
## 2. Language Rules v1.1
**All system files are in ENGLISH:**- File names: English- File content: English- Code: English- Therapist outputs: PT-PT- Client outputs: PT-PT or EN (based on anamnesis)- Anamnesis: Clinical, biomechanical, diagnostic, emotional terms **PERMITTED**
---
## 3. Execution Principles
### 3.1 Determinism
The order of modules is strict and immutable.No module may be executed outside the defined sequence.
### 3.2 Integrity
No module may alter the outputs of another module or contradict the **Master Document v1.1**.
### 3.3 Safety
Narrative and language must follow the directives of **Safety & Compliance v1.1** in all phases.
### 3.4 Advanced Oriental Chiropractic
Execution integrates:- **Body Tension Lines (BTL):** Identified in Data Extraction, used in Pattern Integration- **Energetic Flow States:** Assessed in Pattern Integration, translated in Translation Rules- **Kyo/Jitsu Patterns:** Identified in Pattern Integration, balanced in Therapeutic Orientation
---
## 4. Official Execution Order (Complete Pipeline)
[Stage 1: Data Entry] ↓ [Stage 2: Technical Core — PHYSIOCODE (01 → 02 → 03)] ↓ [Stage 3: Clinical Core (Analysis → Plan → Exercises → Session Guide)] ↓ [Stage 4: Operational Core (Workflow → Translation → Prescription → Output Gen)] ↓ [Stage 5: Infrastructure & Final Validation]




### Stage 1 — Entry
Raw data collection:
- Anatomical and biomechanical data
- Energetic data
- Clinical/history records (clinical terms permitted in anamnesis)
- Subjective reports
- Posture and movement observation
- Body Tension Line findings
- Kyo/Jitsu assessment data
- Energetic Flow State assessments

### Stage 2 — Technical Core (PHYSIOCODE)

PHYSIOCODE is **always executed before any clinical module**.

**Step 1: PHYSIOCODE – Data Extraction & Classification**
- **File:** `KISEI-HŌ - PHYSIOCODE - Data Extraction & Classification.md`
- **Function:** Extracts asymmetries, tensions, patterns, and flows
- **Uses:** Structural & Energetic Tables, Glossary (BTL definitions)
- **Output:** Classified structural and energetic data with BTL identification

**Step 2: PHYSIOCODE – Pattern Integration**
- **File:** `KISEI-HŌ - PHYSIOCODE - Pattern Integration.md`
- **Function:** Integrates anatomical and energetic data, identifies global patterns
- **Uses:** Energetic Framework, Glossary (Flow States, Kyo/Jitsu)
- **Output:** Global pattern identification with Flow State and Kyo/Jitsu analysis

**Step 3: PHYSIOCODE – Therapeutic Orientation**
- **File:** `KISEI-HŌ - PHYSIOCODE - Therapeutic Orientation.md`
- **Function:** Generates therapeutic directions for Integrated Analysis and Therapeutic Plan
- **Uses:** Unified Prescription Rules, Glossary (Kyo/Jitsu balance)
- **Output:** Movement qualities and Kyo/Jitsu balancing suggestions

### Stage 3 — Clinical Core

**Step 4: Integrated Analysis**
- **File:** `KISEI-HŌ - Integrated Analysis.md`
- **Function:** Unifies biomechanics, energy, and narrative using PHYSIOCODE outputs
- **Uses:** All PHYSIOCODE outputs, Translation Rules
- **Output:** Synthesized findings including BTL, Flow States, Kyo/Jitsu patterns

**Step 5: Therapeutic Plan**
- **File:** `KISEI-HŌ - Therapeutic Plan.md`
- **Function:** Defines intervention priorities based on Integrated Analysis
- **Uses:** Integrated Analysis, Safety & Compliance
- **Output:** Client-facing therapeutic direction (PT-PT or EN)

**Step 6: Exercise Plan**
- **File:** `KISEI-HŌ - Exercise Plan.md`
- **Function:** Builds exercise proposals aligned with Therapeutic Plan
- **Uses:** Integrated Analysis, Exercise Library
- **Output:** Non-prescriptive movement framework (PT-PT or EN)

**Step 7: Therapist Session Guide**
- **File:** `KISEI-HŌ - Therapist Session Guide.md`
- **Function:** Consolidates the practical session, combining Therapeutic Plan and Exercise Plan
- **Uses:** Therapeutic Plan, Exercise Plan, Workflow Rules, Translation Rules
- **Output:** Detailed session execution plan (PT-PT)

**Step 8: Integrated Exercise Library**
- **File:** `KISEI-HŌ - Integrated Exercise Library.md`
- **Function:** Provides validated exercise database
- **Uses:** Energetic Framework (Flow States, Kyo/Jitsu alignment)
- **Output:** Exercise reference for Exercise Plan

### Stage 4 — Operational Core

**Step 9: Workflow Rules**
- **File:** `KISEI-HŌ - Workflow Rules.md`
- **Function:** Controls execution order, has priority over Translation Rules
- **Output:** Execution sequence enforcement

**Step 10: Translation Rules**
- **File:** `KISEI-HŌ - Translation Rules.md`
- **Function:** Converts technical language into fluid narrative, never alters technical content
- **Uses:** BTL/Flow State/Kyo-Jitsu transformation tables
- **Output:** Narrative-ready content (PT-PT or EN)

**Step 11: Unified Prescription Rules**
- **File:** `KISEI-HŌ - Unified Prescription Rules.md`
- **Function:** Validates cross-output consistency
- **Output:** Prescription validation

**Step 12: Output Generator**
- **File:** `KISEI-HŌ - Output Generator.md`
- **Function:** Compiles and produces the four final documents, is immutable
- **Output:** Final documents (PT-PT or EN)

### Stage 5 — Infrastructure

- **System Architecture Map:** Defines global architecture and dependencies
- **Safety & Compliance:** Guarantees narrative safety and non-prescription
- **Developer Guide:** Defines maintenance, versioning, and expansion rules

---

## 5. Priority and Hierarchy Rules

### 5.1 Priority Chain
Master Document (Absolute Authority) └── 2. Safety & Compliance (Narrative Safety) └── 3. PHYSIOCODE Pipeline (Technical Data) └── 4. Workflow Rules (Execution Sequencing) └── 5. Translation Rules (Language Adaptation) └── 6. Clinical Modules & Output Generator



### 5.2 Priority Rules

1. **Master Document** has absolute priority over the entire system
2. **Safety & Compliance** overrides any narrative style stipulation
3. **PHYSIOCODE** has technical priority over all clinical modules
4. **Workflow Rules** has execution priority over **Translation Rules**
5. **Output Generator** is final and immutable

---

## 6. Fallback Rules (Missing Data)

When patient input presents missing data, the system applies these controlled omission rules:

| Missing Data | Fallback Protocol |
|--------------|-------------------|
| Anatomical Data | Use standard alignment patterns and average vectors |
| Energetic Data | Derive inferences from biomechanical and posture reading |
| Clinical Data | Process via PHYSIOCODE focused on observational data and narrative |
| Subjective Data | Do not invent or assume; maintain strictly neutral and descriptive tone |
| Movement Data | Restrict analysis to static posture assessment |
| BTL Data | Describe tension patterns in accessible terms without technical BTL classification |
| Kyo/Jitsu Data | Describe patterns as "more active" or "less active" without specific terminology |

---

## 7. Conflict Resolution Rules

When two or more modules generate divergent information:

1. **Master Document** always prevails
2. **PHYSIOCODE** prevails over divergences in clinical modules
3. **Workflow Rules** prevails over Translation Rules
4. **Safety & Compliance** prevails over narrative style preferences
5. **Output Generator** is never modified to accommodate exceptions

---

## 8. Input and Output Flow Map

### Inputs
- Anatomical data
- Energetic data
- Clinical data (permitted in anamnesis)
- Subjective data
- Posture and movement observations
- Body Tension Line findings
- Kyo/Jitsu assessment data
- Energetic Flow State assessments

### Final Outputs

**Client Documents (PT-PT or EN):**
- Biomechanical report
- Energy flow map
- Therapeutic plan
- Exercise plan
- Integrated client narrative

**Therapist Documents (PT-PT):**
- Client documents summary
- Detailed session execution plan
- Session-by-session simplification

---

## 9. Language Rules v1.1 in Execution

| Output Type | Language | Transformation |
|-------------|----------|----------------|
| Anamnesis | PT-PT or EN | Clinical terms permitted |
| PHYSIOCODE Output | EN | Classified data |
| Integrated Analysis | EN | Synthesized findings |
| Client Outputs | PT-PT or EN | Narrative style, transformed terminology |
| Therapist Outputs | PT-PT | Technical detail, narrative style |
| BTL Descriptions | EN→PT/EN | Transformed via Translation Rules |
| Flow State Descriptions | EN→PT/EN | Transformed via Translation Rules |
| Kyo/Jitsu Descriptions | EN→PT/EN | Transformed via Translation Rules |

---

## 10. Version and History

- **Version:** `1.1`
- **Status:** Active
- **Last Update:** August 2026
- **Files:** 29 (10 layers)

---

## 11. Related Documentation

- **System Architecture Map:** Functional hierarchy
- **Dependency Diagram:** Complete dependency mapping
- **Workflow Rules:** 8-step pipeline definition
- **Translation Rules:** 8-step transformation pipeline
- **Safety & Compliance:** Safety and ethics rules
- **Glossary v1.1:** BTL, Flow States, Kyo/Jitsu definitions

---

*This document is part of the official infrastructure of the KISEI-HŌ system.*

**End of Execution Guide v1.1**
