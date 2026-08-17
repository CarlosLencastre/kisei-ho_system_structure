# KISEI-HŌ System — Unified Workspace & Reference Manual
**Version:** 1.2  
**Date:** August 2026  
**Governed by:** KISEI-HŌ - Master Document.md  

---

## 1. System Overview & Architecture

KISEI-HŌ is an advanced manual therapy system that integrates Japanese traditional somatic concepts with high-level structural and biomechanical analysis. The system processes raw postural data from the **PHYSIOCODE Anatomic Study** alongside clinical and biographical anamnesis to generate humanized, deeply resonant, and structurally sound patient documentation and therapeutic plans.

### The Core Paradigm
*   **The Base (Sokushindo):** Stabilizing feet and ankles to send safety cues to the nervous system.
*   **The Center (Hara & Ampuku):** Reorganizing the pelvis and releasing visceral tension.
*   **The Crown (Sōtai & Ori):** Aligning the spine, shoulders, and cranio-cervical axis through comfort and sensory integration.
*   **Advanced Oriental Chiropractic:** Diagnostic lens mapping physical torsion patterns alongside energetic meridians.

---

## 2. Global System Dependency Diagram

graph TD
    %% Base Master Governance
    MASTER[10 — Master Document.md] --> PHYSIO[01 — PHYSIOCODE Clinical Architecture.md]
    MASTER --> TABLES[02 — Structural & Energetic Tables.md]
    MASTER --> EN_READ[03 — Energetic Reading Criteria.md]
    MASTER --> MAP_INT[04 — Energetic Map Interpretation.md]
    MASTER --> RULES[05 — Internal Workflow & Safety Rules.md]
    
    %% Clinical Processing & Analysis
    PHYSIO --> IA[11 — Integrated Analysis.md]
    PHYSIO --> OUT_GEN[12 — Output Generator.md]
    PHYSIO --> SESS_GUIDE[06 — Therapist Session Guide.md]
    
    TABLES --> IA
    TABLES --> OUT_GEN
    
    EN_READ --> MAP_INT
    EN_READ --> IA
    EN_READ --> OUT_GEN
    
    MAP_INT --> IA
    MAP_INT --> OUT_GEN
    
    RULES --> SESS_GUIDE
    RULES --> OUT_GEN
    RULES --> THER_PLAN[09 — Therapeutic Plan.md]
    RULES --> TEMPLATES[08 — Templates.md]
    
    %% Language, Persona & Prescriptions
    GLOSSARY[14 — Glossary.md] --> ALL_FILES((All System Files))
    PERSONA[13 — Persona, Method & Body Reading Criteria.md] --> IA
    PERSONA --> OUT_GEN
    PERSONA --> TEMPLATES
    
    HUMAN_GUIDE[Humanization Guidelines] --> OUT_GEN
    HUMAN_GUIDE --> TEMPLATES
    HUMAN_GUIDE --> THER_PLAN
    
    TRANS_RULES[15 — Translation Rules.md] --> OUT_GEN
    TRANS_RULES --> TEMPLATES
    TRANS_RULES --> THER_PLAN
    
    PRES_RULES[Unified Prescription Rules] --> EX_LIB[07 — Exercise Library]
    PRES_RULES --> OUT_GEN
    PRES_RULES --> THER_PLAN
    
    %% Final Deliverables and Planning
    TEMPLATES --> OUT_GEN
    TEMPLATES --> IA
    TEMPLATES --> THER_PLAN
    
    EX_LIB --> THER_PLAN
    IA --> THER_PLAN

---

## 3. Reference Index of System Files
All system files are categorized into 5 operational layers to ensure absolute modularity, safety, and coherence.

### Layer 1: Core Architecture (Foundation)
*   **01 — KISEI-HŌ — PHYSIOCODE Clinical Architecture.md:** Defines the biomechanical threshold parameters (using $\approx$ notation) to map angles into adaptive categories.
*   **02 — KISEI-HŌ — Structural & Energetic Tables.md:** The primary metric dictionary translating physical measurements and symbols (⨂, ◎, ⊖) safely.
*   **03 — KISEI-HŌ — Energetic Reading Criteria.md:** Establishes regional and global energetic mapping parameters.
*   **04 — KISEI-HŌ — Energetic Map Interpretation.md:** Governs flow dynamics, directionality, and systemic relationships.
*   **05 — KISEI-HŌ — Internal Workflow & Safety Rules.md:** Sets operational constraints and nervous system safety guidelines.

### Layer 2: Therapist & Session Framework
*   **06 — KISEI-HŌ — Therapist Session Guide.md:** Step-by-step clinical execution protocol for physical sessions.
*   **07 — KISEI-HŌ — Exercise Library (Integrated).md:** The therapeutic movement index categorized by structural and energetic intentions.
*   **08 — KISEI-HŌ — Templates.md:** Clean, safe templates using `$\approx$` to prevent rendering conflicts.
*   **09 — KISEI-HŌ — Therapeutic Plan.md:** Guidelines for formulating non-prescriptive, supportive home plans.

### Layer 3: Master System Files
*   **10 — KISEI-HŌ — Master Document.md:** Overarching system governor defining global parameters and ethical baselines.
*   **11 — KISEI-HŌ — Integrated Analysis.md:** The structural-energetic correlation protocols translating biomechanics to bodily narratives.
*   **12 — KISEI-HŌ — Output Generator.md:** Automated engine rules for parsing raw data into beautifully structured client outputs.

### Layer 4: Language, Persona & Translation
*   **13 — KISEI-HŌ — Persona, Method & Body Reading Criteria.md:** Establishes the non-clinical, supportive voice of KISEI-HŌ.
*   **14 — KISEI-HŌ — Glossary.md:** Universal terminology guide (Ki, Hara, Sokushindo, Ampuku, Sōtai, Ori, Kyo, Jitsu).
*   **15 — KISEI-HŌ — Translation Rules.md (v1.1 updated):** Governs the 8-step pipeline converting clinical raw data into humanized client prose.

### Layer 5: Client-Facing Outputs (Final Generation)
*   **KISEI-DYNAMIC-UNIVERSAL-V1 (Dynamic Postural Analysis):** Physical alignment narrative mapped through `$\approx$`.
*   **KISEI-MAP-ENERGY-V1 (Energy Flow Map):** Inner energy mapping, including Kyo/Jitsu qualities and the *Domino Chain* of tension.
*   **KISEI-MAP-EXERCISE-V1 (Exercise Program for Harmonization):** The personalized movement sequence structured under the KISEI-HŌ hierarchy (Base $\rightarrow$ Center $\rightarrow$ Crown).

---

## 4. Crucial Mathematical Rendering Rule (LaTeX Compliance)
To prevent the Markdown parser from interpreting approximations as strikethrough/striked text (`~~` formatting conflicts), **always use the LaTeX math notation `$\approx$`** to render approximation signs in both therapist and patient files. 

*   **Wrong:** `~5.2°` or `~-6.4°` (Creates broken, strikethrough text on UI platforms)
*   **Right:** `$\approx$ 5.2°` or `$\approx$ -6.4°` (Renders a perfect double-tilde approximation symbol: $\approx$)

---
**End of README.md v1.2**
