# KISEI-HŌ — System Architecture Map
*Official Architecture Reference — Technical Document*
**Version:** 1.1**Date:** August 2026
**Governed by:** KISEI-HŌ - Master Document.md
---
## 1. Document Purpose
This document defines the official architecture of the **KISEI-HŌ system**, describing the functional hierarchy, internal dependencies, operational flow, and integration of the **PHYSIOCODE pipeline**.It serves as the technical reference for execution, maintenance, and expansion of the method.
**This file is governed by the Master Document v1.1 and must remain aligned with:**- Execution Guide v1.1- Dependency Diagram v1.1- Developer Guide v1.1- Safety & Compliance v1.1
---
## 2. Language Rules v1.1
**All system files are in ENGLISH:**- File names: English- File content: English- Code: English- Therapist outputs: PT-PT- Client outputs: PT-PT or EN (based on anamnesis)- Anamnesis: Clinical terms permitted, transformed via Translation Rules
---
## 3. Global System Structure
The system is composed of **29 files organized into 10 layers**:
| Layer | Name | Files | Purpose ||-------|------|-------|---------|| **Layer 1** | Foundation | 4 | Core identity, philosophy, language rules, governance || **Layer 2** | System Architecture | 5 | System design, dependencies, developer guidelines, execution || **Layer 3** | PHYSIOCODE | 4 | Clinical data processing, pattern recognition, therapeutic orientation || **Layer 4** | Analysis | 3 | Structural and energetic interpretation, integrated findings || **Layer 5** | Prescription | 4 | Safety rules, therapeutic planning, treatment protocols || **Layer 6** | Output Templates | 5 | Document templates for client and therapist outputs || **Layer 7** | Exercise System | 1 | Exercise library and prescription framework || **Layer 8** | Workflow | 1 | Operational pipeline and execution rules || **Layer 9** | Output Engine | 1 | Automated output generation system || **Layer 10** | Root | 1 | Repository entry point and changelog || **TOTAL** | | **29** | |
---
## 4. Functional Hierarchy
The architecture follows a dependency hierarchy that ensures consistency and determinism:
### Priority Order (Highest to Lowest)
1. **Master Document** — Conceptual and linguistic base (authority)2. **Safety & Compliance** — Narrative safety and ethics (security)3. **Glossary** — Terminology consistency (language)4. **Narrative & Persona Guidelines** — Persona and tone (style)5. **Translation Rules** — Data-to-narrative transformation (conversion)6. **PHYSIOCODE** — Technical data processing (processing)7. **Structural & Energetic Tables** — Classification data (classification)8. **Energetic Framework** — Energetic context (context)9. **Workflow Rules** — Execution sequence (sequencing)10. **Unified Prescription Rules** — Prescription validation (validation)11. **Output Generator** — Document production (production)12. **Clinical Modules** — Practical application (application)13. **Infrastructure** — Security, execution, maintenance (infrastructure)
---
## 5. PHYSIOCODE Integrated Pipeline
The PHYSIOCODE pipeline operates in **three sequential phases**:
### Phase 1: Data Extraction- **File:** `KISEI-HŌ - PHYSIOCODE - Data Extraction & Classification.md`- **Function:** Extracts asymmetries, patterns, tensions, and flows- **Uses:** Structural & Energetic Tables, Glossary (BTL definitions)- **Output:** Classified structural and energetic data
### Phase 2: Pattern Integration- **File:** `KISEI-HŌ - PHYSIOCODE - Pattern Integration.md`- **Function:** Integrates anatomical and energetic data- **Uses:** Energetic Framework, Glossary (Flow States, Kyo/Jitsu)- **Output:** Global pattern identification with BTL and Flow State integration
### Phase 3: Therapeutic Orientation- **File:** `KISEI-HŌ - PHYSIOCODE - Therapeutic Orientation.md`- **Function:** Generates therapeutic directions for Integrated Analysis and Therapeutic Plan- **Uses:** Unified Prescription Rules, Glossary (Kyo/Jitsu balance)- **Output:** Movement qualities and Kyo/Jitsu balancing suggestions
---
## 6. Dependency Flow
Entry → Technical Core → Clinical Core → Output

