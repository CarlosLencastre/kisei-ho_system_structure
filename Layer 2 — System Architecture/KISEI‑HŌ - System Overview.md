# KISEI-HŌ — System Overview
*Central Documentation Hub — For AI and Therapist Use*
**Version:** 1.1**Date:** August 2026
**Governed by:** KISEI-HŌ - Master Document.md
---
## Document Purpose
This document serves as the central hub for understanding the KISEI-HŌ system structure, dependencies, and file organization.It provides the complete registry of 29 files across 10 layers for system navigation, dependency tracking, and version control.
**This file is governed by the Master Document v1.1 and must remain aligned with:**- System Architecture Map v1.1- Dependency Diagram v1.1- Developer Guide v1.1- Execution Guide v1.1
---
## 📌 Language Rules v1.1
**Critical:** All system files (.md) are in **ENGLISH**.- **File names:** All in English- **File content:** All in English- **Code:** All in English- **Therapist outputs:** PT-PT- **Client outputs:** PT-PT or EN (based on anamnesis)
---
## 🏗️ System Architecture — 10 Layers, 29 Files
### Layer 1 — Foundation (4 files)Core identity, philosophy, language rules, and operational coherence.
| # | File | Purpose | Dependencies ||---|------|---------|--------------|| 1 | `KISEI-HŌ - Master Document.md` | Defines identity, architecture, narrative rules, governance | None (master authority) || 2 | `KISEI-HŌ - Glossary.md` | Terminology, symbols, Kyo/Jitsu definitions, BTL, Flow States | Master Document || 3 | `KISEI-HŌ - Narrative & Persona Guidelines.md` | Persona, tone, body-reading criteria, forbidden terms | Master Document || 4 | `KISEI-HŌ - Translation Rules.md` | 8-step pipeline for clinical-to-narrative transformation | Master Document, Glossary, Narrative Guidelines |
### Layer 2 — System Architecture (5 files)System design, dependencies, developer guidelines, and execution rules.
| # | File | Purpose | Dependencies ||---|------|---------|--------------|| 5 | `KISEI-HŌ - System Overview.md` | Central hub for system navigation (this file) | Master Document || 6 | `KISEI‑HŌ System Architecture Map.md` | Functional hierarchy, internal dependencies, pipeline integration | Master Document || 7 | `KISEI-HŌ - Dependency Diagram.md` | Complete dependency map of all 29 files | Master Document || 8 | `KISEI‑HŌ - Developer Guide.md` | Maintenance, versioning, expansion rules | Master Document, Architecture Map || 9 | `KISEI‑HŌ - Execution Guide.md` | Deterministic execution order, priority rules, fallback | Master Document, Workflow Rules |
### Layer 3 — PHYSIOCODE (4 files)Clinical data processing, pattern recognition, and therapeutic orientation.
| # | File | Purpose | Dependencies ||---|------|---------|--------------|| 10 | `KISEI-HŌ - PHYSIOCODE - Data Extraction & Classification.md` | Data intake, structural/energetic classification | Master Document, Glossary, Structural & Energetic Tables || 11 | `KISEI-HŌ - PHYSIOCODE - Pattern Integration.md` | Global pattern identification, BTL integration, Flow States | Master Document, Energetic Framework, Glossary || 12 | `KISEI-HŌ - PHYSIOCODE - Therapeutic Orientation.md` | Movement qualities, Kyo/Jitsu balancing | Master Document, Unified Prescription Rules, Glossary || 13 | `KISEI-HŌ - PHYSIOCODE - - Clinical Architecture.md` | PHYSIOCODE framework documentation | Master Document, all Layer 1 files |
### Layer 4 — Analysis (3 files)Structural and energetic interpretation, integrated findings.
| # | File | Purpose | Dependencies ||---|------|---------|--------------|| 14 | `KISEI-HŌ - Energetic Framework.md` | Energy states, Flow States, global patterns, Kyo/Jitsu | Master Document, Glossary || 15 | `KISEI‑HŌ - Structural & Energetic Tables.md` | Structural deviation classification, BTL descriptions | Master Document, Glossary || 16 | `KISEI-HŌ - Integrated Analysis.md` | Unified synthesis of structural, energetic, axis findings | Master Document, PHYSIOCODE, Translation Rules |
### Layer 5 — Prescription (4 files)Safety rules, therapeutic planning, and treatment protocols.
| # | File | Purpose | Dependencies ||---|------|---------|--------------|| 17 | `KISEI‑HŌ - Safety & Compliance.md` | Safety rules, ethics, forbidden terms (allowed in anamnesis) | Master Document, Narrative Guidelines || 18 | `KISEI-HŌ - Unified Prescription Rules.md` | Movement orientation logic, prescription consistency | Master Document, Glossary, Integrated Analysis || 19 | `KISEI‑HŌ - Postural Rehabilitation Rules.md` | Postural correction principles, alignment rules | Master Document, Structural & Energetic Tables || 20 | `KISEI-HŌ - Safety Rules.md` | Historical safety documentation | Master Document (reference only) |
### Layer 6 — Output Templates (5 files)Document templates for client and therapist outputs.
| # | File | Purpose | Dependencies ||---|------|---------|--------------|| 21 | `KISEI-HŌ - Templates.md` | Standardized output structures, formatting rules | Master Document, Narrative Guidelines || 22 | `KISEI-HŌ - Therapeutic Plan.md` | Client-facing therapeutic direction | Master Document, Integrated Analysis, Safety & Compliance || 23 | `KISEI-HŌ - Exercise Plan.md` | Non-prescriptive movement framework | Master Document, Integrated Analysis, Exercise Library || 24 | `KISEI-HŌ - Therapist Session Guide.md` | 6-phase session structure, execution details | Master Document, Workflow Rules, Translation Rules || 25 | `KISEI‑HŌ - Template Postural Rehabilitation Plan.md` | Postural rehabilitation template | Master Document, Postural Rehabilitation Rules |
### Layer 7 — Exercise System (1 file)Exercise library and prescription framework.
| # | File | Purpose | Dependencies ||---|------|---------|--------------|| 26 | `KISEI-HŌ - Integrated Exercise Library.md` | Movement categories, energetic alignment, BTL exercises | Master Document, Energetic Framework |
### Layer 8 — Workflow (1 file)Operational pipeline and execution rules.
| # | File | Purpose | Dependencies ||---|------|---------|--------------|| 27 | `KISEI-HŌ - Workflow Rules.md` | Mandatory 8-step pipeline, execution sequence | Master Document, all technical files |
### Layer 9 — Output Engine (1 file)Automated output generation system.
| # | File | Purpose | Dependencies ||---|------|---------|--------------|| 28 | `KISEI-HŌ - Output Generator.md` | Automates narrative generation, compiles final documents | Master Document, PHYSIOCODE, Translation Rules, Templates |
### Layer 10 — Root (1 file)Repository entry point and changelog.
| # | File | Purpose | Dependencies ||---|------|---------|--------------|| 29 | `README.md` | System introduction, file navigation, version history | All files |
---
## 📊 Complete File Registry (29 Files)
| Layer | Files | Count ||-------|-------|-------|| Layer 1 — Foundation | Master Document, Glossary, Narrative Guidelines, Translation Rules | 4 || Layer 2 — System Architecture | System Overview, Architecture Map, Dependency Diagram, Developer Guide, Execution Guide | 5 || Layer 3 — PHYSIOCODE | Data Extraction, Pattern Integration, Therapeutic Orientation, Clinical Architecture | 4 || Layer 4 — Analysis | Energetic Framework, Structural & Energetic Tables, Integrated Analysis | 3 || Layer 5 — Prescription | Safety & Compliance, Unified Prescription Rules, Postural Rehabilitation Rules, Safety Rules | 4 || Layer 6 — Output Templates | Templates, Therapeutic Plan, Exercise Plan, Therapist Session Guide, Template Postural Rehab | 5 || Layer 7 — Exercise System | Integrated Exercise Library | 1 || Layer 8 — Workflow | Workflow Rules | 1 || Layer 9 — Output Engine | Output Generator | 1 || Layer 10 — Root | README | 1 || **TOTAL** | | **29** |
---
## 🗺️ Dependency Diagram — Simplified
### Layer 1 Dependencies (Foundation)
Master Document (authority) ├── Glossary ├── Narrative & Persona Guidelines └── Translation Rules




