# 🏆 Análise de Dados Preditiva: Simulação da Copa do Mundo 2026

![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)
![Data Analysis](https://img.shields.io/badge/Main_Field-Data__Analysis-green.svg)
![Google Colab](https://img.shields.io/badge/Environment-Google__Colab-orange.svg)

Este repositório contém um projeto de **Análise de Dados e Simulação Estatística** focado nas fases finais da Copa do Mundo de 2026. Utilizando Python e bibliotecas de Data Science, o modelo analisa a distribuição de probabilidades de título entre as principais potências mundiais remanescentes no torneio neste mês de julho.

---

## 📊 1. Distribuição de Probabilidades (Resultados da Simulação)

O modelo computacional gerou as seguintes probabilidades matemáticas de título para cada seleção com base no cruzamento de chaves, histórico recente e métricas de desempenho tático:

| Seleção | Probabilidade de Título (%) | Status no Modelo |
| :--- | :---: | :--- |
| 🇧🇷 **Brasil** | **18.5%** | Favorito Estatístico |
| 🇫🇷 França | 17.0% | Desafiante Principal |
| 🏴󠁧󠁢󠁥󠁮󠁧󠁿 Inglaterra | 15.2% | Candidato de Elite |
| 🇦🇷 Argentina | 14.0% | Força Consistente |
| 🇪🇸 Espanha | 11.5% | Concorrente Indireto |
| 🇵🇹 Portugal | 9.8% | Azarão Técnico |
| 🌍 Outros | 14.0% | Cauda Longa (Surpresas) |

---

## 💡 2. Insights Analíticos Extraídos via Código

### 🔹 Liderança Marginal e Alta Volatilidade
Embora o **Brasil** lidere a projeção com **18.5%** de probabilidade, a distância para a **França (17.0%)** é de apenas **1.5 ponto percentual**. 
* **Insight:** Estatisticamente, isso indica um cenário de equilíbrio extremo. Não há dominância absoluta de uma única seleção, o que significa que fatores contextuais (como cartões, prorrogações ou lesões) têm peso crítico para alterar o favoritismo real em campo.

### 🔹 Concentração de Força (Market Share)
As três principais seleções do topo (**Brasil, França e Inglaterra**) acumulam sozinhas **50.7%** de chance de conquistar o troféu.
* **Insight:** Mais da metade da probabilidade total do torneio está retida em apenas três eixos táticos. O modelo aponta uma forte polarização técnica nesta edição.

### 🔹 O Risco da "Cauda Longa" (Fator Zebra)
O agrupamento de seleções menores ("Outros") retém uma probabilidade agregada de **14.0%**.
* **Insight:** Matematicamente, a chance de uma seleção surpresa vencer a Copa do Mundo de 2026 é maior do que a chance individual de uma potência como **Portugal (9.8%)**, justificando o nível de imprevisibilidade trazido pelo novo formato expandido do torneio.

---

## 🛠️ 3. Tecnologias e Ferramentas Utilizadas

O desenvolvimento e a visualização dos dados foram executados em ambiente **Jupyter Notebook (Google Colab)**, utilizando o seguinte ecossistema de bibliotecas Python:

* **Pandas:** Para manipulação, estruturação e ordenação dos dados em DataFrames.
* **Matplotlib & Seaborn:** Para a construção e refinamento estético do gráfico de barras horizontais, aplicando técnicas de destaque visual (*Data Viz*).
* **Numpy:** Para suporte a operações matemáticas de agregação.

---

## 🚀 4. Como Executar o Projeto

1. Clone este repositório para sua máquina local:
```bash
git clone [https://github.com/Maria54-star/simulacao-copa-2026.git](https://github.com/Maria54-star/simulacao-copa-2026.git)