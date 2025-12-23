# 🚢 Titanic Data Science: Duelo entre Deep Learning e Modelos Clássicos
**Por: Henrique Monteiro**

Este repositório é parte dos meus estudos contínuos em Ciência de Dados e Inteligência Artificial. O objetivo aqui foi aplicar modelos de Redes Neurais em um problema clássico de classificação, unindo a base matemática aprendida na graduação em Física com ferramentas modernas de IA.

## 🚀 Sobre o Projeto
Neste experimento, utilizei uma arquitetura de rede neural do tipo **MLP (Multilayer Perceptron)** com camadas densas (16 e 8 neurônios). O foco principal deste estudo foi a etapa de **Feature Engineering** e o **Benchmarking** entre diferentes algoritmos para identificar a fronteira de decisão mais eficiente para o problema.

## 🛠️ Stack Utilizada
* **Linguagem:** Python
* **Deep Learning:** TensorFlow & Keras
* **Machine Learning Clássico:** Scikit-Learn (Random Forest & SVM/SVC)
* **Análise e Visualização:** Pandas, NumPy, Seaborn e Matplotlib

## 🧠 O Duelo de Modelos
Para validar a eficácia da Rede Neural, realizei um teste comparativo com modelos consolidados de Machine Learning. Os resultados finais de acurácia foram:

| Modelo | Acurácia (Teste) | Característica |
| :--- | :--- | :--- |
| **SVM (SVC)** | **81.56%** | Vencedor: Melhor separação geométrica dos dados padronizados. |
| **Rede Neural** | 81.01% | Alta capacidade de generalização com camadas ReLU. |
| **Random Forest** | 81.01% | Robustez excepcional para dados tabulares. |

## 📉 O que foi explorado
* **Pré-processamento:** Tratamento de dados ausentes e aplicação de **StandardScaler** para garantir a convergência dos gradientes na Rede Neural.
* **Avaliação de Performance:** Uso de **Matrizes de Confusão** individuais (em gradientes de cor Blue, Green e Red) para identificar falsos positivos e negativos em cada modelo.
* **Análise Crítica:** Investigação de como o tamanho do dataset influencia a performance de modelos de Deep Learning comparados a modelos estatísticos clássicos.

## 📈 Próximos Objetivos de Estudo
Este projeto encerra a etapa de classificação binária. Meus próximos passos planejados na trilha de aprendizado incluem:
* Aprofundamento em **SQL** para manipulação de bancos de dados estruturados.
* Estudo de arquiteturas de **IA Generativa** e técnicas de RAG.
