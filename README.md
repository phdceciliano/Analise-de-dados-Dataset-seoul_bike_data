# 🚲 Previsão de Aluguel de Bicicletas - Seoul Bike Sharing

Este projeto utiliza técnicas de **Machine Learning** para prever a quantidade de bicicletas alugadas por hora em Seul, Coreia do Sul, com base em variáveis climáticas e temporais.

## 📊 Sobre o Projeto

Este projeto foi desenvolvido como parte de uma atividade prática de aprendizado de máquina, utilizando **Python** e **Jupyter Notebook**. A base de dados é o *Seoul Bike Sharing Demand*, que contém informações meteorológicas e de uso diário de bicicletas em Seul.

## 🔍 Objetivo

Prever o número de bicicletas alugadas (`Rented Bike Count`) com base em variáveis como:
- Temperatura,
- Umidade,
- Velocidade do vento,
- Precipitação,
- Visibilidade,
- Data,
- Estação do ano,
- Tipo de feriado, entre outros.

## 🗂️ Dataset

- 📁 Nome: **Seoul Bike Sharing Demand**
- 📆 Período: Janeiro a dezembro de 2017
- 📌 Fonte: UCI Machine Learning Repository

## 🛠️ Tecnologias Utilizadas

- Python 3
- Pandas
- NumPy
- Matplotlib / Seaborn
- XGBRegressor
- Scikit-learn
- Jupyter Notebook

## 🔎 Etapas Realizadas

1. **Exploração e limpeza dos dados**
   - Análise de nulos
   - Conversão de datas
   - Engenharia de atributos

2. **Análise exploratória**
   - Visualização de correlações
   - Distribuições sazonais
   - Tendências semanais e mensais

3. **Modelagem preditiva**
   - Separação em treino e teste
   - Aplicação de modelos como:
     - Regressão Linear
     - Random Forest Regressor
   - Avaliação com métricas:
     - RMSE (Root Mean Squared Error)
     - R² Score

4. **Resultados e Conclusão**
   - O modelo Random Forest apresentou melhor desempenho na previsão.
   - As variáveis mais influentes foram **Temperatura**, **Hora do dia**, **Umidade** e **Estação**.

## 📚 Conclusão

A análise demonstrou que é possível prever com boa precisão a demanda de aluguel de bicicletas com base em dados climáticos e temporais. Este projeto pode ser útil para planejamento urbano, logística e mobilidade sustentável.

## 🤖 Autor

Desenvolvido por Pedro Henrique Ceciliano, como parte do projeto em Ciência de Dados e Machine Learning.

---

📌 **Nota:** Os dados e código completo estão disponíveis neste repositório.
