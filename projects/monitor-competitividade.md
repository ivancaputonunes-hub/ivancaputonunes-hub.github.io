---
layout: page
title: Monitor de Competitividade e Price Gap
permalink: /projects/monitor-competitividade/
---

# Monitor de Competitividade e Price Gap

Projeto de **Inteligência de Mercado e Pricing Analytics** voltado ao monitoramento contínuo de preços da concorrência, identificação de gaps competitivos e apoio à tomada de decisão comercial.

---

## Contexto do Problema

Em ambientes competitivos, a falta de visibilidade estruturada sobre preços da concorrência gera:

- decisões reativas e pouco consistentes  
- dificuldade em priorizar ajustes de preço  
- risco de perda de volume ou erosão de margem  

Além disso, análises manuais não escalam e rapidamente ficam obsoletas.

---

## Objetivo do Projeto

Construir um **monitor analítico de competitividade** capaz de:

- comparar preços próprios vs. concorrência  
- identificar **price gaps**, dispersões e outliers  
- classificar risco competitivo por produto ou cluster  
- apoiar decisões de ajuste de preço com base em dados  

---

## Abordagem Analítica

O projeto é estruturado em quatro etapas principais:

### 1. Consolidação de Dados
- Preços próprios por SKU  
- Preços da concorrência (sell-out / pesquisa de mercado)  
- Identificação de concorrentes relevantes  
- Estrutura de produto (categoria, marca, cluster)  

### 2. Cálculo de Métricas-Chave
- Price gap absoluto e percentual  
- Índice de competitividade  
- Dispersão de preços entre concorrentes  
- Ranking de preço (mais caro / mais barato)  

### 3. Classificação de Risco
- Produtos acima do mercado  
- Produtos abaixo do mercado  
- Produtos alinhados  
- Identificação de casos críticos  

### 4. Visualização e Interpretação
- Dashboards comparativos  
- Alertas de risco competitivo  
- Apoio à priorização comercial  

---

## Principais Métricas

- Preço próprio  
- Preço médio da concorrência  
- Menor e maior preço do mercado  
- Gap percentual vs. mercado  
- Índice de competitividade por SKU ou cluster  

---

## Entregáveis

- Base analítica consolidada (SKU × concorrente)  
- Monitor de price gap e dispersão  
- Classificação automática de risco competitivo  
- Dashboards para acompanhamento contínuo  

---

## Stack Tecnológica

- **SQL** — estruturação e consolidação dos dados  
- **Python** — cálculos e regras analíticas  
- **Ferramentas de BI** — visualização e monitoramento  

---

## Próximos Passos

- Inclusão de histórico temporal para análise de tendência  
- Integração com elasticidade e volume  
- Gatilhos automáticos para revisão de preço  

---

⬅️ [Voltar para a lista de projetos](/projects/)