### Layer 2 Dependencies (Architecture)
System Overview (navigation hub) ├── Architecture Map ├── Dependency Diagram ├── Developer Guide └── Execution Guide




### Layer 3 Dependencies (PHYSIOCODE)
Data Extraction & Classification └── Pattern Integration └── Therapeutic Orientation




### Pipeline Flow
Input → PHYSIOCODE → Integrated Analysis → Therapeutic Plan → Exercise Plan → Therapist Session Guide → Output Generator → Final Documents ↓ ↓ ↓ Structural & Translation Safety & Energetic Tables Rules Compliance




---

## 🔑 Key Integration Points

### Advanced Oriental Chiropractic Integration
- **Glossary v1.1:** BTL, Flow States, Kyo/Jitsu, Sōtai, Oriental Structural Terminology
- **Narrative Guidelines v1.1:** Kyo/Jitsu body-reading, BTL descriptions
- **Translation Rules v1.1:** BTL/Flow State/Kyo-Jitsu transformation rules

### Language Rules v1.1 Integration
- **System files:** EN only
- **Code:** EN only
- **Therapist outputs:** PT-PT
- **Client outputs:** PT-PT or EN
- **Anamnesis:** Clinical terms permitted, transformed via Translation Rules

### Safety & Compliance v1.1 Integration
- **Forbidden terms:** Allowed in anamnesis, transformed in outputs
- **Narrative safety:** All outputs follow Narrative & Persona Guidelines
- **Non-prescription:** Outputs never prescribe or diagnose

