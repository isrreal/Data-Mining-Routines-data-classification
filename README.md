# Mineração de Dados: Rotina de classificação de dados.

Este repositório é uma continuação da etapa de [pré-processamento](https://github.com/isrreal/Data-Mining-Routines-preprocessing).
Serão aplicados métodos de aprendizado de máquina para realizar tarefas de classificação de dados. A base de dados utilizada é 
[Food choices: College students' food and cooking preferences](https://www.kaggle.com/datasets/borapajo/food-choices?select=food_coded.csv) 
e são avaliados vários algoritmos de classificação para determinar sua eficácia. O objetivo é entender como diferentes métodos de aprendizado de máquina se comportam em relação à acurácia na classificação de dados.

## A solução será dividida em várias etapas:

### 1. Pré-processamento dos dados:

Limpeza do conjunto de dados, tratando valores ausentes, removendo duplicatas e realizando transformações necessárias, assim, normalizando-o.
Os dados pré-processados estão no repositório de [pré-processamento](https://github.com/isrreal/Data-Mining-Routines-preprocessing).


### 2. Divisão do conjunto de dados:
Divisão do conjunto de dados em um conjunto de treinamento e um conjunto de teste para avaliar o desempenho dos algoritmos.
O mesmo conjunto de teste é usado por todos os algoritmos analizados e nenhum dado deste pode ser usado na fase de treinamento.
O atributo alvo (rótulo) da classificação será o campo self_perception_overweight.




### 3. Seleção de algoritmos de classificação:
Seleção de uma variedade de algoritmos de aprendizado de máquina para testar na tarefa de classificação.
A seleção contêm os seguintes algoritmos de classificação supervisonada, juntamente com a descrição de cada um: 
Naive Bayes, k-Nearest Neighbors, Support Vector Machine (Linear/RBF), Decision Trees, Random Forest.




### 4. Treinamento e avaliação:
Treinamento dos algoritmos de classificação usando todo o conjunto de treinamento.
Avaliação do desempenho de cada algoritmo no conjunto de teste usando métricas como acurácia, precisão, recall e F1-score.
Repetição da análise treinando os algoritmos com validação cruzada.
Repetição da análise realizando ajuste de hiperparâmetros.

### 5. Análise dos resultados:
Um texto que descreve os resultados obtidos e uma análise crítica destes resultados.
Comparação do desempenho dos diferentes algoritmos e uma explicação do porquê de alguns apresentaram resultados mais adequados que outros.
