# Projeto de detecção de fraude em cartões de crédito

Este projeto demonstra como usar um modelo de floresta aleatória (Random Forest) para detectar transações fraudulentas em um conjunto de dados de transações de cartão de crédito. O projeto utiliza bibliotecas populares de ciência de dados como Pandas, NumPy, Matplotlib, Seaborn e Scikit-learn.

Requisitos

Python 3.x

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Você pode instalar as dependências usando pip:

pip install pandas numpy matplotlib seaborn scikit-learn

Para o dataset, é possível baixar pelo Kaggle: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

# Estrutura do projeto

Importação de Bibliotecas: Importamos as bibliotecas necessárias para manipulação de dados, visualização e construção do modelo.

Carregamento e Exploração dos Dados: Carregamos o dataset de transações de cartão de crédito e exploramos os dados com métodos como head(), describe() e info().

Preparação dos Dados: Separamos as features da label, normalizamos as features e dividimos os dados em conjuntos de treinamento e teste.

Treinamento do Modelo: Treinamos um modelo de floresta aleatória com os dados de treinamento.

Fazer Previsões: Utilizamos o modelo treinado para fazer previsões com os dados de teste.

Avaliação do Modelo: Avaliamos o desempenho do modelo usando métricas como acurácia, precisão, recall, F1-score e matriz de confusão.

Visualização da Matriz de Confusão: Visualizamos a matriz de confusão usando a biblioteca Seaborn.
