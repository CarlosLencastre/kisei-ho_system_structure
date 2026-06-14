# KISEI-HŌ — Dependency Diagram
*Support File — Official Version*

This document maps the dependency relationships between all KISEI-HŌ system files. It ensures structural coherence and clarifies how each file interacts with the others.

**Note**: This file will be merged into System Overview.md in Phase 8. See below for current structure.

This file does not contain clinical content and does not participate in client-facing outputs.

---
## 1. Master Dependency

The Master Document governs all files:
- Core Architecture Files
- Therapist & Session Files
- Master System Files
- Language & Narrative Files
- Support Files

No file may contradict the Master Document.

---
## 2. Exclusive Data Source Files

1. Physiocode & Anamnesis [patient name].pdf — First data input. Without this file, the rest of the workflow cannot be executed.
2. Integrated Analysis [patient name].pdf — First output. It requires file 1.
3. Therapeutic Plan [patient name].pdf — Second output. It requires files 1 and 2.
4. Exercise Plan [patient name].pdf — Third output. It requires files 2 and 3.

---
## 3. Core Architecture Files

- PHYSIOCODE - Data Extraction & Classification
- PHYSIOCODE - Pattern Integration
- PHYSIOCODE - Therapeutic Orientation
- Structural & Energetic Tables
- Energetic Framework
- Workflow Rules
- Safety Rules

---
## 4. Language & Narrative Files

- Narrative & Persona Guidelines
- Translation Rules
- Glossary

---
## 5. Therapist & Session Files

- Therapist Session Guide
- Templates
- Unified Prescription Rules

---
## 6. Output Files

- Integrated Analysis
- Therapeutic Plan
- Exercise Plan
- Output Generator
