# Regressão Linear: Temperatura vs Vendas de Sorvete

## Contexto do Projeto

A Regressão Linear é uma das técnicas mais importantes da Estatística e do Aprendizado de Máquina Supervisionado, sendo frequentemente utilizada para modelar relações entre variáveis numéricas e realizar previsões.

Neste projeto foi desenvolvido um exemplo didático utilizando dados fictícios que relacionam a temperatura ambiente com as vendas de sorvete.

Embora simplificado, o problema ilustra conceitos fundamentais presentes em aplicações reais de Ciência de Dados, permitindo compreender desde a análise exploratória até a avaliação do desempenho do modelo.

O projeto foi desenvolvido com foco educacional, servindo como material de apoio para estudantes e profissionais que desejam aprender os conceitos básicos de regressão linear.

---

## Objetivo do Projeto

Demonstrar de forma prática como aplicar um modelo de Regressão Linear para prever vendas de sorvete a partir da temperatura ambiente.

Os objetivos específicos incluem:

* Compreender o conceito de regressão linear;
* Visualizar a relação entre variáveis numéricas;
* Construir um modelo preditivo simples;
* Avaliar o desempenho do modelo;
* Interpretar métricas de regressão;
* Visualizar o ajuste da reta aos dados observados.

---

## Base de Dados

Foi utilizada uma base de dados fictícia contendo informações sobre temperatura ambiente e vendas de sorvete.

O conjunto de dados foi criado exclusivamente para fins educacionais.

### Características da Base

| Característica       | Valor             |
| -------------------- | ----------------- |
| Tipo de Problema     | Regressão         |
| Variável Explicativa | Temperatura       |
| Variável Resposta    | Vendas de Sorvete |
| Fonte                | Dados Simulados   |

### Variáveis

| Variável         | Descrição                       |
| ---------------- | ------------------------------- |
| Temperatura (°C) | Temperatura ambiente            |
| Vendas           | Quantidade de sorvetes vendidos |

A hipótese considerada é que temperaturas mais elevadas tendem a aumentar as vendas de sorvete.

---

## Metodologia

O desenvolvimento do projeto seguiu as seguintes etapas.

### 1. Construção da Base de Dados

* Geração dos dados simulados;
* Organização em estrutura tabular;
* Verificação das variáveis.

### 2. Análise Exploratória

Foram realizadas análises iniciais para compreender a relação entre temperatura e vendas.

As análises incluíram:

* Estatísticas descritivas;
* Visualização gráfica dos dados;
* Análise da relação entre as variáveis.

### 3. Separação dos Dados

Os dados foram divididos em:

* Conjunto de treinamento;
* Conjunto de teste.

Essa etapa permite avaliar a capacidade de generalização do modelo.

### 4. Construção do Modelo

Foi utilizado o algoritmo:

* Linear Regression (Scikit-Learn)

O modelo foi treinado para estimar as vendas de sorvete com base na temperatura observada.

### 5. Avaliação do Modelo

O desempenho foi avaliado utilizando métricas clássicas de regressão:

* MAE (Mean Absolute Error);
* MSE (Mean Squared Error);
* RMSE (Root Mean Squared Error);
* Coeficiente de Determinação (R²).

### 6. Visualização dos Resultados

Foram construídos gráficos para:

* Comparar valores observados e previstos;
* Visualizar a reta de regressão;
* Interpretar a qualidade do ajuste.

---

## Resultados Principais

As análises permitiram observar uma relação positiva entre temperatura e vendas de sorvete.

Os resultados obtidos demonstram como a regressão linear pode ser utilizada para modelar relações entre variáveis numéricas e realizar previsões.

Além disso, o projeto apresenta uma introdução prática às principais métricas utilizadas para avaliação de modelos de regressão.

---

## Linguagem de Programação

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge\&logo=python\&logoColor=white)](https://www.python.org/)

---

## Bibliotecas Utilizadas

### Manipulação e Tratamento de Dados

[![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge\&logo=pandas\&logoColor=white)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge\&logo=numpy\&logoColor=white)](https://numpy.org/)

### Visualização de Dados

[![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge)](https://matplotlib.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge)](https://seaborn.pydata.org/)

### Machine Learning

[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge\&logo=scikitlearn\&logoColor=white)](https://scikit-learn.org/)

---

## Ambiente de Desenvolvimento

[![Visual Studio Code](https://img.shields.io/badge/Visual_Studio_Code-007ACC?style=for-the-badge\&logo=visualstudiocode\&logoColor=white)](https://code.visualstudio.com/)
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter_Notebook-F37626?style=for-the-badge\&logo=jupyter\&logoColor=white)](https://jupyter.org/)
[![Google Colab](https://img.shields.io/badge/Google_Colab-F9AB00?style=for-the-badge\&logo=googlecolab\&logoColor=white)](https://colab.research.google.com/)

---

## Estrutura do Projeto

```text
Regressao_Sorvete_Temperatura
│
├── dados/
│   └── dados_sorvete.csv
│
├── notebooks/
│   └── Regressao_Sorvete_Temperatura.ipynb
│
└── README.md
```

---

## Fluxo do Projeto

```text
Dados de Temperatura
          │
          ▼
Análise Exploratória
          │
          ▼
Separação Treino/Teste
          │
          ▼
Regressão Linear
          │
          ▼
Predições
          │
          ▼
MAE | MSE | RMSE | R²
          │
          ▼
Visualização dos Resultados
```

---

## Considerações Finais

Este projeto demonstra os conceitos fundamentais da Regressão Linear por meio de um exemplo simples e intuitivo.

Apesar de utilizar dados simulados, o fluxo desenvolvido é semelhante ao utilizado em aplicações reais de Ciência de Dados, envolvendo análise exploratória, treinamento de modelos, avaliação de desempenho e interpretação dos resultados.

Dessa forma, o projeto serve como uma introdução prática ao Aprendizado de Máquina Supervisionado e à modelagem preditiva utilizando Python.

---

## Referências

* https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html
* https://scikit-learn.org/stable/modules/linear_model.html
* https://pandas.pydata.org/
* https://numpy.org/
* https://matplotlib.org/

---

## Autor

**Felipe A. Camargo**

GitHub:
https://github.com/FelipeaACamargo

LinkedIn:
https://www.linkedin.com/in/felipeacamargo
