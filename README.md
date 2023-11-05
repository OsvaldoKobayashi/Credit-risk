# Fraud Detection  

Nesse Dataset analisaremos as transações de cartão realizadas pelos seus titulares na Europa em setembro de 2013. Os dados são compostos por transações de dois dias nesse mês.

Dataset: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud


Observações:
- O Dataset está extremamente desbalanceado, com uma pequena porcentagem, 0,172% sendo representada por fraudes e o restante por operações normais.
- As variáveis V1,V2,...,V28 são todas numéricas, devido a técnica de PCA (principal component analysis) aplicada para diminuir a dimensionalidade do problema, e assim evitar Overfitting (multicolinearidade, menos parâmetros para estimar).
- A técnica anterior somado ao fator confidenciabilidade dos dados bancários implicaram em uma ausência do significado de cada feature.
- o Target Class tem como resultado 1 - Fraude, 0 - Operação normal.


Objetivos:

- Aplicaremos uma análise exploratória para entender as variáveis presentes no dataset.
- Pré-processamento dos dados.
- Aplicação de modelos de Machine Learning.
- Uso de técnicas de Undersampling e Oversampling para balancear o Dataset
- Uso de métricas para avaliar a performance do modelo.
