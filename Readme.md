# Machine Learnig

Repositório destinado para estudos e práticas com a linguagem Python juntamente com a cadeira de Machine Learning (Curso Sistemas de Informação), onde foram abordados conceitos básicos acerca de pré-processamento, classificação, agrupamento e visualização de grandes quantidades de dados além de aprendizado de modelos, redes naurais, entre outros conceitos de aprendizado de máquina.

## Linguagem e Bibliotecas

### Linguagem

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

### Bibliotecas

![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)

O livro usado como norteador da cadeira foi :

- Mãos à Obra: Aprendizado de Máquina com Scikit-Learn, Keras & TensorFlow: Conceitos, Ferramentas e Técnicas Para a Construção de Sistemas Inteligentes

## Trabalho Final

A abordagem inicial do trabalho foi a seguinte:

- **Problema:** Prever o número de ocorrências cidade de São Paulo.
- **Objetivo:** Auxiliar a segurança pública no policiamento e melhorar a infraestrutura urbana.

O tipo de aprendizado escolhido foi o *Supervisionado*.

Em relação as métricas escolhidas foram:
- **MAE e RMSE:** Avaliam a precisão das previsões em termos de magnitude do erro.
- **R²:** Mede o quão bem o modelo explica a variabilidade dos dados.

Mas a abordagem que escolhemos envolvia além de modelos simples de aprendizado de máquina,
ela envolveria Redes Neurais Recorrentes usando a linha temporal construída para entender 
os eventos de sazionalidade das ocorrências criminais. A dica sugerida pelo professor foi:
- **Classificação:** trocaríamos a abordagem do problema para ser um problema de classifficação
visando separar áreas das ocorrências com base na sua quantidade em cada região, baseado apenas
na longitude e na latitude, como temos poucas *Features*, o modelo erraria bastante.
- **Plano B:** mudança do problema. 

### Plano B

Após discutir e decidir qual tema abordaríamos, o escolhido foi uma ideia abordando regressão onde :

- **Problema:** Prever o preço das passagens aéreas com base em diversos fatores.
- **Objetivo:** Auxiliar companhias aéreas e consumidores a entenderem a dinâmica dos preços e a tomarem decisões informadas sobre compra e venda de passagens.

Na abordagem utilizada, procuramos no site [Kaggle](https://www.kaggle.com/) e encontramos dados de reserva de voos da empresa [EaseMyTrip](https://www.easemytrip.com/) onde ela é uma empresa indiana multinacional de viagens online, sediada em Nova Déli, Índia. A empresa fornece reservas de hotéis, passagens aéreas, pacotes de férias nacionais e internacionais, reservas de ônibus e serviços de marca branca (produtos de preço mais económico e de qualidade relativamente baixa).

O tipo de aprendizado escolhido foi o *Supervisionado*.

Em relação as métricas escolhidas foram:
- **MAE e RMSE:** Avaliam a precisão das previsões em termos de magnitude do erro.
- **R²:** Mede o quão bem o modelo explica a variabilidade dos dados.
