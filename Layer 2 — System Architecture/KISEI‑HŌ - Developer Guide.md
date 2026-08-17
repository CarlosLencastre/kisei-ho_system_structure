# KISEI-HŌ — Developer Guide
*Technical Maintenance and Expansion Document*
**Version:** 1.1**Date:** August 2026
**Governed by:** KISEI-HŌ - Master Document.md
---
## 1. Document Purpose
This guide defines the official rules for maintenance, expansion, versioning, and integrity of the **KISEI-HŌ system**.It is a technical document intended for developers, advanced therapists, and AI systems that operate or evolve the method structure.
**Goals:**- Maintain coherence with the **Master Document v1.1**- Respect the architecture defined in the **System Architecture Map v1.1**- Not break the **PHYSIOCODE** pipeline- Not alter outputs from critical modules- Preserve narrative and technical safety
**This file is governed by the Master Document v1.1 and must remain aligned with:**- System Architecture Map v1.1- Dependency Diagram v1.1- Execution Guide v1.1- Safety & Compliance v1.1
---
## 2. Language Rules v1.1
**All system files are in ENGLISH:**- File names: English- File content: English- Code: English- Therapist outputs: PT-PT- Client outputs: PT-PT or EN (based on anamnesis)- Anamnesis: Clinical, biomechanical, diagnostic, emotional terms **PERMITTED**
**Translation Rules:** Clinical terms in anamnesis must be transformed via the Translation Rules pipeline before appearing in any output.
---
## 3. Development Principles
### 3.1 Structural Integrity
No change may contradict:- **Master Document v1.1**- **System Architecture Map v1.1**- **Safety & Compliance v1.1**- **Execution Guide v1.1**- **Dependency Diagram v1.1**
### 3.2 Modularity
Each file is an independent module.Changes must be made in isolation, without lateral impact.
### 3.3 Determinism
The execution order never changes.Any expansion must respect the official 8-step pipeline (Workflow Rules).
### 3.4 Transparency
All changes must be documented in:- This guide- System Architecture Map- Dependency Diagram- Version History section of each file
---
## 4. Versioning Rules
### 4.1 Version Structure
The system uses semantic versioning (`MAJOR.MINOR.PATCH`):- **MAJOR** — Deep structural changes- **MINOR** — Module or functionality additions- **PATCH** — Small corrections, no structural impact
### 4.2 When to Update MAJOR
- Architecture change- New critical modules- PHYSIOCODE pipeline change
### 4.3 When to Update MINOR
- New templates- Energy table expansions- New narrative rules- New terminology (BTL, Flow States, Kyo/Jitsu, Sōtai)
### 4.4 When to Update PATCH
- Language corrections- Formatting adjustments- Rule clarifications
### 4.5 Version Reference
| Version | Date | Content ||---------|------|---------|| 1.0 | June 2026 | Initial release — 21 files, 6 layers || 1.1 | August 2026 | 29 files, 10 layers, Advanced Oriental Chiropractic, BTL, Flow States, Kyo/Jitsu, Sōtai, language rules v1.1 |
---
## 5. Expansion Rules
### 5.1 Creating New Modules
New modules may only be created if:1. They do not duplicate existing functions2. They do not replace essential modules3. They are approved by the **System Architecture Map v1.1**4. They follow the narrative and technical structure of the method5. They integrate with existing terminology (Glossary v1.1)
### 5.2 Expanding Existing Modules
Allowed only when:- It does not alter outputs from other modules- It does not alter dependencies- It does not alter the PHYSIOCODE pipeline- It maintains terminology consistency (Glossary v1.1)
### 5.3 Prohibition of Change
The following modules are **IMMUTABLE**:- Master Document- Output Generator- Workflow Rules- Safety & Compliance
### 5.4 Advanced Oriental Chiropractic Integration
When expanding, consider integration with:- **Body Tension Lines (BTL):** Physical tension pathways- **Energetic Flow States:** Energy quality and movement through meridians- **Kyo/Jitsu Patterns:** Deficiency/excess balance- **Sōtai Principles:** Natural movement and gentle correction- **Energetic Principles:** Governing rules of energy movement
---
## 6. Maintenance Rules
### 6.1 Periodic Audit
At each version cycle, verify:- Coherence between modules- Integrity of energy tables (Flow States, Kyo/Jitsu patterns)- Alignment with official narrative- Consistency of PHYSIOCODE pipeline- Terminology alignment with Glossary v1.1
### 6.2 Error Correction
Errors must be corrected without altering:- Structure- Dependencies- Technical outputs- BTL or Flow State descriptions
### 6.3 Language Updates
Allowed only if:- Following **Safety & Compliance v1.1**- Not altering technical content- Not altering meaning- Maintaining Glossary v1.1 consistency
---
## 7. Contribution Rules
### 7.1 Writing Style
- **English** for all file content- Technical, natural, and fluid language- Smooth, non-clinical narrative- Absence of prescription- Integration of Oriental structural terminology where appropriate
### 7.2 File Structure
Each file must contain:- Title- Purpose- Rules- Examples (when applicable)- Version history
### 7.3 Content Prohibition
Not allowed:- Medical language- Diagnoses- Therapeutic promises- Psychological interpretations- Clinical terms in outputs (permitted in anamnesis, transformed via Translation Rules)
---
## 8. Compatibility Rules
### 8.1 PHYSIOCODE Compatibility
Any expansion must:- Respect the three phases of PHYSIOCODE- Not alter internal algorithms- Not alter structural tables- Not alter BTL or Flow State classifications
### 8.2 Clinical Modules Compatibility
Changes cannot:- Alter clinical outputs- Alter plan structures- Alter session guides- Alter Kyo/Jitsu balance descriptions
### 8.3 Output Generator Compatibility
The **Output Generator** is final and immutable.
---
## 9. Alteration Procedures
### 9.1 Mandatory Steps
1. Identify need2. Check structural impact3. Verify terminology alignment (Glossary v1.1)4. Update System Architecture Map5. Update Dependency Diagram6. Update Developer Guide7. Create new version8. Document changes
### 9.2 Alteration Checklist
- [ ] Does the change contradict the Master Document? → **NO**- [ ] Does the change alter dependencies? → **NO**- [ ] Does the change alter outputs? → **NO**- [ ] Does the change alter the pipeline? → **NO**- [ ] Does the change follow Safety & Compliance? → **YES**- [ ] Does the change maintain Glossary consistency? → **YES**- [ ] Does the change maintain BTL/Flow State/Kyo-Jitsu integration? → **YES**
---
## 10. Allowed Alterations Examples
- Energy table expansions (Flow States, Kyo/Jitsu patterns)- New templates (with BTL/Flow State support)- Narrative rules clarifications (with Glossary alignment)- Technical explanation improvements- New Oriental structural terminology integration
---
## 11. Prohibited Alterations Examples
- Altering the Master Document- Altering the Output Generator- Altering the PHYSIOCODE pipeline- Creating duplicate modules- Introducing clinical language in outputs- Removing BTL or Flow State integration
---
## 12. Terminology Integration (v1.1)
When developing, integrate these terms from **Glossary v1.1**:
| Term | Description | Integration Point ||------|-------------|-------------------|| Body Tension Lines (BTL) | Physical tension pathways | Data Extraction, Structural Tables || Energetic Flow States | Energy quality/movement | Energetic Framework, Pattern Integration || Kyo (虚) | Deficiency pattern | Pattern Integration, Therapeutic Orientation || Jitsu (実) | Excess pattern | Pattern Integration, Therapeutic Orientation || Sōtai | Structural balancing technique | Postural Rehabilitation, Therapeutic Orientation || Energetic Principles | Energy movement rules | Energetic Framework, Prescription Rules |
---
## 13. Version and History
- **Version:** `1.1`- **Status:** Active- **Last Update:** August 2026- **Files:** 29 (10 layers)
---
## 14. Related Documentation
- **System Architecture Map:** Functional hierarchy and integration- **Dependency Diagram:** Complete file dependency mapping- **Execution Guide:** Execution sequence and priority rules- **Glossary v1.1:** Terminology reference (BTL, Flow States, Kyo/Jitsu)- **Safety & Compliance v1.1:** Safety rules and ethics
---
*This document is part of the official infrastructure of the KISEI-HŌ system.*
**End of Developer Guide v1.1**
