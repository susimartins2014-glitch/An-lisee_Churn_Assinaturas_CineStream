# 🎬 CineStream — Análise de Churn e Retenção de Assinantes



> ⚠️ **Nota:** Este projeto utiliza **dados fictícios** da plataforma **CineStream**, criados para fins de estudo e composição de portfólio em Análise de Dados e Growth Marketing.

---

## 📌 Sobre o Projeto & Metodologia

O objetivo deste projeto é analisar os padrões de **Churn (cancelamento de assinaturas)** na plataforma CineStream para identificar gargalos de retenção e embasar estratégias de Growth.

A construção do projeto seguiu um fluxo de trabalho em etapas:

1. **Extração e Tratamento em SQL:** 
   * Consultas para limpeza e agregação da base bruta de assinantes.
   * Agrupamento de métricas de permanência (dias ativos) por tipo de plano.
   * Criação de **quartis de churn** (com funções de janela/agregação) para segmentar a base entre usuários de saída precoce (Q1) e usuários de longa data.
2. **Modelagem no Power BI:** 
   * Importação das visões tratadas no SQL.
   * Criação de medidas em DAX para cálculo de médias, taxas e distribuição de cancelamentos.
3. **UI/UX e Design de Relatório:**
   * Construção de layout personalizado no Canva  em tons de roxo/lilás para compor uma interface limpa e intuitiva.

---

## 📊 Principais Indicadores e Visuais

* **Métricas Principais (Cards):** Total de churns, permanência média geral, média de churn precoce no Q1 e o principal motivo de cancelamento.
* **Permanência Média por Plano:** Gráfico comparativo de retenção entre os planos Premium, Padrão e Mobile.
* **Quartis de Churn x Plano:** Matriz com mapa de calor (gradiente condicional) exibindo a evolução da permanência por quartil e tipo de assinatura.
* **Motivos de Cancelamento:** Gráfico de rosca detalhando os principais fatores de saída (preço, catálogo, interface e suporte).
* **Painel de Observações:** Resumo executivo trazendo os *insights* mais relevantes para tomada de decisão.

---

## 🛠️ Tecnologias Utilizadas

* **SQL:** Extração, limpeza, agregação de dados e segmentação em quartis.
* **Power BI:** Modelagem de dados, criação de medidas DAX e visualização interativa.

---

## ✒️ Autoria
Desenvolvido por mim para fins de estudo e composição de portfólio, integrando Análise de Dados e estratégias de Growth para retenção de clientes.
