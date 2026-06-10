<div align="center">

<img src="https://avatars.githubusercontent.com/u/282925572?s=200&v=4" alt="Aquvaris AI" width="80" style="border-radius: 12px"/>

# Aquvaris AI — Inspection Engine

**Motor de inspeções digitais e scoring operacional ambiental**

[![TypeScript](https://img.shields.io/badge/TypeScript-Next.js-3178C6?style=flat&logo=typescript&logoColor=white)](#)
[![Supabase](https://img.shields.io/badge/Backend-Supabase-3ECF8E?style=flat&logo=supabase&logoColor=white)](#)
[![Status](https://img.shields.io/badge/Status-Em%20desenvolvimento-yellow?style=flat)](#)

[← Voltar para a plataforma](https://github.com/aquvarisAI/aquvaris-platform) · [AI Models](https://github.com/aquvarisAI/aquvaris-ai-models) · [Design System](https://github.com/aquvarisAI/aquvaris-design-system)

</div>

---

## Sobre este repositório

Este repositório contém o **motor de inspeções digitais** da plataforma Aquvaris — responsável pela coleta estruturada de dados em campo, avaliação de conformidade regulatória e geração automática de relatórios de inspeção ambiental.

---

## Responsabilidades

| Módulo | Descrição |
|--------|-----------|
| **Formulários inteligentes** | Templates dinâmicos de inspeção por tipo de ativo e setor |
| **Scoring operacional** | Pontuação automática de conformidade com base nas respostas |
| **Detecção de não-conformidades** | Identificação de itens fora dos limites regulatórios |
| **Geração de relatórios** | Relatórios automáticos em PDF com diagnóstico e recomendações |
| **Histórico de inspeções** | Rastreamento temporal de inspeções por ativo e localização |

---

## Fluxo de inspeção

```
Técnico em campo (mobile/web)
           ↓
   Seleciona tipo de inspeção
   (água · resíduos · emissões · energia · conformidade)
           ↓
   Preenche formulário inteligente
   (campos dinâmicos por categoria)
           ↓
   Motor de scoring
   → calcula pontuação de conformidade
   → identifica não-conformidades
   → define nível de risco (baixo · médio · alto · crítico)
           ↓
   Geração automática de relatório
   → PDF com diagnóstico completo
   → recomendações de ação
   → prazo estimado de resolução
           ↓
   Dados enviados para aquvaris-ai-models
   → alimenta modelos preditivos e de anomalia
```

---

## Tipos de inspeção suportados

| Categoria | Indicadores avaliados |
|-----------|----------------------|
| 💧 Qualidade da água | pH, turbidez, OD, DBO, metais pesados |
| 🗑️ Resíduos sólidos | Classificação, armazenamento, destinação |
| 💨 Emissões atmosféricas | Material particulado, gases, ruído |
| ⚡ Energia | Consumo, eficiência, fontes renováveis |
| 📋 Conformidade legal | Licenças, laudos, prazos regulatórios |

---

## Stack técnica

| Camada | Tecnologia |
|--------|-----------|
| Frontend | React + Next.js + TypeScript |
| Backend | Supabase (banco + auth + storage) |
| Banco de dados | PostgreSQL + PostGIS |
| Relatórios | Geração automática via IA (OpenAI API) |
| Armazenamento | Supabase Storage (PDFs e imagens) |

---

## Roadmap

- [x] Estrutura do repositório
- [ ] Schema de dados para inspeções (PostgreSQL)
- [ ] Formulários dinâmicos por categoria
- [ ] Motor de scoring e avaliação de conformidade
- [ ] Geração automática de relatório PDF
- [ ] Histórico e rastreamento por ativo
- [ ] Integração com aquvaris-ai-models

---

## Relação com os outros repositórios

```
aquvaris-platform          ← exibe os resultados das inspeções
aquvaris-ai-models         ← consome os dados de inspeção para análise
aquvaris-inspection-engine ← este repositório (motor de inspeções)
aquvaris-design-system     ← fornece componentes visuais dos formulários
```

---

## Fundadora

**Bruna Preschadt de Oliveira** — Data Engineer & AI Developer

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Bruna%20Preschadt-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/bruna-preschadt-de-oliveira-1550ab1ab/)
[![GitHub](https://img.shields.io/badge/GitHub-bpreschac--gif-181717?style=flat&logo=github)](https://github.com/bpreschac-gif)
[![Kaggle](https://img.shields.io/badge/Kaggle-brunapreschadt-20BEFF?style=flat&logo=kaggle)](https://www.kaggle.com/brunapreschadt)

---

<div align="center">
<sub>Aquvaris AI © 2025 · Inteligência ambiental e operacional · Brasil</sub>
</div>
