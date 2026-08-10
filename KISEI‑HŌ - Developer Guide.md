# KISEI‑HŌ - Developer Guide

## 1. Propósito do Documento
Este guia define as regras oficiais de manutenção, expansão, versionamento e integridade do sistema **KISEI‑HŌ**. É um documento técnico destinado a desenvolvedores, terapeutas avançados e sistemas de IA que operam ou evoluem a estrutura do método.

O objetivo é garantir que qualquer alteração futura:
- Mantém coerência com o **Master Document**;
- Respeita a arquitetura definida no **System Architecture Map**;
- Não quebra o pipeline **PHYSIOCODE**;
- Não altera outputs de módulos críticos;
- Preserva a segurança narrativa e técnica.

---

## 2. Princípios de Desenvolvimento

### 2.1. Integridade Estrutural
Nenhuma alteração pode contradizer:
- O **Master Document**;
- O **System Architecture Map**;
- O **Safety & Compliance**;
- O **Execution Guide**.

### 2.2. Modularidade
Cada ficheiro é um módulo independente. Alterações devem ser feitas de forma isolada, sem impacto lateral.

### 2.3. Determinismo
A ordem de execução nunca muda. Qualquer expansão deve respeitar o pipeline oficial.

### 2.4. Transparência
Todas as alterações devem ser documentadas neste guia e no **System Architecture Map**.

---

## 3. Regras de Versionamento

### 3.1. Estrutura de Versão
O sistema utiliza versionamento semântico (`MAJOR.MINOR.PATCH`):
- **MAJOR** — Alterações estruturais profundas;
- **MINOR** — Adição de módulos ou funcionalidades;
- **PATCH** — Correções pequenas, sem impacto estrutural.

### 3.2. Quando atualizar MAJOR
- Alteração na arquitetura geral;
- Criação de novos módulos críticos;
- Alteração no pipeline PHYSIOCODE.

### 3.3. Quando atualizar MINOR
- Adição de novos templates;
- Expansão de tabelas energéticas;
- Novas regras narrativas.

### 3.4. Quando atualizar PATCH
- Correções de linguagem;
- Ajustes de formatação;
- Clarificação de regras.

---

## 4. Regras de Expansão

### 4.1. Criação de Novos Módulos
Novos módulos só podem ser criados se:
1. Não duplicarem funções existentes;
2. Não substituírem módulos essenciais;
3. Forem aprovados pelo **System Architecture Map**;
4. Seguirem a estrutura narrativa e técnica do método.

### 4.2. Expansão de Módulos Existentes
Permitido apenas quando:
- Não altera outputs de outros módulos;
- Não altera dependências;
- Não altera o pipeline PHYSIOCODE.

### 4.3. Proibição de Alteração
Os seguintes módulos são **imutáveis**:
- Master Document;
- Output Generator;
- Workflow Rules;
- Safety & Compliance.

---

## 5. Regras de Manutenção

### 5.1. Auditoria Periódica
A cada ciclo de versão, verificar:
- Coerência entre módulos;
- Integridade das tabelas energéticas;
- Alinhamento com a narrativa oficial;
- Consistência do pipeline PHYSIOCODE.

### 5.2. Correção de Erros
Erros devem ser corrigidos sem alterar:
- Estrutura;
- Dependências;
- Outputs técnicos.

### 5.3. Atualização de Linguagem
Permitido apenas se:
- Seguir **Safety & Compliance**;
- Não alterar conteúdo técnico;
- Não alterar significado.

---

## 6. Regras de Contribuição

### 6.1. Estilo de Escrita
- Português europeu pré‑acordo ortográfico;
- Linguagem técnica, natural e fluida;
- Narrativa suave, não clínica;
- Ausência de prescrição.

### 6.2. Estrutura dos Ficheiros
Cada ficheiro deve conter:
- Título;
- Propósito;
- Regras;
- Exemplos (quando aplicável);
- Versão.

### 6.3. Proibição de Conteúdo
Não é permitido:
- Linguagem médica;
- Diagnósticos;
- Promessas terapêuticas;
- Interpretações psicológicas.

---

## 7. Regras de Compatibilidade

### 7.1. Compatibilidade com PHYSIOCODE
Qualquer expansão deve:
- Respeitar as três fases do PHYSIOCODE;
- Não alterar algoritmos internos;
- Não alterar tabelas estruturais.

### 7.2. Compatibilidade com Módulos Clínicos
Alterações não podem:
- Alterar outputs clínicos;
- Alterar estrutura dos planos;
- Alterar guias de sessão.

### 7.3. Compatibilidade com Output Generator
O **Output Generator** é final e imutável.

---

## 8. Procedimentos de Alteração

### 8.1. Passos Obrigatórios
1. Identificar necessidade.
2. Verificar impacto estrutural.
3. Atualizar System Architecture Map.
4. Atualizar Developer Guide.
5. Criar versão nova.
6. Documentar alterações.

### 8.2. Checklist de Alteração
- [ ] A alteração contradiz o Master Document? **→ NÃO**
- [ ] A alteração altera dependências? **→ NÃO**
- [ ] A alteração altera outputs? **→ NÃO**
- [ ] A alteração altera pipeline? **→ NÃO**
- [ ] A alteração segue Safety & Compliance? **→ SIM**

---

## 9. Exemplos de Alterações Permitidas
- Expansão de tabelas energéticas.
- Adição de novos templates.
- Clarificação de regras narrativas.
- Melhoria de explicações técnicas.

---

## 10. Exemplos de Alterações Proibidas
- Alterar o Master Document.
- Alterar o Output Generator.
- Alterar o pipeline PHYSIOCODE.
- Criar módulos duplicados.
- Introduzir linguagem clínica.

---

## 11. Versão e Histórico

- **Versão:** `1.0.0`
- **Estado:** Estável
- **Última atualização:** 10/08/2026

*Este documento faz parte da infraestrutura oficial do sistema KISEI‑HŌ.*