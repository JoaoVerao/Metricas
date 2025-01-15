# Análise de Desempenho de Modelo com FastAI

Este projeto utiliza a biblioteca **FastAI** para treinar um modelo de aprendizado de máquina e extrair as principais **métricas de desempenho** com base na **matriz de confusão**. Após treinar o modelo, o programa calcula métricas como **Acurácia**, **Precisão**, **Recall**, **F1-Score** e a **Curva ROC** para avaliar a performance do modelo.

## Requisitos

- Python 3.10
- FastAI
- NumPy

## Como usar

<b>Carregar o conjunto de dados:</b> O programa utiliza FastAI para carregar os dados de imagens e dividir em treinamento e validação. <br>
<b>Treinar o modelo:</b> Um modelo de classificação é treinado com o conjunto de dados.<br>
<b>Extrair a matriz de confusão:</b> Após o treinamento, a matriz de confusão é extraída utilizando as funções do FastAI.<br>
<b>Calcular as métricas:</b> Com a matriz de confusão, o programa calcula as seguintes métricas:

- Sensibilidadede
- Especificidade
- Acurácia
- Precisão
- F-Score
