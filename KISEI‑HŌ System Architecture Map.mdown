# KISEI‑HŌ - System Architecture Map

## 1. Propósito do Documento
Este documento define a arquitectura oficial do sistema **KISEI‑HŌ**, descrevendo a hierarquia funcional, dependências internas, fluxo operacional e integração do pipeline **PHYSIOCODE**. Serve como referência técnica para execução, manutenção e expansão do método.

---

## 2. Estrutura Global do Sistema
O sistema é composto por **21 módulos** organizados em cinco camadas funcionais:

### Camada 1 — Núcleo Conceptual
- Master Document
- Narrative & Persona Guidelines
- Glossary
- Energetic Framework

### Camada 2 — Núcleo Técnico
- Structural & Energetic Tables
- PHYSIOCODE – Data Extraction
- PHYSIOCODE – Pattern Integration
- PHYSIOCODE – Therapeutic Orientation

### Camada 3 — Núcleo Operacional
- Workflow Rules
- Translation Rules
- Unified Prescription Rules
- Output Generator

### Camada 4 — Núcleo Clínico
- Integrated Analysis
- Therapeutic Plan
- Exercise Plan
- Therapist Session Guide
- Integrated Exercise Library
- Templates

### Camada 5 — Infraestrutura
- System Architecture Map *(este documento)*
- Execution Guide
- Safety & Compliance
- Developer Guide

---

## 3. Hierarquia Funcional
A arquitectura segue uma hierarquia de dependências que garante consistência e determinismo:

1. **Master Document** — base conceptual e linguística.
2. **PHYSIOCODE** — processamento técnico de dados biomecânicos e energéticos.
3. **Structural & Energetic Tables** — dados estruturais e energéticos.
4. **Energetic Framework** — contexto energético.
5. **Workflow Rules** — ordem de execução.
6. **Translation Rules** — conversão técnica ➔ narrativa.
7. **Unified Prescription Rules** — validação de consistência.
8. **Output Generator** — produção dos documentos finais.
9. **Módulos clínicos** — aplicação prática.
10. **Infraestrutura** — segurança, execução e manutenção.

---

## 4. Pipeline PHYSIOCODE Integrado
O pipeline PHYSIOCODE opera em três fases sequenciais:

1. **Data Extraction:** Extrai assimetrias, padrões, tensões e fluxos. Utiliza *Structural & Energetic Tables*.
2. **Pattern Integration:** Integra dados anatómicos e energéticos. Utiliza *Energetic Framework*.
3. **Therapeutic Orientation:** Gera direcções terapêuticas que alimentam a *Integrated Analysis* e o *Therapeutic Plan*.

---

## 5. Fluxo de Dependências

Entrada ➔ Núcleo Técnico ➔ Núcleo Clínico ➔ Saída

- **Entrada:** Dados do Paciente
- **Processamento:** PHYSIOCODE (3 módulos)
- **Análise e Planeamento:** Integrated Analysis ➔ Therapeutic Plan ➔ Exercise Plan ➔ Therapist Session Guide
- **Geração:** Output Generator
- **Saída:** Documentos finais

---

## 6. Mapa de Fluxo

- **Master Document** ➔ define tudo
- **Glossary** ➔ garante linguagem
- **Narrative Guidelines** ➔ garante estilo
- **PHYSIOCODE** ➔ processa dados
- **Workflow Rules** ➔ ordena passos
- **Translation Rules** ➔ converte linguagem
- **Unified Prescription Rules** ➔ valida consistência
- **Output Generator** ➔ produz outputs
- **Módulos clínicos** ➔ aplicam o método
- **Infraestrutura** ➔ garante segurança e execução

---

## 7. Regras de Prioridade

1. **Master Document** tem prioridade absoluta.
2. **PHYSIOCODE** tem prioridade sobre módulos clínicos.
3. **Workflow Rules** tem prioridade sobre Translation Rules.
4. **Safety & Compliance** tem prioridade sobre narrativa.
5. **Output Generator** é imutável.

---

## 8. Mapa de Interação entre Módulos

PHYSIOCODE ➔ Integrated Analysis
Integrated Analysis ➔ Therapeutic Plan
Therapeutic Plan ➔ Exercise Plan
Exercise Plan ➔ Therapist Session Guide
Therapist Session Guide ➔ Output Generator
Output Generator ➔ Documentos Finais

---

## 9. Mapa de Entrada e Saída

### Entrada
- Dados anatómicos
- Dados energéticos
- Dados clínicos
- Dados subjetivos
- Dados de postura
- Dados de movimento

### Saída
- Relatório biomecânico
- Mapa energético
- Plano terapêutico
- Plano de exercícios
- Guia de sessão
- Narrativa integrada

---

## 10. Regras de Integridade

- Nenhum módulo pode contradizer o **Master Document**.
- Nenhum módulo pode alterar outputs de outro módulo.
- **PHYSIOCODE** é sempre executado antes de qualquer módulo clínico.
- **Translation Rules** nunca altera conteúdo técnico.
- **Safety & Compliance** tem prioridade sobre narrativa.
- **Output Generator** é imutável.

---

## 11. Versão e Actualização

Este documento define a arquitectura oficial. Qualquer alteração estrutural deve ser registada aqui.
O **Developer Guide** explica procedimentos de versão e expansão.