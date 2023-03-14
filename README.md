Trata-se de um projeto desenvolvido para o trabalho de conclusão *Comparando métodos de aprendizado de máquina para previsão da demanda de viagens de bicicletas da BIXI Montreal e análise do efeito da pandemia de COVID-19 na demanda de 2020* da Pós-graduação em Ciência de dados e Machine Learning no UniCEUB, elaborado em novembro de 2021.

O código foi dividido em partes a fim de facilitar o processamento:
* Parte 1 - Tratamento dos dados;
* Parte 2 - Criação da base de simulação para o ano de 2020;
* Parte 3 - Criação dos modelos e resultados;
* Parte 4 - Análise das previsões.

Caso queira analisar o trabalho completo, ele está disponível nesse link: https://repositorio.uniceub.br/jspui/handle/prefix/15956

RESUMO: A previsão de demanda é uma atividade estratégica para uma organização planejar e dimensionar os recursos necessários para a produção de bens e serviços de forma a atender sua demanda e não ter prejuízos. Visto que estima o futuro, ela pode ser impactada com alterações no ambiente externo, como foi o caso da pandemia de COVID-19. Nesse sentido, esse trabalho tem como objetivo analisar como a demanda da BIXI Montreal foi impactada pela pandemia de COVID-19, comparando os valores reais de 2020 com valores projetados utilizando modelos de aprendizado de máquina e dados históricos. Para isso, quatro modelos usando os algoritmos LinearRegression, DecisionTreeRegressor, RandomForestRegressor e XGBRegressor de pacotes do Python foram elaborados e seus desempenhos avaliados considerando as métricas MAE, MSE, RMSE e Score. A partir disso, o melhor modelo foi escolhido, sendo utilizado para prever a demanda de 2020 e comparar a demanda real com a contrafactual. De forma geral, o modelo de Random Forest apresentou o melhor desempenho e foram realizadas três previsões de demanda diferentes. Uma delas apresentou um resultado de demanda muito superestimado. As outras duas apresentaram resultados mais realistas, demonstrando possibilidades da demanda em um cenário mais conservador e outro mais otimista. Por fim, concluiu-se que a demanda de quantidade de viagens da BIXI Montreal sofreu um impacto negativo entre 32% e 125% por causa da pandemia.

