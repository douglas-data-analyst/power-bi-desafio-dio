# 📊 Desafio Power BI DIO: Análise Financeira Global

Este repositório contém a solução para o desafio prático do curso de Power BI da Digital Innovation One (DIO), focado na replicação, expansão e refinamento de um relatório de análise financeira. O objetivo principal foi consolidar o aprendizado sobre modelagem de dados, criação de visuais e, principalmente, a organização e o profissionalismo do relatório final.

## 🎯 O Desafio Proposto

O desafio original consistia em três partes principais:

1.  **Replicação** das duas primeiras páginas do relatório (baseadas no material do curso).
2.  **Criação de uma terceira página** inédita, focada em análise geográfica e de segmento, contendo:
    *   Visual mapa 1: Soma de Sales e Unidades Vendidas por País.
    *   Visual mapa 2: Soma de Lucro (Profit) por País.
    *   Visual de pizza: Lucro por Segmento.
3.  **Documentação** do projeto no GitHub, conforme as melhores práticas do mercado.

## ✅ O que foi Feito (Minhas Contribuições)

Além de cumprir os requisitos de replicação das páginas existentes e a criação da terceira página, foram realizados refinamentos cruciais para a qualidade e profissionalismo do relatório:

### 1. Criação da Página Inédita

A página **"Análise de Segmento e Detalhes Geográficos"** foi criada com os visuais solicitados, incluindo um visual extra de Treemap para reforçar a análise de lucro por segmento.

| Visual | Medidas | Dimensões | Título do Visual (Português) |
| :--- | :--- | :--- | :--- |
| **Mapa (Bolhas)** | Soma de `Sales` e `Units Sold` (Tooltip) | `Country` | Vendas e Unidades Vendidas por País |
| **Mapa (Coroplético)** | Soma de `Profit` (Cor da Saturação) | `Country` | Lucro Total por País |
| **Gráfico de Pizza** | Soma de `Profit` | `Segment` | Distribuição de Lucro por Segmento de Mercado |

### 2. Refinamento e Organização do Relatório

O foco foi na melhoria da experiência do usuário (UX) e na padronização do idioma:

*   **Renomeação das Abas:** Todas as abas do relatório foram renomeadas para títulos claros e descritivos, facilitando a navegação e o entendimento do conteúdo:
    *   `Página 1` → **Visão Geral de Vendas**
    *   `Página 2` → **Análise Geográfica (Países e Lucro)**
    *   `Página 3` → **Análise de Segmento e Detalhes Geográficos** (A página criada no desafio)
    *   `Página 4` → **Análise de Produto**
    *   `Página 5` → **Detalhes de Produto e Lucro**
*   **Padronização de Títulos:** Todos os títulos dos visuais foram traduzidos e padronizados para o português, garantindo a consistência do relatório. Exemplos de tradução:
    *   `Soma de Profit por Segment` → **Soma de Lucro por Segmento**
    *   `Soma de Sales e Soma de Units Sold por Country` → **Vendas e Unidades Vendidas por País**
    *   `Soma de Profit por Country` → **Lucro Total por País**

## 📁 Estrutura do Repositório

*   `FinancialSample(1).xlsx`: A base de dados utilizada para a construção do relatório.
*   `Análise_Financeira_Global.pbix`: O arquivo final do Power BI Desktop contendo as páginas do relatório.

## 🔗 Referências

*   **Curso/Desafio Original:** [Link para o repositório da expert](https://github.com/julianazanelatto/power_bi_analyst )
*   **Plataforma:** Digital Innovation One (DIO)

---
*Este projeto demonstra habilidades avançadas em Power BI, Análise de Dados, Refinamento de Relatórios e Versionamento de Código (Git/GitHub).*
