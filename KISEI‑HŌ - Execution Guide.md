# KISEI‑HŌ - Execution Guide

## 1. Propósito do Documento
Este guia define a ordem determinística de execução do sistema **KISEI‑HŌ**.
Serve como manual técnico para IA (Copilot, GPT, Claude) e terapeutas, garantindo:
- Consistência total entre módulos;
- Ausência de conflitos de execução;
- Execução sequencial correta do pipeline;
- Regras claras de fallback;
- Definição estrita de prioridades e integridade.

*Este documento substitui na totalidade o antigo `Dependency Diagram.md`.*

---

## 2. Princípios de Execução

### 2.1. Determinismo
A ordem dos módulos é estrita e imutável. Nenhum módulo pode ser executado fora da sequência definida.

### 2.2. Integridade
Nenhum módulo pode alterar os outputs de outro módulo nem contradizer o **Master Document**.

### 2.3. Segurança
A narrativa e a linguagem seguem obrigatoriamente e em todas as fases as diretivas do módulo **Safety & Compliance**.

---

## 3. Ordem Oficial de Execução (Pipeline Completo)


[Etapa 1: Entrada de Dados]
│
▼
[Etapa 2: Núcleo Técnico — PHYSIOCODE (01 ➔ 02 ➔ 03)]
│
▼
[Etapa 3: Núcleo Clínico (Analysis ➔ Plan ➔ Exercises ➔ Session Guide)]
│
▼
[Etapa 4: Núcleo Operacional (Workflow ➔ Translation ➔ Prescription ➔ Output Gen)]
│
▼
[Etapa 5: Infraestrutura & Validação Final]

---

### Etapa 1 — Entrada
Recolha de dados brutos:
- Dados anatómicos e biomecânicos
- Dados energéticos
- Registos clínicos/histórico
- Relatos subjetivos
- Observação postural e de movimento

### Etapa 2 — Núcleo Técnico (PHYSIOCODE)
O PHYSIOCODE é sempre executado antes de qualquer módulo clínico.
1. **PHYSIOCODE – Data Extraction:** Extrai assimetrias, tensões, padrões e fluxos. Utiliza as *Structural & Energetic Tables*.
2. **PHYSIOCODE – Pattern Integration:** Integra dados anatómicos e energéticos. Utiliza o *Energetic Framework*.
3. **PHYSIOCODE – Therapeutic Orientation:** Gera direções terapêuticas para alimentar a *Integrated Analysis* e o *Therapeutic Plan*.

### Etapa 3 — Núcleo Clínico
1. **Integrated Analysis:** Integra biomecânica, energia e narrativa utilizando os outputs do PHYSIOCODE.
2. **Therapeutic Plan:** Define as prioridades de intervenção com base na *Integrated Analysis*.
3. **Exercise Plan:** Constrói propostas de exercício alinhadas com o *Therapeutic Plan*.
4. **Therapist Session Guide:** Consolida a sessão prática, combinando o *Therapeutic Plan* e o *Exercise Plan*.
5. **Integrated Exercise Library:** Fornece a base de dados de exercícios validados.
6. **Templates:** Define a estrutura visual de formatação.

### Etapa 4 — Núcleo Operacional
1. **Workflow Rules:** Controla a ordem de execução. Tem prioridade sobre as *Translation Rules*.
2. **Translation Rules:** Converte a linguagem técnica em narrativa fluida. Nunca altera conteúdo técnico.
3. **Unified Prescription Rules:** Valida a consistência cruzada entre outputs.
4. **Output Generator:** Compila e produz os quatro documentos finais. É imutável.

### Etapa 5 — Infraestrutura
- **System Architecture Map:** Define a arquitetura global e dependências.
- **Safety & Compliance:** Garante a segurança narrativa e não-prescrição.
- **Developer Guide:** Define as regras de manutenção, versionamento e expansão.

---

## 4. Regras de Prioridade e Hierarquia

1. Master Document (Autoridade Máxima)
└── 2. Safety & Compliance (Segurança Narrativa)
└── 3. Pipeline PHYSIOCODE (Dados Técnicos)
└── 4. Workflow Rules (Sequenciamento)
└── 5. Translation Rules (Adaptação de Linguagem)
└── 6. Módulos Clínicos & Output Generator

1. O **Master Document** tem prioridade absoluta sobre todo o sistema.
2. **Safety & Compliance** sobrepõe-se a qualquer estipulação de linguagem narrativa.
3. O **PHYSIOCODE** tem prioridade técnica sobre todos os módulos clínicos.
4. **Workflow Rules** tem prioridade de execução sobre as **Translation Rules**.
5. O **Output Generator** é final e imutável.

---

## 5. Regras de Fallback (Ausência de Dados)

Quando o input do paciente apresenta dados omissos, o sistema aplica as seguintes regras de omissão controlada:

| Dado Omisso / Em Falta | Protocolo de Fallback a Aplicar |
| :--- | :--- |
| **Dados Anatómicos** | Utilizar padrões de alinhamento e vetores médios padrão. |
| **Dados Energéticos** | Derivar inferências a partir da leitura biomecânica e postural. |
| **Dados Clínicos** | Processar via PHYSIOCODE focado em dados observacionais e narrativa. |
| **Dados Subjetivos** | Não inventar nem assumir; manter tom estritamente neutro e descritivo. |
| **Dados de Movimento** | Restringir a análise à avaliação postural estática. |

---

## 6. Regras de Resolução de Conflitos

Caso dois ou mais módulos gerem informação divergente:
1. **Master Document** prevalece sempre.
2. **PHYSIOCODE** prevalece sobre divergências nos módulos clínicos.
3. **Workflow Rules** prevalece sobre as *Translation Rules*.
4. **Safety & Compliance** prevalece sobre preferências de estilo narrativo.
5. O **Output Generator** nunca é modificado para acomodar excepções.

---

## 7. Mapeamento de Fluxo de Entrada e Saída

### Entradas (Inputs)
- Dados anatómicos
- Dados energéticos
- Dados clínicos
- Dados subjetivos
- Observações de postura e movimento

### Saídas Finais (Outputs)
- Relatório biomecânico
- Mapa bioenergético
- Plano terapêutico
- Plano de exercícios
- Guia prático de sessão
- Narrativa integrada do paciente

---

## 8. Versão e Histórico

- **Versão:** `1.0.0`
- **Estado:** Estável
- **Última Atualização:** 10/08/2026
- **Responsável:** Infraestrutura e Operações KISEI‑HŌ