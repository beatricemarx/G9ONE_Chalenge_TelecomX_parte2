Desafio 3 de DS

# 📊 TelecomX - Análise de Churn (Evasão de Clientes)

Este projeto consiste em uma análise detalhada de retenção de clientes para a empresa fictícia **TelecomX**. O objetivo principal é identificar os fatores que levam os clientes a cancelarem seus serviços (churn) e construir modelos de Machine Learning para prever esses comportamentos.

## 🚀 Sobre o Projeto

A perda de clientes (Churn) é uma das métricas mais críticas para empresas de telecomunicações. Através deste notebook, realizamos o ciclo completo de ciência de dados: desde a extração e limpeza até a modelagem preditiva e interpretação de resultados.

## 📋 Etapas do Projeto

O arquivo está dividido nas seguintes seções:

1.  **Extração (Coleta):** Importação de bibliotecas (`pandas`, `seaborn`, `matplotlib`) e carregamento do dataset.
2.  **Transformação (Limpeza e Tratamento):**
    * Remoção de colunas irrelevantes (como `customerID`).
    * Tratamento de dados nulos e conversão de tipos (ex: `TotalCharges`).
    * Codificação de variáveis categóricas para modelos numéricos.
3.  **Análise Exploratória (EDA):** Identificação de padrões visuais entre variáveis como tipo de contrato, tempo de permanência e churn.
4.  **Modelagem:** Implementação e comparação de algoritmos de classificação.
5.  **Avaliação:** Análise de desempenho através de métricas como Acurácia, Precision, Recall e F1-Score.

## 🔍 Principais Insights

Com base nos dados analisados, os fatores que mais influenciam a evasão são:
* **Tipo de Contrato:** Clientes com contratos "mês a mês" possuem taxa de churn muito superior aos contratos anuais.
* **Serviços de Internet:** Usuários de Fibra Óptica apresentam maior propensão ao cancelamento.
* **Tempo de Permanência (Tenure):** Clientes novos têm maior probabilidade de sair nos primeiros meses.
* **Serviços Adicionais:** A ausência de Suporte Técnico e Segurança Online está diretamente ligada à saída do cliente.



## 🛠️ Tecnologias Utilizadas

* **Linguagem:** Python 3.x
* **Manipulação de Dados:** Pandas, NumPy
* **Visualização:** Seaborn, Matplotlib
* **Machine Learning:** Scikit-learn

## 📈 Modelos Avaliados

Os seguintes algoritmos foram testados para encontrar o melhor equilíbrio entre precisão e recall:
* Regressão Logística
* Árvores de Decisão (Decision Trees)
* K-Nearest Neighbors (KNN)



## 💡 Estratégias Recomendadas

Para reduzir a taxa de churn na TelecomX, sugere-se:
1.  Incentivar a migração de contratos mensais para planos anuais com descontos.
2.  Oferecer pacotes de suporte técnico gratuito para clientes de fibra óptica.


---
📝 *Este projeto foi desenvolvido como parte de um desafio técnico de análise de dados.*
