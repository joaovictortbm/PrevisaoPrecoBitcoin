# Previsão de Preço de Bitcoin com LSTM

Este projeto utiliza redes neurais LSTM (Long Short-Term Memory) para prever o preço de fechamento do Bitcoin, com base em dados históricos.

## Tecnologias Utilizadas

- Python 
- **Bibliotecas**:
  - TensorFlow (para construção e treinamento do modelo LSTM)
  - Keras (API de alto nível para modelos neurais)
  - NumPy (para manipulação de dados)
  - Pandas (para carregamento e pré-processamento dos dados)
  - Matplotlib (para visualização de resultados)
  - Scikit-learn (para normalização dos dados)

## Objetivo

O objetivo principal deste projeto é construir um modelo LSTM capaz de prever o preço de fechamento do Bitcoin para os próximos dias com base nos dados históricos. O modelo é treinado com dados de preços diários e volumes de transações do Bitcoin, e sua performance é avaliada utilizando métricas como `Mean Squared Error (MSE)`.

## Estrutura do Projeto

- **Pré-processamento de Dados**: Os dados históricos do Bitcoin são carregados e normalizados para garantir que o modelo LSTM possa aprender efetivamente.
- **Modelo LSTM**: O modelo LSTM é configurado e treinado para aprender a relação temporal nos dados de preços do Bitcoin.
- **Avaliação e Visualização**: O modelo é avaliado com base em sua capacidade de prever o preço de fechamento em dados de teste e ráficos são gerados para comparar as previsões do modelo com os valores reais..


