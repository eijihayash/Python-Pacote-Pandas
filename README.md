# 🐼 **Estudos e Exercícios com Pandas / Fixação de Conceitos**

## 📘 **Descrição**
Projeto criado para **fixar conceitos essenciais e intermediários da biblioteca Pandas**, explorando leitura, manipulação e análise de dados em **Python**.  
Os exercícios utilizam diferentes **datasets reais e simulados**, abordando desde operações básicas até análises mais completas de vendas, regiões e desempenho.

---

## 🧠 **Conteúdo Estudado**

### 📍 **Parte 1 Fundamentos do Pandas**
- Introdução à biblioteca e uso de *alias* (`import pandas as pd`)  
- Estruturas de dados: `Series` e `DataFrame`  
- Leitura e exploração de dados: `head()`, `info()`, `describe()`, `value_counts()`  
- Seleção e filtragem: `loc[]`, `iloc[]`, e condições lógicas  
- Criação e modificação de colunas com `np.where()`, `map()` e `apply()`  
- Estatísticas descritivas: médias, medianas, proporções e desvio padrão  
- Agrupamentos e agregações com `groupby()`  
- Limpeza e manipulação: `drop()`, `rename()`, `isna()`  

---

### 📍 **Parte 2 — Manipulação e Análise Avançada**
- Combinação de tabelas com `merge()` (tipos: `left`, `right`, `inner`, `outer`)  
- Criação de tabelas dinâmicas com `pivot_table()`  
- Verificação e tratamento de nulos com `isna()`, `fillna()`  
- Contagem e listagem de valores únicos com `nunique()` e `unique()`  
- Agrupamentos múltiplos e cálculos de métricas personalizadas  
- Análises de **receita, quantidade e desempenho por marca, produto e estado**  
- Integração de múltiplos *DataFrames*: `orders`, `order_items`, `stores`, `brands`, `products`  

---

## 🧾 **Datasets Utilizados**
1. **Insurance Dataset** - informações sobre seguros de saúde (idade, IMC, fumo, filhos, custos, etc.)  
2. **Incêndios no Brasil** - registros mensais de incêndios por estado  
3. **Dataset de Vendas** - dados de pedidos, produtos, marcas, lojas, clientes e etc.
4. **Dataset de Estudante** - informações sobre estudantes
5. **Dataset de Banco** - informações sobre cliente que aceita e não aceita a proposta. (loan, y(sim, não), return, defaul, e etc)

---

## 💪 **Exercícios e Aplicações**
- Tratamento e verificação de **valores ausentes**  
- Criação de colunas condicionais e classificações de risco  
- Comparações entre **grupos e categorias** (ex: fumantes x não fumantes)  
- Consolidação de dados via `merge()`  
- Cruzamento de informações com `pivot_table()`  
- Cálculo e análise de **receita média e total por estado e marca**  

---

## 📊 **Principais Resultados**
- Fumantes apresentaram **custos médios mais altos** em seguros.  
- A **Região Sudeste** registrou **mais incêndios** que a **Centro-Oeste**.  
- Diferenças significativas de **receita e desempenho entre estados**, indicando oportunidades de **expansão ou otimização**.  

---

## 🛠️ **Tecnologias Utilizadas**
🐍 **Python 3**  
📦 **Pandas**  
🔢 **NumPy**  
📓 **Jupyter Notebook**


