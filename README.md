# 🏬 Alura Store - Análise de Vendas com Python

Este projeto faz parte do desafio do curso da **ONE + Alura**, onde foram analisados dados de **4 lojas da Alura Store**.  
O objetivo é indicar, com base nos dados de vendas e métricas operacionais, qual das 4 lojas o Sr. João deveria vender.

---

## 🎯 Objetivo do Projeto

Realizar uma análise exploratória de dados (EDA) utilizando **Python no Google Colab**, respondendo às seguintes perguntas:

1. 💰 Qual é o **faturamento total** das lojas?  
2. 🛍️ Quais são as **categorias mais vendidas**?  
3. ⭐ Como está a **avaliação dos clientes**?  
4. 📦 Quais são os **produtos mais e menos vendidos**?  
5. 🚚 Qual é o **frete médio por loja**?  
6. ✅ Checklist final de qualidade e consistência dos dados  

---

## 🧠 Tecnologias Utilizadas

- 🐍 **Python**
- 📓 **Google Colab / Jupyter Notebook**
- 📊 **Pandas** — para tratamento e análise de dados  
- 📈 **Matplotlib** e **Seaborn** — para criação de gráficos e visualizações  
- 💾 **CSV Files** — como base de dados das lojas  

---

## 📂 Estrutura dos Dados

Cada loja possui um arquivo CSV contendo informações de vendas com as seguintes colunas principais:

| Coluna | Descrição |
|--------|------------|
| `Loja` | Nome ou número da loja |
| `Produto` | Nome do produto vendido |
| `Categoria do Produto` | Categoria a que o produto pertence |
| `Valor Unitário` | Preço do produto |
| `Frete` | Valor cobrado pelo frete |
| `Avaliação da Compra` | Nota dada pelo cliente |
| `Data da Venda` | Data em que o produto foi vendido |

---

## 📊 Principais Análises e Resultados

### 💰 Faturamento
- Calculado com base no somatório do valor das vendas de todas as lojas.
- Permite identificar a loja de maior receita e o total consolidado.

### 🛍️ Categorias mais vendidas
- Agrupamento das vendas por categoria de produto.
- Visualização em gráfico de barras ordenado do maior para o menor.

### ⭐ Avaliação dos clientes
- Cálculo da **média de avaliações** de cada loja.
- Ajuda a entender o nível de satisfação dos consumidores.

### 📦 Produtos mais e menos vendidos
- Identificação dos **5 produtos mais vendidos** e **5 produtos menos vendidos**.


### 🚚 Frete médio por loja
- Cálculo da **média** do frete.
- Visualização em **gráfico de pizza** com 4 tons distintos para cada loja.

---

## 📈 Visualizações

Foram criados gráficos com **Matplotlib** e **Seaborn**, como:

- 📊 Gráfico de barras para faturamento e categorias
- 🥧 Gráfico de pizza para frete médio
- 📦 Gráfico comparativo de produtos mais vendidos por loja