Entry: Anamnesis Data (clinical terms permitted) ↓ Technical Core (PHYSIOCODE): Data Extraction → Pattern Integration → Therapeutic Orientation Uses: Structural & Energetic Tables, Energetic Framework, Glossary ↓ Clinical Core: Integrated Analysis → Therapeutic Plan → Exercise Plan → Therapist Session Guide Uses: Translation Rules, Safety & Compliance, Unified Prescription Rules ↓ Output: Output Generator → Final Documents (PT-PT or EN)




---

## 7. Module Interaction Map

### Core Interactions
Master Document ↓ governs all files

Glossary ↔ Narrative Guidelines ↔ Translation Rules ↓ all depend on Master Document

PHYSIOCODE (3 modules) ↓ outputs to Integrated Analysis ↓ outputs to Therapeutic Plan → Exercise Plan → Therapist Session Guide ↓ all use Output Generator → Final Documents

Workflow Rules ↓ controls execution sequence for All modules




### Output Flow
Integrated Analysis (client report + energy flow) ↓ Therapeutic Plan (client-facing therapeutic direction) ↓ Exercise Plan (non-prescriptive movement framework) ↓ Therapist Session Guide (detailed session execution) ↓ Output Generator ↓ Final Documents (PT-PT or EN based on anamnesis)




---

## 8. Input and Output Map

### Inputs
- Anatomical data
- Energetic data
- Clinical data (permitted in anamnesis)
- Subjective reports
- Posture observations
- Movement observations
- Body Tension Line findings
- Kyo/Jitsu assessment data
- Energetic Flow State assessments

### Outputs

**Client Documents:**
- Evaluation Report (structural/energetic synthesis)
- Energy Flow Map
- Therapeutic Plan
- Exercise Plan

**Therapist Documents:**
- Client Document Summary
- Detailed Session Execution Plan
- Session-by-Session Simplification

---

## 9. Priority Rules

1. **Master Document** has absolute priority
2. **Safety & Compliance** overrides narrative style
3. **PHYSIOCODE** has priority over clinical modules
4. **Workflow Rules** has priority over Translation Rules
5. **Output Generator** is immutable
6. **Translation Rules** never alters technical content

---

## 10. Integrity Rules

- No module may contradict the **Master Document**
- No module may alter outputs from another module
- **PHYSIOCODE** is always executed before any clinical module
- **Translation Rules** never alters technical content
- **Safety & Compliance** has priority over narrative
- **Output Generator** is immutable

---

## 11. Advanced Oriental Chiropractic Integration

The architecture integrates **Advanced Oriental Chiropractic** principles:

### Terminology Integration (Glossary v1.1)
- **Body Tension Lines (BTL):** Physical tension pathways across the body
- **Energetic Flow States:** Quality and movement of energy through meridians
- **Kyo (虚):** Deficiency pattern — empty, weak, insufficient
- **Jitsu (実):** Excess pattern — full, tense, congested
- **Sōtai:** Japanese structural balancing technique
- **Energetic Principles:** Governing rules of energy movement and balance

### Pipeline Integration
- **Data Extraction:** Identifies BTL pathways and Flow States
- **Pattern Integration:** Maps Kyo/Jitsu patterns across the body
- **Therapeutic Orientation:** Balances Kyo/Jitsu through appropriate interventions
- **Translation Rules:** Transforms clinical terms (BTL, Flow States, Kyo/Jitsu) into narrative

---

## 12. Language Rules v1.1 Architecture

| Type | Language | Rule |
|------|----------|------|
| System Files (.md) | EN | All content in English |
| Code | EN | Variables, functions, comments in English |
| Anamnesis | PT-PT or EN | Clinical, biomechanical, diagnostic, emotional terms permitted |
| Therapist Outputs | PT-PT | Full technical detail, clinical terminology after transformation |
| Client Outputs | PT-PT or EN | Narrative style, accessible language, transformed terminology |

---

## 13. Version and Update Rules

This document defines the official architecture.
Any structural change must be recorded here.
The **Developer Guide** explains versioning and expansion procedures.

---

## 14. Version History

| Version | Date | Changes |
|---------|------|---------|
| 1.0 | June 2026 | Initial release — 5 functional layers, 21 modules |
| 1.1 | August 2026 | Updated to 10 layers, 29 files, Advanced Oriental Chiropractic integration, BTL and Flow States terminology, Kyo/Jitsu pipeline integration, language rules v1.1, Safety & Compliance v1.1 alignment, full dependency reconstruction |

---

**End of System Architecture Map v1.1**
