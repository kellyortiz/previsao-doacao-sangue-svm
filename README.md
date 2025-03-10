# Previsão de Doação de Sangue com SVM

## Descrição do Projeto

Este repositório contém um projeto de análise de dados para prever a participação de doadores de sangue em campanhas, utilizando a técnica de aprendizado de máquina *Máquina de Vetor de Suporte* (SVM). O sistema visa identificar quais doadores, com base em suas informações históricas, estarão presentes em campanhas de doação, ajudando a otimizar a gestão dos estoques de sangue em um hemocentro.

## Contexto

O projeto foi idealizado por Fátima, funcionária da prefeitura de Rosa Branca (MG), para resolver um problema crítico relacionado à gestão de estoque de sangue. Com a ajuda de Francisco, um analista de dados, a ideia foi utilizar os registros históricos de doadores, como frequência, quantidade doada e recência das doações, para prever se um doador comparecerá a uma campanha específica.

A análise foi realizada utilizando dados extraídos do arquivo *doação.csv*, com 748 registros de doadores. Para resolver um problema de desbalanceamento dos dados (com mais não doadores do que doadores), foi feita uma redução no número de não doadores para ajustar a classificação. Com o uso de uma SVM, a previsão foi feita, e uma matriz de confusão foi gerada para avaliar a precisão do modelo.

## Objetivos
- Prever a participação de doadores em campanhas com base nos dados históricos.
- Demonstrar o uso da SVM em conjuntos de dados pequenos e desbalanceados.
- Fornecer uma ferramenta que pode ser usada para prever a necessidade de campanhas de doação com antecedência.
