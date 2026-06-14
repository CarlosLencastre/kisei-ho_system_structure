# KISEI-HŌ — System Overview
*Central Documentation Hub — For AI and Therapist Use*

This document serves as the central hub for understanding the KISEI-HŌ system structure, dependencies, and file organization. Use it to:
- Navigate the system: Find and access files via Library calls.
- Understand dependencies: Review how files interact.
- Track changes: See updates to the system.

This file is governed by the Master Document and integrates:
- Dependency Diagram (for structural relationships).
- System Files Index (for file listings).

---
## 📚 Complete File List by Category

### 1. Master
   File | document_id | Purpose | Dependencies |
 |------|-------------|---------|--------------|
 | KISEI-HŌ - Master Document.md | *(Use Library call)* | Governs the entire system. | None |

### 2. Foundation
 | File | document_id | Purpose | Dependencies |
 |------|-------------|---------|--------------|
 | KISEI-HŌ - Narrative & Persona Guidelines.md | *(Use Library call)* | Defines persona, tone, and body reading criteria. | Master Document |
 | KISEI-HŌ - Glossary.md | *(Use Library call)* | Central repository for terms. | Master Document |

### 3. Clinical Architecture
 | File | document_id | Purpose | Dependencies |
 |------|-------------|---------|--------------|
 | KISEI-HŌ - PHYSIOCODE - Data Extraction & Classification.md | *(Use Library call)* | Data intake and structural/energetic classification. | Master Document, Structural & Energetic Tables |
 | KISEI-HŌ - PHYSIOCODE - Pattern Integration.md | *(Use Library call)* | Global pattern identification. | Master Document, Energetic Framework |
 | KISEI-HŌ - PHYSIOCODE - Therapeutic Orientation.md | *(Use Library call)* | Movement qualities and suggestions. | Master Document, Unified Prescription Rules |
 | KISEI-HŌ - Structural & Energetic Tables.md | *(Use Library call)* | Classifies structural deviations and energetic states. | Master Document |
 | KISEI-HŌ - Energetic Framework.md | *(Use Library call)* | Defines energetic states, global patterns, and regional application. | Master Document |
 | KISEI-HŌ - Workflow Rules.md | *(Use Library call)* | Mandatory 8-step pipeline. | Master Document |
 | KISEI-HŌ - Safety Rules.md | *(Use Library call)* | Forbidden language and tone constraints. | Master Document |

### 4. Interpretation
 | File | document_id | Purpose | Dependencies |
 |------|-------------|---------|--------------|
 | KISEI-HŌ - Translation Rules.md | *(Use Library call)* | 3-stage pipeline for narrative translation. | Master Document, PHYSIOCODE |
 | KISEI-HŌ - Integrated Analysis.md | *(Use Library call)* | Unifies structural, energetic, and axis findings. | Master Document, PHYSIOCODE |

### 5. Output Templates
 | File | document_id | Purpose | Dependencies |
 |------|-------------|---------|--------------|
 | KISEI-HŌ - Integrated Analysis.md | *(Use Library call)* | Master output: structural/energetic/axis synthesis. | Master Document, PHYSIOCODE |
 | KISEI-HŌ - Therapeutic Plan.md | *(Use Library call)* | Client-facing therapeutic direction. | Master Document, Integrated Analysis |
 | KISEI-HŌ - Exercise Plan.md | *(Use Library call)* | Non-prescriptive movement framework. | Master Document, Integrated Analysis |
 | KISEI-HŌ - Therapist Session Guide.md | *(Use Library call)* | 6-phase session structure. | Master Document, Workflow Rules |

### 6. Library/Support
 | File | document_id | Purpose | Dependencies |
 |------|-------------|---------|--------------|
 | KISEI-HŌ - Integrated Exercise Library.md | *(Use Library call)* | Movement categories and energetic alignment. | Master Document, Energetic Framework |
 | KISEI-HŌ - Templates.md | *(Use Library call)* | Standardized output structures. | Master Document |
 | KISEI-HŌ - Unified Prescription Rules.md | *(Use Library call)* | Movement orientation logic. | Master Document, Integrated Exercise Library |

### 7. Output System
 | File | document_id | Purpose | Dependencies |
 |------|-------------|---------|--------------|
 | KISEI-HŌ - Output Generator.md | *(Use Library call)* | Automates narrative generation. | Master Document, PHYSIOCODE, Translation Rules |

---
## 🗺️ Dependency Diagram

### Master Document
- Governs: All files (see file list above).

### PHYSIOCODE Sub-Files
- Data Extraction & Classification → Pattern Integration → Therapeutic Orientation
- All depend on: Master Document, Structural & Energetic Tables, Energetic Framework

### Energetic Framework
- Used by: PHYSIOCODE, Integrated Analysis, Output Generator

### Workflow Rules
- Governs: 8-step pipeline (Data Extraction → Safety Validation)
- Used by: All output files

### Safety Rules
- Governs: Forbidden terms, tone constraints
- Used by: Output Generator, All client-facing files

### Translation Rules
- Governs: Narrative pipeline (Technical Input → Editorial Narrative)
- Used by: Integrated Analysis, Output Generator

### Output Files
- Integrated Analysis → Therapeutic Plan → Exercise Plan
- All depend on: PHYSIOCODE, Translation Rules, Templates

---
## 📅 Change Log
 | Date | Change | Files Affected | Notes |
 |------|--------|----------------|-------|
 | *(To be populated with actual changes)* | | | |

---
## 📌 How to Use This File
1. For AI: Use `library_fetch` with the `document_id` to access files.
2. For Therapists: Use this as a reference for system navigation.
3. For Updates: Add changes to the Change Log above.
---
**IMPORTANT**: This file must be uploaded **LAST**, after all other files have their final `document_id`s.