---

## 📌 How to Use This File

1. **For AI Navigation:** Use `document_id` URLs to access files via library_fetch
2. **For Therapists:** Use as reference for system structure and file location
3. **For Developers:** Use for dependency tracking and version control
4. **For Updates:** Record all changes in the Changelog section

---

## 🔗 Quick Access Links

| File | GitHub URL |
|------|------------|
| Master Document | `https://github.com/CarlosLencastre/kisei-ho_system_structure/blob/main/KISEI-H%C5%8C%20-%20Master%20Document.md` |
| Glossary | `https://github.com/CarlosLencastre/kisei-ho_system_structure/blob/main/KISEI-H%C5%8C%20-%20Glossary.md` |
| Narrative Guidelines | `https://github.com/CarlosLencastre/kisei-ho_system_structure/blob/main/KISEI-H%C5%8C%20-%20Narrative%20%26%20Persona%20Guidelines.md` |
| Translation Rules | `https://github.com/CarlosLencastre/kisei-ho_system_structure/blob/main/KISEI-H%C5%8C%20-%20Translation%20Rules.md` |
| Workflow Rules | `https://github.com/CarlosLencastre/kisei-ho_system_structure/blob/main/KISEI-H%C5%8C%20-%20Workflow%20Rules.md` |
| Safety & Compliance | `https://github.com/CarlosLencastre/kisei-ho_system_structure/blob/main/KISEI%E2%80%91H%C5%8C%20-%20Safety%20%26%20Compliance.md` |
| Output Generator | `https://github.com/CarlosLencastre/kisei-ho_system_structure/blob/main/KISEI-H%C5%8C%20-%20Output%20Generator.md` |

---

## 📋 Version History

| Version | Date | Changes |
|---------|------|---------|
| 1.0 | June 2026 | Initial release — 21 files, 6 categories |
| 1.1 | August 2026 | Updated to 29 files, 10 layers, Advanced Oriental Chiropractic integration, language rules v1.1, BTL and Flow States terminology, Kyo/Jitsu integration, aligned with Master Document v1.1, Glossary v1.1, Narrative Guidelines v1.1, Translation Rules v1.1, Safety & Compliance v1.1 |

---

**IMPORTANT:** This file must be updated after all other files have their final versions confirmed.
This file serves as the central navigation reference for the entire KISEI-HŌ system.

---

**End of System Overview v1.1**