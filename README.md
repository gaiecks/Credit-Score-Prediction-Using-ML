# Previsão de Score de Crédito com Machine Learning

Este projeto tem como objetivo desenvolver um modelo preditivo para calcular o Score de Crédito de clientes utilizando técnicas de Machine Learning. 
Através de um conjunto de etapas que incluem análise exploratória de dados, visualizações, tratamento de dados, tratamento de valores missing, engenharia de atributos, normalização dos dados, OneHotEncoding, além da criação, treino e teste de um modelo de Machine Learning, conseguimos prever o Score de Clientes baseados nas variáveis de entrada.

O projeto foi desenvolvido na linguagem Python através do ambiente do Google Colab.


# Projeto Completo

Para acessar o projeto completo, clique no link:
[Credit_Score](https://github.com/gaiecks/Credit-Score-Prediction-Using-ML/blob/main/Credit_Score.ipynb)


# Etapas do Projeto

1. **Importação de Bibliotecas e Dataset:**
   - Importação das bibliotecas necessárias
   - Carregamento do dataset
   - Análise da estrutura do dataset

2. **Pré-processamento:**
   - Tratamento de variáveis categóricas e numéricas
   - Tratamento de valores missing
   - Conversão de variáveis para os tipos apropriados
   - Substituição de valores nulos pela mediana
     
3. **Análise Exploratória de Dados:**
   - Análise estatística básica
   - Identificação e tratamento de outliers
   - Visualização de distribuições e correlações entre variáveis

4. **Engenharia de Atributos:**
   - Criação de faixas etárias a partir da variável "IDADE"
   - Label Encoding para variáveis categóricas


5. **Preparação dos Dados para o Modelo:**
   - Separação das variáveis preditoras e da variável alvo (SCORE)
   - Divisão dos dados em conjuntos de treino e teste
   - Normalização dos dados

6. **Criação e Avaliação do Modelo:**
   - Treinamento do modelo de Regressão Linear
   - Avaliação do modelo utilizando a métrica R²

7. **Simulação de Previsões:**
   - Simulação de previsões com dados de um potencial cliente


## Conclusão

O modelo desenvolvido atingiu uma acurácia de aproximadamente 79%, indicando uma boa capacidade preditiva para o Score de Crédito de clientes. A partir deste ponto, podemos simular diferentes situações ajustando os valores das variáveis de entrada.
