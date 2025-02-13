video streamlit: https://github.com/user-attachments/assets/84092b3f-d60e-4cad-915b-d39999e81dd3

# Credit Scoring - Análise de Risco de Crédito

## Visão Geral
Este projeto desenvolve um **modelo de credit scoring** para avaliar o risco de crédito de clientes de cartão de crédito. A abordagem combina técnicas estatísticas e de aprendizado de máquina para prever a probabilidade de inadimplência, utilizando um conjunto de dados com **15 safras e 12 meses de performance**.

## Objetivo
Criar um modelo preditivo robusto que auxilie instituições financeiras na **tomada de decisão de crédito**, minimizando riscos e otimizando a concessão de crédito.

## Metodologia
O projeto segue as melhores práticas de ciência de dados, estruturado nas seguintes etapas:

1. **Coleta e Entendimento dos Dados**  
   - Leitura e exploração dos dados em formato **Feather (.ftr)**
   - Análise estatística e visualização de padrões

2. **Pré-processamento e Feature Engineering**  
   - Tratamento de valores ausentes e inconsistências  
   - Normalização de variáveis numéricas (**StandardScaler**)
   - Redução de dimensionalidade com **PCA (Principal Component Analysis)**

3. **Modelagem Preditiva**  
   - Modelos utilizados:
     - **Regressão Logística**
     - **Random Forest Classifier**
   - Construção de **pipelines** com `scikit-learn`
   - Ajuste de hiperparâmetros e validação

4. **Avaliação do Modelo**  
   - Métricas de desempenho:
     - **Acurácia**
     - **ROC AUC Score**
     - **Matriz de confusão**
     - **Curva ROC**
   - Validação *out of time* (OOT) para garantir robustez

5. **Implantação e Interpretação**  
   -  Geração de relatórios interpretáveis
   -  Estratégias para integração em sistemas financeiros

##  Tecnologias Utilizadas
- **Linguagem:** Python
- **Manipulação de Dados:** `pandas`, `numpy`
- **Visualização:** `matplotlib`, `seaborn`
- **Modelagem e Machine Learning:** `scikit-learn`
- **Pipeline e Pré-processamento:** `StandardScaler`, `PCA`, `ColumnTransformer`
