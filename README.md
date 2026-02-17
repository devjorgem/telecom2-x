# telecom2-x
entrega del segundo challenge de la escuela alura data science

El objetivo fue desarrollar un modelo de clasificación binaria capaz de predecir qué clientes tienen alta probabilidad de abandonar el servicio (churn), permitiendo a la empresa tomar acciones preventivas y reducir la pérdida de clientes.

El flujo de trabajo fue el siguiente:

Separación de variables predictoras (X) y variable objetivo (y)

División en conjunto de entrenamiento y prueba (80/20)

Escalado de variables con StandardScaler

Balanceo del set de entrenamiento usando SMOTE

Entrenamiento de tres modelos:

Logistic Regression

KNN

SVM

Evaluación con métricas:

Accuracy

Precision

Recall

F1-score

ROC-AUC

📊 Resultados
Modelo	Accuracy	Precision	Recall	F1	ROC-AUC
Logistic Regression	0.765	0.539	0.786	0.640	0.853
KNN	0.687	0.446	0.735	0.556	0.760
SVM	0.767	0.549	0.693	0.612	0.826
