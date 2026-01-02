---
layout: page
title: Motor de Precificação Dinâmica
permalink: /projects/motor-precificacao/
---


# Motor de Precificação Dinâmica para Varejo

## Visão Técnica
Projeto de **pricing analytics** voltado à recomendação de preços e simulação de cenários com foco em maximização de margem e competitividade.

---

## Problema de Negócio
Decisões de preço frequentemente são:
- manuais
- reativas à concorrência
- tomadas sem simulação de impacto financeiro

Isso gera perda de margem ou perda de competitividade.

---

## Objetivo
Construir um modelo capaz de:
- recomendar preços por SKU (ou SKU × cluster)
- simular cenários de preço × volume × margem
- apoiar decisões comerciais baseadas em dados

---

## Variáveis Consideradas
- custo unitário / CMV
- preço atual
- margem alvo
- preços da concorrência
- volume histórico
- elasticidade-preço (estimada ou assumida)
- restrições comerciais

---

## Metodologia
1. Estruturação da base analítica (SQL)
2. Definição de regras de negócio (guardrails)
3. Modelagem de cenários de preço
4. Avaliação de impacto financeiro
5. Visualização e interpretação

---

## Entregáveis
- dataset analítico
- motor de recomendação de preço
- simulador de cenários (what-if)
- dashboard de apoio à decisão

---

## Stack
- SQL
- Python (pandas, numpy)
- Excel / Google Sheets
- Power BI ou Looker Studio

---

## Autor
Ivan Caputo — Pricing & Data Analytics
