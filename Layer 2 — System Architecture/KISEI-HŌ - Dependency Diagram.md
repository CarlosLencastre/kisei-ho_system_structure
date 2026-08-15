# KISEI-HŌ — Dependency Diagram
*Support File — Official Version*
**Version:** 1.1**Date:** August 2026
**Governed by:** KISEI-HŌ - Master Document.md
---
## Document Purpose
This document maps the dependency relationships between all 29 KISEI-HŌ system files.It ensures structural coherence and clarifies how each file interacts with the others.
**This file is governed by the Master Document v1.1 and must remain aligned with:**- System Architecture Map v1.1- Execution Guide v1.1- Developer Guide v1.1
**Note:** This file provides textual dependency mapping. The Execution Guide provides the execution sequence logic. Both files complement each other.
---
## Language Rules v1.1
**All system files are in ENGLISH:**- File names: English- File content: English- Code: English- Therapist outputs: PT-PT- Client outputs: PT-PT or EN (based on anamnesis)- Anamnesis: Clinical terms permitted, transformed via Translation Rules
---
## 1. Master Dependency (Authority)
The **Master Document** governs all 29 files:
Master Document (absolute authority) ├── Layer 1: Foundation (4 files) ├── Layer 2: System Architecture (5 files) ├── Layer 3: PHYSIOCODE (4 files) ├── Layer 4: Analysis (3 files) ├── Layer 5: Prescription (4 files) ├── Layer 6: Output Templates (5 files) ├── Layer 7: Exercise System (1 file) ├── Layer 8: Workflow (1 file) ├── Layer 9: Output Engine (1 file) └── Layer 10: Root (1 file)




**Rule:** No file may contradict the Master Document.

---

## 2. Layer 1 — Foundation Dependencies

Layer 1 files are the authority for all other layers.

### File Dependencies

| File | Depends On | Used By |
|------|------------|---------|
| Master Document | None (authority) | All files |
| Glossary | Master Document | All files |
| Narrative & Persona Guidelines | Master Document, Glossary | All output files |
| Translation Rules | Master Document, Glossary, Narrative Guidelines | PHYSIOCODE, Integrated Analysis, Output Generator |

### Dependency Tree
Master Document ├── Glossary ├── Narrative & Persona Guidelines │ └── (uses Glossary) └── Translation Rules └── (uses Glossary, Narrative Guidelines)




---

## 3. Layer 2 — System Architecture Dependencies

Layer 2 files provide system infrastructure.

| File | Depends On | Used By |
|------|------------|---------|
| System Overview | Master Document | Navigation reference |
| System Architecture Map | Master Document | Architecture reference |
| Dependency Diagram | Master Document | Dependency reference |
| Developer Guide | Master Document, System Architecture Map | Developers |
| Execution Guide | Master Document, Workflow Rules | AI systems, therapists |

### Dependency Tree
Master Document └── Layer 2: System Architecture ├── System Overview ├── System Architecture Map ├── Dependency Diagram ├── Developer Guide └── Execution Guide └── (uses Workflow Rules from Layer 8)




---

## 4. Layer 3 — PHYSIOCODE Dependencies

PHYSIOCODE files process clinical data.

| File | Depends On | Used By |
|------|------------|---------|
| Data Extraction & Classification | Master Document, Glossary, Structural & Energetic Tables | Pattern Integration |
| Pattern Integration | Master Document, Glossary, Energetic Framework | Therapeutic Orientation |
| Therapeutic Orientation | Master Document, Glossary, Unified Prescription Rules | Integrated Analysis |
| Clinical Architecture | Master Document, all Layer 1 files | System documentation |

### Dependency Tree
Master Document └── Layer 3: PHYSIOCODE ├── Data Extraction & Classification │ ├── Glossary (BTL, terminology) │ └── Structural & Energetic Tables ├── Pattern Integration │ ├── Glossary (Flow States, Kyo/Jitsu) │ └── Energetic Framework ├── Therapeutic Orientation │ ├── Glossary (Kyo/Jitsu balance) │ └── Unified Prescription Rules └── Clinical Architecture └── All Layer 1 files




---

## 5. Layer 4 — Analysis Dependencies

Analysis files synthesize findings.

| File | Depends On | Used By |
|------|------------|---------|
| Energetic Framework | Master Document, Glossary | Pattern Integration, Output Generator |
| Structural & Energetic Tables | Master Document, Glossary | Data Extraction, Integrated Analysis |
| Integrated Analysis | Master Document, PHYSIOCODE (all), Translation Rules | Therapeutic Plan, Exercise Plan |

### Dependency Tree
Master Document └── Layer 4: Analysis ├── Energetic Framework │ └── Glossary (Flow States, Kyo/Jitsu, Symbols) ├── Structural & Energetic Tables │ └── Glossary (BTL, terminology) └── Integrated Analysis ├── (uses all PHYSIOCODE outputs) └── Translation Rules




---

## 6. Layer 5 — Prescription Dependencies

Prescription files define safety and planning rules.

| File | Depends On | Used By |
|------|------------|---------|
| Safety & Compliance | Master Document, Narrative Guidelines | All output files, Output Generator |
| Unified Prescription Rules | Master Document, Glossary, Integrated Analysis | Therapeutic Orientation, Output Generator |
| Postural Rehabilitation Rules | Master Document, Structural & Energetic Tables | Template Postural Rehab |
| Safety Rules | Master Document | Historical reference only |

