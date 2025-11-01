# 📊 Desafio Power BI DIO: Análise Financeira Global

Este repositório contém a solução para o desafio prático do curso de Power BI da Digital Innovation One (DIO), focado na replicação e expansão de um relatório de análise financeira. O objetivo principal foi consolidar o aprendizado sobre modelagem de dados, criação de visuais e formatação de relatórios no Power BI Desktop.

## 🎯 Objetivo do Projeto

O desafio consistiu em três partes principais:

1.  **Replicação** das duas primeiras páginas do relatório (baseadas no material do curso).
2.  **Criação de uma terceira página** inédita, focada em análise geográfica e de segmento.
3.  **Documentação** do projeto no GitHub, conforme as melhores práticas do mercado.

## 📈 Terceira Página: Análise Geográfica e de Segmento

A página criada por mim, **"Análise Geográfica e de Segmento"**, utiliza o *dataset* financeiro para explorar a distribuição de vendas, unidades e lucro em diferentes países e segmentos de mercado.

### Visuais Implementados:

| Visual | Medidas | Dimensões | Propósito |
| :--- | :--- | :--- | :--- |
| **Mapa 1 (Bolhas)** | Soma de `Sales` e `Units Sold` (Tooltip) | `Country` | Visualizar o volume de vendas e unidades por localização. |
| **Mapa 2 (Coroplético)** | Soma de `Profit` (Cor da Saturação) | `Country` | Identificar rapidamente os países com maior e menor lucratividade. |
| **Gráfico de Pizza** | Soma de `Profit` | `Segment` | Analisar a distribuição percentual do lucro total entre os diferentes segmentos de mercado. |

## 📁 Estrutura do Repositório

*   `FinancialSample(1).xlsx`: A base de dados utilizada para a construção do relatório.
*   `Análise_Financeira_Global.pbix`: O arquivo final do Power BI Desktop contendo as três páginas do relatório.

## 🔗 Referências

*   **Curso/Desafio Original:** [Link para o repositório da expert](https://github.com/julianazanelatto/power_bi_analyst )
*   **Plataforma:** Digital Innovation One (DIO)

---
*Este projeto demonstra habilidades em Power BI, Análise de Dados e Versionamento de Código (Git/GitHub).*
