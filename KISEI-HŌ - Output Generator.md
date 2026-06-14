# KISEI-HŌ — Output Generator
(Output File — Official Version)

The Output Generator defines the automated logic used to produce all KISEI-HŌ client‑facing outputs.
It transforms PHYSIOCODE data into structured narrative using the Templates, Translation Rules and Narrative & Persona Guidelines.

This file is governed by the Master Document and must remain aligned with:
- PHYSIOCODE Clinical Architecture
- Structural & Energetic Tables
- Energetic Framework
- Narrative & Persona Guidelines
- Translation Rules
- Unified Prescription Rules
- Workflow Rules
- Safety Rules
- Templates
- Glossary

---
## 1. Purpose of the Output Generator

The Output Generator exists to:
- automate narrative creation
- ensure consistency
- ensure safety
- ensure alignment with all system rules
- ensure correct language (PT‑PT or EN) based on Physiocode

It is the final stage of the PHYSIOCODE pipeline.

---
## 2. Output Types

The Output Generator produces:
- Integrated Analysis [patient name].pdf
- Therapeutic Plan [patient name].pdf
- Exercise Plan [patient name].pdf
- Therapist Session Guide [patient name].pdf

---
## 3. Pipeline Compliance

The Output Generator follows the 8-step PHYSIOCODE pipeline:
1. Data Extraction
2. Structural Processing
3. Energetic Processing
4. Axis Processing
5. Integrated Pattern Reading
6. Narrative Translation
7. Therapeutic Orientation
8. Safety Validation

---
## 4. Pre-Output Safety Scan
Mandatory validation before generating client-facing outputs.

### 4.1 Forbidden Term Check
Scan all outputs for the following prohibited terms (see Safety Rules.md):
- Clinical terms: e.g., "posture," "misalignment," "scoliosis."
- Biomechanical terms: e.g., "joint," "spine curvature."
- Diagnostic terms: e.g., "dysfunction," "syndrome."
- Prescriptive terms: e.g., "you must," "correct this."
- Psychological terms: e.g., "stress," "anxiety," "trauma."
- Spiritual/Esoteric terms: e.g., "chakra," "energy healing."

Action: If any forbidden term is found, revise the output to use compliant language.

---
### 4.2 Tone Check
Verify compliance with Narrative & Persona Guidelines.md:
- Tone is calm, grounded, and sensory.
- Language is neutral and non-prescriptive.
- No urgency, intensity, or emotional coloring.

Action: If tone is non-compliant, revise the narrative to align with guidelines.

---
### 4.3 Dependency Check
Ensure all referenced files are up-to-date and aligned:
- Master Document (governance).
- Narrative & Persona Guidelines (tone/language).
- Energetic Framework (energetic logic).
- Structural & Energetic Tables (classifications).
- Templates (output structure).

Action: If dependencies are outdated, update the file references before generating outputs.

---
### 4.4 Workflow Compliance
Confirm the output follows the 8-step pipeline (see Workflow Rules.md):
1. Data Extraction
2. Structural Processing
3. Energetic Processing
4. Axis Processing
5. Integrated Pattern Reading
6. Narrative Translation
7. Therapeutic Orientation
8. Safety Validation

Action: If any step is missing, regenerate the output from the beginning.