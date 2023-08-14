# Projeto de Análise de Crédito no Kaggle
Bem-vindo ao nosso projeto de análise de dados e modelagem de machine learning, desenvolvido para a empolgante competição no Kaggle! Neste desafio, mergulhamos na avaliação de aumento de limite de cartão de crédito para o renomado Billion Bank
   <p align="center"><strong><a href="https://www.kaggle.com/competitions/cdshackdays3/overview">Mais detalhes </a></strong></p>

## Contexto do Projeto
Imagine o Billion Bank, um banco digital inovador no Brasil, em busca de aprimorar seu processo de avaliação de aumento de limite de cartão de crédito. O objetivo é claro: reduzir custos operacionais e, ao mesmo tempo, aprimorar a experiência do cliente. Atualmente, o banco depende de informações de uma empresa de crédito terceirizada para decidir sobre os pedidos de aumento de limite. No entanto, devido a demoras e um aumento no número de clientes insatisfeitos (churn), o banco decidiu trilhar um novo caminho.

## Objetivos do Projeto
Nosso projeto tem um objetivo central: criar um poderoso modelo de classificação. Esse modelo será responsável por determinar se um pedido de aumento de limite deve ser "negado" ou "concedido" a um cliente. Para atingir esse objetivo, exploramos profundamente o histórico financeiro dos clientes, selecionamos as características mais relevantes, treinamos um modelo de Gradient Boosting e avaliamos seu desempenho com rigor.

## O que o Projeto Contém
Nossa jornada está organizada em seções distintas, cada uma desempenhando um papel crucial no desenvolvimento do projeto:

* Preparação dos Dados: Começamos carregando os dados de treinamento e realizando transformações essenciais. Além disso, mergulhamos em uma análise exploratória detalhada para compreender melhor os dados e pré-processamos tudo para o próximo estágio.
* Processamento dos Dados: Nesta etapa, empregamos a técnica Boruta para selecionar as características mais relevantes e efetuamos a normalização dos dados, preparando-os para a modelagem.
* Modelagem: Aqui está o coração do projeto. Treinamos um modelo Gradient Boosting Classifier, avaliamos métricas de desempenho cruciais e refinamos os hiperparâmetros com a ajuda da biblioteca PyCaret.
* Teste: Levamos nosso modelo treinado para um teste de fogo nos dados de teste. Geramos previsões sólidas e as preparamos para a tão aguardada submissão.

## Conquistas e Resultados
Nossa dedicação deu frutos notáveis. O modelo que construímos se destaca, alcançando uma impressionante acurácia de 87% na previsão de aprovação de aumento de limite de cartão de crédito. Além disso, investigamos mais a fundo e relatamos as métricas de precisão, recall e F1-score para várias categorias. Quer saber mais? Basta dar uma olhada em nosso notebook para explorar todas essas métricas em detalhes.
