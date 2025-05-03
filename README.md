# 🧪 Análise de Agrupamentos e Redução de Dimensionalidade com Scikit-learn
Este projeto de Data Science explora diversas técnicas de clusterização e redução de dimensionalidade aplicadas a diferentes tipos de dados, utilizando bibliotecas do ecossistema Python como scikit-learn, matplotlib e pandas. As análises foram desenvolvidas no ambiente Google Colab e são apresentadas de forma sequencial com explicações e visualizações de apoio.

🔍 Etapas do Projeto
1. Clusterização Hierárquica no dataset Wine Quality
   
- Pré-processamento: Aplicação de escalonamento nos dados com StandardScaler.
- Dendrograma: Geração do dendrograma para visualização da hierarquia dos clusters e definição do melhor número de agrupamentos.
- Avaliação: Cálculo do coeficiente de silhueta para validar os agrupamentos.
- Discussão: Análise dos resultados obtidos e sugestões de melhoria para futuras abordagens.

2. Clusterização com KMeans no dataset Wine Quality

- Aplicação do método do cotovelo (Elbow Method) para definição do valor ideal de k.
- Cálculo do coeficiente de silhueta para avaliar a qualidade dos agrupamentos.
- Comparação com os resultados obtidos na clusterização hierárquica.

3. Explicação Visual do DBSCAN

- Descrição detalhada do funcionamento do algoritmo DBSCAN com figuras explicativas:
- Conceitos de ponto core, ponto de borda e ruído.
- Importância dos parâmetros epsilon e MinPts.

4. Aplicação do DBSCAN em Dados Sintéticos

- Geração de dados com make_moons (300 pontos).
- Aplicação do DBSCAN e visualização dos clusters por dispersão colorida.

5. Clusterização de Textos com KMeans

- Dataset utilizado: Amazon Massive Intent.
- Aplicação do método do cotovelo para definir k.
- Agrupamento com KMeans e análise qualitativa dos resultados.

6. Modelagem de Tópicos com NMF

- Aplicação do algoritmo Non-Negative Matrix Factorization no dataset da Amazon.
- Definição dos tópicos e análise interpretativa dos grupos formados.

7. Modelagem de Tópicos com LDA

- Aplicação do Latent Dirichlet Allocation no mesmo dataset textual.
- Comparação com os tópicos do NMF e análise do conteúdo extraído.

8. Redução de Dimensionalidade com KMeans vs PCA

- Dataset: Breast Cancer.
- Redução para 4 características usando KMeans e comparação direta com PCA.
- Discussão sobre desempenho, interpretabilidade e possíveis aplicações.

🛠️ Tecnologias Utilizadas
Python (Google Colab)

Scikit-learn

Pandas

Matplotlib / Seaborn

NLTK / Scikit-learn para processamento de texto

numpy

📎 Como Executar
Basta abrir os notebooks no Google Colab. Certifique-se de instalar os pacotes necessários via pip se estiver em outro ambiente.
