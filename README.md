# **Previsão de Doação de Sangue com SVM**  

## **Descrição do Projeto**  

Este repositório contém um projeto de análise de dados para prever a participação de doadores de sangue em campanhas, utilizando a técnica de aprendizado de máquina **Máquina de Vetores de Suporte (SVM)**. O objetivo é identificar, com base no histórico de doações, quais doadores têm maior probabilidade de comparecer às campanhas. Essa previsão auxilia hemocentros na gestão eficiente dos estoques de sangue, garantindo disponibilidade para situações emergenciais.  

## **Contexto**  

O projeto foi idealizado por **Fátima**, funcionária da prefeitura de Rosa Branca (MG), para solucionar um problema crítico de gestão de estoque de sangue. Com a colaboração de **Francisco**, um analista de dados, surgiu a ideia de utilizar registros históricos dos doadores, como **frequência**, **quantidade doada** e **recência das doações**, para prever a participação em campanhas futuras.  

A análise foi realizada com base nos dados do arquivo **doacao.csv**, contendo 748 registros de doadores. Durante o processamento, foi identificado um **desbalanceamento** na distribuição dos dados, com mais registros de não doadores do que de doadores. Para mitigar esse problema, realizou-se um ajuste na amostragem, reduzindo a quantidade de não doadores.  

O modelo foi treinado com **SVM**, e sua eficácia foi avaliada por meio de uma **matriz de confusão** e métricas de acurácia.  

## **Objetivos**  

✔ **Prever** a participação de doadores em campanhas com base no histórico de doações.  
✔ Demonstrar o uso da **SVM** em conjuntos de dados pequenos e desbalanceados.  
✔ Fornecer uma ferramenta para **previsão antecipada** da necessidade de novas campanhas de doação.  

## **Como Executar no Google Colab**  

Para rodar o código diretamente no **Google Colab**, clique no link abaixo:  

🔗 [**Abrir no Google Colab**](https://colab.research.google.com/github/kellyortiz/previsao-doacao-sangue-svm/blob/main/previsao_doacao_sangue_svm.ipynb)  

### **Passo a passo para executar o código:**  

1️⃣ **Acesse o link** acima para abrir o notebook no Google Colab.  
2️⃣ Faça o **upload** do arquivo **doacao.csv** clicando no botão de seleção de arquivos no Colab.  
3️⃣ Execute todas as células do notebook para **treinar o modelo** e visualizar os resultados.  

## **Tecnologias Utilizadas**  

📌 **Linguagem:** Python  
📌 **Bibliotecas:** scikit-learn, pandas, numpy, matplotlib, seaborn  
📌 **Algoritmo:** Máquina de Vetores de Suporte (**SVM**)  

## **Conclusão**  

Este projeto demonstra como técnicas de **aprendizado de máquina** podem auxiliar na gestão de recursos em hemocentros, prevendo a participação de doadores e evitando escassez de sangue. A abordagem com **SVM** mostrou-se eficaz para esse tipo de problema, especialmente após o tratamento do desbalanceamento nos dados.  