### Dependency Tree
Master Document └── Layer 5: Prescription ├── Safety & Compliance │ └── Narrative Guidelines ├── Unified Prescription Rules │ ├── Glossary (Kyo/Jitsu) │ └── Integrated Analysis ├── Postural Rehabilitation Rules │ └── Structural & Energetic Tables └── Safety Rules (reference only)




---

## 7. Layer 6 — Output Templates Dependencies

Output files generate client and therapist documents.

| File | Depends On | Used By |
|------|------------|---------|
| Templates | Master Document, Narrative Guidelines | Output Generator |
| Therapeutic Plan | Master Document, Integrated Analysis, Safety & Compliance | Therapist Session Guide |
| Exercise Plan | Master Document, Integrated Analysis, Exercise Library | Therapist Session Guide |
| Therapist Session Guide | Master Document, Workflow Rules, Translation Rules | Output Generator |
| Template Postural Rehabilitation Plan | Master Document, Postural Rehabilitation Rules | Therapist documentation |

### Dependency Tree
Master Document └── Layer 6: Output Templates ├── Templates │ └── Narrative Guidelines ├── Therapeutic Plan │ ├── Integrated Analysis │ └── Safety & Compliance ├── Exercise Plan │ ├── Integrated Analysis │ └── Exercise Library ├── Therapist Session Guide │ ├── Workflow Rules │ └── Translation Rules └── Template Postural Rehabilitation Plan └── Postural Rehabilitation Rules




---

## 8. Layer 7 — Exercise System Dependencies

| File | Depends On | Used By |
|------|------------|---------|
| Integrated Exercise Library | Master Document, Energetic Framework | Exercise Plan |

### Dependency Tree
Master Document └── Layer 7: Exercise System └── Integrated Exercise Library └── Energetic Framework (Flow States, Kyo/Jitsu)




---

## 9. Layer 8 — Workflow Dependencies

| File | Depends On | Used By |
|------|------------|---------|
| Workflow Rules | Master Document, all technical files | Execution Guide, all modules |

### Dependency Tree
Master Document └── Layer 8: Workflow └── Workflow Rules └── (governs execution of all files)




---

## 10. Layer 9 — Output Engine Dependencies

| File | Depends On | Used By |
|------|------------|---------|
| Output Generator | Master Document, PHYSIOCODE, Translation Rules, Templates | Final documents |

### Dependency Tree
Master Document └── Layer 9: Output Engine └── Output Generator ├── PHYSIOCODE (all outputs) ├── Translation Rules └── Templates




---

## 11. Layer 10 — Root Dependencies

| File | Depends On | Used By |
|------|------------|---------|
| README | All files | Repository entry |

### Dependency Tree
Master Document └── Layer 10: Root └── README └── (references all files)




---

## 12. Complete Data Flow Dependencies

### Patient Data Input Flow
Anamnesis (clinical terms permitted) ↓ PHYSIOCODE - Data Extraction ↓ Structural & Energetic Tables + Glossary (BTL) ↓ PHYSIOCODE - Pattern Integration ↓ Energetic Framework + Glossary (Flow States, Kyo/Jitsu) ↓ PHYSIOCODE - Therapeutic Orientation ↓ Unified Prescription Rules + Glossary (Kyo/Jitsu balance) ↓ Integrated Analysis ↓ Therapeutic Plan + Safety & Compliance ↓ Exercise Plan + Exercise Library ↓ Therapist Session Guide + Workflow Rules + Translation Rules ↓ Output Generator ↓ Final Documents (PT-PT or EN)




### Client Output Flow
Integrated Analysis ↓ Therapeutic Plan → Client Document 1: Therapeutic Plan Exercise Plan → Client Document 2: Exercise Plan Therapist Session Guide → Therapist Documents Output Generator → Compiled Final Documents




### Therapist Output Flow
Therapist Session Guide ↓ Execution Guide (detailed session plan) ↓ Therapist Document 1: Client Summary Therapist Document 2: Session Execution Plan Therapist Document 3: Session-by-Session Guide




---

## 13. Exclusive Data Source Files (Patient-Specific)

These files are created per patient and depend on system files:

| File | Depends On | Creates |
|------|------------|---------|
| Physiocode & Anamnesis [patient name].pdf | System files | First data input |
| Integrated Analysis [patient name].pdf | Physiocode & Anamnesis | First output |
| Therapeutic Plan [patient name].pdf | Physiocode, Integrated Analysis | Second output |
| Exercise Plan [patient name].pdf | Integrated Analysis, Therapeutic Plan | Third output |

---

## 14. Priority Chain for Conflicts

When two or more modules generate divergent information:

1. **Master Document** — Always prevails
2. **Safety & Compliance** — Overrides narrative style
3. **PHYSIOCODE** — Prevents divergence in clinical modules
4. **Workflow Rules** — Prevails over Translation Rules
5. **Output Generator** — Never modified for exceptions

---

## 15. Version History

| Version | Date | Changes |
|---------|------|---------|
| 1.0 | June 2026 | Initial release — dependency mapping for 21 files |
| 1.1 | August 2026 | Complete reconstruction for 29 files, 10 layers, Advanced Oriental Chiropractic integration (BTL, Flow States, Kyo/Jitsu), language rules v1.1, aligned with Master Document v1.1, System Architecture Map v1.1, Execution Guide v1.1 |

---

## 16. Related Documentation

- **Execution Guide:** Provides execution sequence logic (complements this file)
- **System Architecture Map:** Provides functional hierarchy (complements this file)
- **Developer Guide:** Provides maintenance and expansion rules

---

**End of Dependency Diagram v1.1**