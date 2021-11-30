**TFG**
=====================================

Este proyecto está orientado a la predicción del precio de la luz usando métodos de Deep Learning. La predicción de la luz es una tarea compleja en la que intervienen multitud de variables. Los productores y consumidores se benefician mucho de este tipo de predicciones puesto que les permite ajustar su estrategia en el mercado de la luz que se celebra cada día.

Se han implementado los siguientes modelos para la predicción de la luz: Random Forest, Multilayer Perceptron y TCN. Además, para hiperparametrizar éstos modelos, se ha implementado los algoritmos RandomSearch, HyperBand y BayesianOptimization. Por otra parte, se obtienen los datos con los que entrenar y probar los modelos de la API de Esios, guardándose en archivos csv los cuales usan los distintos métodos de predicción e hiperparametrización. Para comparar éstos modelos, se ha implementado los métodos MAE, MAPE Y WAPE que se basan en las métricas con sus respectivos nombres.
