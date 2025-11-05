# 🐼 Exercícios de Pandas — Fixação de Conceitos  

## 📘 Descrição  
Este projeto reúne **dois exercícios práticos com Pandas**, desenvolvidos com o objetivo de **fixar os principais conceitos e comandos de manipulação e análise de dados**.  

Foram utilizados dois conjuntos de dados:  
- 🧾 **Insurance Dataset** — dados sobre seguros de saúde (charges, idade, IMC, fumo, etc.)  
- 🔥 **Incêndios no Brasil** — dados sobre a ocorrência de incêndios em diferentes estados e meses  

---

## 🧠 Conceitos Praticados  
- Leitura e exploração de dados com `head()`, `info()`, `describe()` e `value_counts()`  
- Filtragem de dados com `loc` e `iloc`  
- Agrupamentos e agregações com `groupby()`  
- Criação de novas colunas com condições (`np.where()` e `map()`)  
- Cálculo de médias, somas, desvios e proporções  
- Uso de **funções lambda**  
- Comparações entre grupos e categorias (ex: fumantes x não fumantes, regiões, faixas etárias)  

---

## 📊 Principais Resultados  

### 🧾 Insurance Dataset  
- Fumantes apresentaram **média de cobrança bem superior** aos não fumantes.  
- As mulheres **não fumantes** tiveram média de cobrança maior que os homens **não fumantes**, mas o contrário ocorreu entre fumantes.  
- A média do **IMC (BMI)** entre fumantes e não fumantes é semelhante, mostrando leve assimetria.  
- Pessoas com **filhos** apresentaram **média de cobrança um pouco maior** em comparação a quem não tem.  

### 🔥 Incêndios no Brasil  
- A **Região Sudeste** apresentou **mais incêndios** que a **Região Centro-Oeste**, com:  
  - Sudeste → **140.303,32 incêndios**  
  - Centro-Oeste → **137.502,55 incêndios**  
- Foram criadas colunas (`regiao_sudeste` e `regiao_centro_oeste`) para identificar os estados de cada região.  
- Também foram analisadas as **médias mensais** e o **desvio padrão de incêndios** por estado.  

---

## 🛠️ Tecnologias Utilizadas  
- **Python 3**  
- **Pandas**  
- **NumPy**  
- **Jupyter Notebook**  

---

## 📂 Estrutura do Projeto  

