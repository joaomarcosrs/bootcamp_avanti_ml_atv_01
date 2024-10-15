# 1. Explique, com suas palavras, o que é machine learning?
É um ramo da inteligência artificial que permite a criação de sistemas capazes de aprender e melhorar seu desempenho em uma tarefa sem serem explicitamente programados para isso. O modelo utiliza dados, que pode-se chamar experiência, para identificar padrões e ajustar seus parâmetros, com o objetivo de melhorar o desempenho em relação a uma métrica específica, que pode se acurácia ou erro médio, por exemplo. Conforme esse sistema é exposto a mais dados o desempenho tende a melhorar.

# 2. Explique o conceito de conjunto de treinamento, conjunto de validação e conjunto de teste em machine learning.
Essa etapa refere-se ao split do conjunto de dados. Onde divide-se em:
- **Conjunto de Treinamento:** Contém a maior parte dos dados e é utilizado para treinar o modelo, ou seja, é onde o modelo ajusta seus parâmetros para aprender os padrões presentes nos dados.
- **Conjunto de Validação:** Utilizado para ajustar hiperparâmetros e avaliar o desempenho do modelo durante o processo de treinamento. Ele ajuda a detectar problemas como overfitting ou underfitting, permitindo ajustes finos antes de finalizar o modelo.
- **Conjunto de Teste:** Conjunto de dados usado para avaliar o desempenho final do modelo, depois que ele foi treinado e validado. Ele oferece uma visão realista de como o modelo se comporta em dados novos, que não foram usados para seu treinamento.

# 3. Explique como você lidaria com dados ausentes em um conjunto de dados de treinamento.
- **Remoção de valores nulos (linhas ou colunas):** Se a quantidade de dados ausentes for pequena e a remoção não prejudicar a representatividade do conjunto de dados, essa técnica pode ser utilizada. É simples e evita introduzir viés.
- **Imputação de dados faltantes:** Quando a perda de dados é significativa durante a removação de valores, é mais eficiente preencher os valores ausentes com a média, mediana ou moda (para variáveis numéricas ou categóricas), ou usar técnicas mais avançadas como imputação por vizinhos mais próximos, que pode-se citar KNN ou regressão.
- **Modelos de predição para imputação:** Se os valores ausentes seguirem um padrão mais complexo, é possível treinar modelos para prever esses valores, utilizando as demais variáveis do conjunto de dados.

# 4. O que é uma matriz de confusão e como ela é usada para avaliar o desempenho de um modelo preditivo?
A matriz de confusão é uma tabela que permite visualizar o desempenho de um modelo de classificação, mostrando a distribuição de previsões corretas e incorretas. Ela divide as previsões em quatro categorias principais:
- Verdadeiros Positivos (VP),
- Verdadeiros Negativos (VN),
- Falsos Positivos (FP), e
- Falsos Negativos (FN).
A partir da matriz de confusão, métricas como **acurácia**, **precisão**, **recall**, **F1-score** e **especificidade** podem ser calculadas para fornecer uma avaliação detalhada do modelo.

# 5. Em quais áreas (tais como construção civil, agricultura, saúde, manufatura, entre outras) você acha mais interessante aplicar algoritmos de machine learning?
Gosto das aplicações em áreas que trazem benefícios diretos para a sociedade. Por exemplo, identificação de objetos para pessoas que possuem limitação na visão, assistentes virtuais que ajudam com a organização, reconhecedores de caracteres que podem retornar a informação de um lugar analisando só o nome do local, diagnóstico precoce de doenças, personalização de tratamentos e análise de imagens médicas.
