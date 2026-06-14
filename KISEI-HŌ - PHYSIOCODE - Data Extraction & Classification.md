# KISEI-HŌ — PHYSIOCODE - Data Extraction & Classification
(Core File — Official Version)

This file defines the initial stages of the PHYSIOCODE pipeline, focusing on raw data intake and classification.
It is governed by the Master Document and must remain aligned with:
- Structural & Energetic Tables
- Energetic Framework
- PHYSIOCODE Clinical Architecture

---
## 1. Source of Data

All clinical processing begins with the Physiocode & Anamnesis [client name].pdf.
This file determines:
- the language of all client-facing outputs (PT-PT or EN)
- the structural data (angles, deviations, regions)
- the energetic data (states, symbols, relationships)
- the axis data (Centre, Root, Firmament, Ki Flow)
- the session context (history, symptoms, notes)

All .md system files remain in English.

---
## 2. Data Extraction (Step 1)

Extract all raw data from the Physiocode & Anamnesis file:
- Structural deviations
- Energetic states
- Axis behaviour
- Session notes
- Language setting for output

Rule: No interpretation occurs at this stage.

---
## 3. Structural Processing (Step 2)

Using the Structural & Energetic Tables:
- Convert angles → direction (+/-)
- Convert angles → amplitude (mild / moderate / marked)
- Classify structural meaning
- Identify protective patterns
- Identify compensatory patterns

Dependencies:
- Structural & Energetic Tables

---
## 4. Energetic Processing (Step 3)

Using the Energetic Framework:
- Classify energetic states (e.g., Normal Flow, Blockage, Excess/Deficiency)
- Assign symbols (→, ⨂, ◎, ⊖)
- Identify regional energetic patterns

Dependencies:
- Energetic Framework

---
## 5. Axis Processing (Step 4)

Using the Energetic Framework:
- Assess Centre (spine, core)
- Assess Root (lower body connection to ground)
- Assess Firmament (upper body connection to space)
- Identify axis interactions

Dependencies:
- Energetic Framework