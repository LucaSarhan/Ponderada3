# Ponderada3

## Modelo
Optei por utilizar os dados relacionados aos acidentes em estradas brasileiras como ponto de partida para a construção do meu modelo. Após selecionar o conjunto de dados, o próximo passo consistiu em determinar qual aspecto desejo prever por meio do meu modelo. Optei por antecipar a ocorrência de fatalidades em um acidente, ou seja, determinar se um acidente resultaria ou não em vítimas fatais.

Em seguida, realizei as etapas de extração, transformação e carregamento (ETL) dos dados, garantindo que estivessem em um formato adequado para possibilitar previsões precisas. Uma vez concluída essa etapa, chegou o momento de decidir qual modelo utilizar para a construção do meu sistema de previsão. Para fazer essa escolha de forma informada, executei um processo de aprendizado de máquina automatizado (AutoML) que avaliou diversos modelos e suas configurações.

Com base nos resultados desse processo, selecionarei o modelo que demonstrou o melhor desempenho. Posteriormente, estabelecerei a conexão com a minha API, permitindo que o modelo seja acessado e utilizado de forma eficaz.

[Link do meu video funcional](https://drive.google.com/file/d/1eHoY8L3-XbgarLiKmY8CtyQWt8C7WkCJ/view?usp=sharing)

[Link do meu colab](https://colab.research.google.com/drive/14lBdUNejKqsT8Vb8utNjR1Nbpsqdx9gG#scrollTo=xSIX0g0qHE26)

Para rodar o colab, basta clicar no botâo chamado 'runtime' e depois clicar em 'runtime'

## Estrutura
O projeto tem um coponente funcional o colab. O notebook do colab faz toda a parte de pré-processamento e normalização dos dados e o treinamento do modelo autoML do PyCaret. O modelo com maior acurácia é salvo e seria utilizado pela api posteriormente. O modelo com maior acurácia no meu caso foi o XGBClassifier
