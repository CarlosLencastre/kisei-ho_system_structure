# KISEI-HŌ — Workflow Rules
(Core File — Official Version)

This file defines the mandatory 8-step sequence for processing outputs in the KISEI-HŌ system. It ensures consistency and coherence across all stages of data transformation.

This file is governed by the Master Document and must remain aligned with:
- PHYSIOCODE Clinical Architecture
- Structural & Energetic Tables
- Energetic Framework

---
## 1. Mandatory Sequence

All outputs must follow this 8-step pipeline in strict order. No step may be skipped or reordered:

1. Data Extraction: Extract raw data from the Physiocode & Anamnesis file (see PHYSIOCODE - Data Extraction & Classification).
2. Structural Processing: Classify structural deviations (see Structural & Energetic Tables).
3. Energetic Processing: Classify energetic states (see Energetic Framework).
4. Axis Processing: Assess Centre, Root, and Firmament (see Energetic Framework).
5. Integrated Pattern Reading: Combine structural, energetic, and axis data (see PHYSIOCODE - Pattern Integration).
6. Narrative Translation: Transform technical data into descriptive meaning (see PHYSIOCODE - Therapeutic Orientation).
7. Therapeutic Orientation: Generate non-prescriptive movement suggestions (see PHYSIOCODE - Therapeutic Orientation).
8. Safety Validation: Validate outputs against Safety Rules and Master Document.

---
## 2. File Dependencies

Each step depends on the following files:
- Step 1: Physiocode & Anamnesis PDF, PHYSIOCODE - Data Extraction & Classification
- Step 2: Structural & Energetic Tables
- Step 3: Energetic Framework
- Step 4: Energetic Framework
- Step 5: PHYSIOCODE - Pattern Integration
- Step 6: PHYSIOCODE - Therapeutic Orientation, Translation Rules
- Step 7: PHYSIOCODE - Therapeutic Orientation, Unified Prescription Rules
- Step 8: Safety Rules, Master Document

---
## 3. Integration with Other Files

This workflow must remain aligned with:
- PHYSIOCODE Clinical Architecture (for pipeline logic).
- Master Document (for governance).
- Dependency Diagram (for structural coherence).