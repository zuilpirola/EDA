# Projeto de Análise Exploratória de Dados (EDA)  
## Dataset: Ames Housing

---

## Objetivo

O objetivo deste projeto é realizar uma Análise Exploratória de Dados (EDA) completa sobre o dataset Ames Housing, com foco na variável alvo:

**SalePrice** (preço de venda dos imóveis)

Os alunos deverão investigar os dados, identificar padrões, tratar problemas e justificar quais variáveis são mais adequadas para um modelo de regressão linear.

---

## Contexto

O dataset Ames Housing descreve características de imóveis residenciais na cidade de Ames, Iowa (EUA). Ele contém diversas variáveis explicativas relacionadas a:

- Tamanho  
- Localização  
- Qualidade  
- Ano de construção  
- Características físicas  

---

## Objetivos específicos

Ao final do projeto, espera-se que o aluno seja capaz de:

- Compreender a estrutura de um dataset real  
- Identificar e tratar valores ausentes  
- Detectar outliers  
- Analisar distribuições de variáveis  
- Avaliar relações entre variáveis  
- Identificar multicolinearidade  
- Selecionar variáveis relevantes para regressão  
- Comunicar insights de forma clara  

---

## Etapas obrigatórias

### 1. Entendimento dos dados
- Descrever o dataset (número de linhas, colunas, tipos de dados)  
- Identificar variáveis numéricas e categóricas  
- Interpretar o significado das variáveis principais  

---

### 2. Análise Univariada

Para cada variável (ou principais variáveis):

- Distribuição (histogramas)  
- Assimetria (skewness)  
- Identificação de outliers  
- Análise de missing data  

**Responder:**

- Quais variáveis parecem relevantes?  
- Quais devem ser descartadas? Por quê?  

---

## 3. Análise de Correlação

- Matriz de correlação (especial foco em variáveis numéricas)  
- Correlação com SalePrice  
- Identificação de:
  - Variáveis fortemente correlacionadas com o target  
  - Multicolinearidade entre variáveis independentes  

**Responder:**

- Quais variáveis são bons candidatos para regressão?  
- Existem variáveis redundantes?  

---

## 4. Análise Bivariada (opcional mas recomendado)

- Relação entre variáveis explicativas e SalePrice  
- Uso de scatterplots, boxplots ou gráficos equivalentes  

---

## 5. Seleção de Variáveis

Com base na análise:

- Selecionar um conjunto de variáveis para regressão linear  
- Justificar escolhas com base em:
  - Correlação  
  - Distribuição  
  - Qualidade dos dados  

---

## Entregáveis

### 1. Notebook (obrigatório)

- Código bem organizado e comentado  
- Deve permitir reproduzir toda a análise  
- Estrutura clara com seções bem definidas  

---

### 2. Relatório (obrigatório)

Pode ser em PDF ou Markdown.

Deve conter:

- Explicação das etapas realizadas  
- Justificação das decisões  
- Principais insights encontrados  
- Conclusões finais  

**Importante:**  
O relatório deve fazer referência direta ao código (por exemplo: “ver célula X”).

---

## Integração código e relatório

O avaliador deve conseguir facilmente:

- Ir do relatório para o código  
- Entender como cada conclusão foi obtida  

**Sugestões:**

- Referenciar células do notebook  
- Usar títulos consistentes  
- Manter organização lógica  

---

## Boas práticas esperadas

- Código limpo e legível  
- Uso adequado de gráficos  
- Justificações claras (não apenas mostrar gráficos)  
- Evitar conclusões superficiais  

---

## Evitar

- Apenas descrever gráficos sem interpretar  
- Ignorar missing values  
- Ignorar outliers  
- Usar variáveis sem justificar  
- Copiar análises prontas  

---

## Dicas

- Comece simples e aprofunde depois  
- Nem todas as variáveis são úteis — saber descartar faz parte  
- Correlação não implica causalidade  
- Clareza é mais importante que complexidade  

---

## Ferramentas sugeridas

- Python (pandas, numpy)  
- matplotlib / seaborn  
- Jupyter Notebook

---

## Observação final

Este projeto não avalia apenas código, mas principalmente:

capacidade analítica, pensamento crítico e comunicação