# DesafioAlura__TelecomX_parte2
Challenge Telecom X: análise de evasão de clientes - Parte 2 Alura 

# 📊 Churn Prediction - Telecom X
O objetivo deste projeto é analisar dados de clientes de uma empresa TelecomX e aplicar modelos de machine mearning para prever a rotatividade de clientes (Churn).
O desafio consiste em comparar diferentes algoritmos, ajustar hiperparâmetros e avaliar o desempenho dos modelos, buscando o melhor equilíbrio entre precisão e recall.

## 🎯 Objetivos
* Realizar **análise exploratória dos dados (EDA)**.
* Pré-processar variáveis (normalização, codificação e tratamento de nulos)
* Classificar variáveis em categóricas e numéricas
* Separar os dados em conjuntos de treino e teste
* Treinar e avaliar diferentes modelos de classificação
* Dummy Classifier (baseline)
* Decision Tree
* KNN (inicial e ajustado)
* Justificar escolhas de modelagem e ajustes de hiperparâmetros
* Comparar métricas: **Acurácia, Precisão, Recall, F1-score, Matriz de Confusão**
* Identificar sinais de **overfitting** e **underfitting**
* Sugerir **próximos passos** para melhoria do modelo
  
   ## 📊 Exemplos de Visualizações
 Distribuição de Churn
 Tempo de Permanência (Tenure)
 Importância das Variáveis (Árvore de Decisão)
 Matriz de Confusão - KNN Ajustado

## 📈 Principais Resultados
* **Dummy Classifier (baseline)** → Acurácia: \~0.73
* * **Decision Tree (max\_depth=3)** → Melhor **precisão** (0.69), boa generalização, sem overfitting
* **KNN Inicial** → Recall maior que a árvore, mas apresentou overfitting
* **KNN Ajustado (k=11, distância Manhattan)** → Melhor **F1-score (0.56)** e maior **recall**, equilibrando precisão e recall
* **Decision Tree** → recomendado quando a prioridade é precisão
* **KNN Ajustado** → recomendado quando a prioridade é recall (identificar mais clientes em risco de churn).

## 📌 Conclusão

- Decision Tree → melhor em precisão (menos falsos positivos)
- KNN Ajustado → melhor em recall (captura mais clientes em risco real).


