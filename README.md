# 🚢 Projeto Titanic: Deep Learning com Keras e TensorFlow
**Candidato:** [Seu Nome Aqui]
**Perfil:** Desenvolvedor Júnior - IA (Edital Dell/IMD 2026)

Este repositório contém a implementação de uma Rede Neural Artificial para prever a sobrevivência de passageiros do Titanic. O projeto foi desenvolvido focando nos requisitos técnicos do edital da Dell Technologies em parceria com o IMD/UFRN.

---

## 🔬 Abordagem Científica
Como graduando em Física na UFRN, utilizei minha base analítica para o tratamento de dados e para compreender a estrutura de otimização da rede neural durante o treinamento.

## 🛠️ Tecnologias Utilizadas
* **Linguagem:** Python
* **Biblioteca de IA:** Keras / TensorFlow
* **Manipulação de Dados:** Pandas e NumPy
* **Engenharia de Características:** Scikit-Learn (StandardScaler e OneHotEncoder)

## 🏗️ Arquitetura do Modelo
O modelo foi construído utilizando uma estrutura `Sequential` com:
1. **Camada de Entrada:** Processamento das features padronizadas.
2. **Camadas Ocultas:** 16 e 8 neurônios com ativação **ReLU** para captar não-linearidades.
3. **Camada de Saída:** 1 neurônio com ativação **Sigmoid** para classificação binária.

## 📊 Métricas de Avaliação
O desempenho foi avaliado além da acurácia nominal, utilizando:
* **Matriz de Confusão:** Para diagnóstico de Falsos Positivos e Negativos.
* **Recall e Precisão:** Essenciais para entender a sensibilidade do modelo.
