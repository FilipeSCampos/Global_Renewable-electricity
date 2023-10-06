### Seleção do Conjunto de Dados

**Justificação:** A escolha do conjunto de dados "global-data-on-sustainable-energy" é relevante porque ele contém informações abrangentes sobre indicadores de energia sustentável, bem como fatores econômicos e ambientais para todos os países em um período de 20 anos (2000 a 2020). Este projeto visa prever o "Acesso à eletricidade (% da população)" com base em outros indicadores presentes no conjunto de dados.

**Resumo do Conjunto de Dados:** O conjunto de dados consiste em várias colunas, incluindo informações sobre países/regiões, ano, e a variável alvo "Acesso à eletricidade (% da população)" que estamos tentando prever. Também inclui variáveis independentes que são usadas para fazer essa previsão.

### Pré-processamento de Dados

**Justificação:** Durante o pré-processamento de dados, realizamos várias tarefas, incluindo a renomeação de colunas para tornar os nomes mais legíveis e a seleção de recursos relevantes para o problema que desejamos resolver - ou seja, prever o "Acesso à eletricidade (% da população)" com base nas variáveis independentes disponíveis no conjunto de dados. Também aplicamos normalização aos dados para garantir que todas as variáveis tenham a mesma escala, o que é importante para algoritmos de regressão.

**Escolhas de Pré-processamento:** Renomeamos algumas colunas para melhorar a clareza e a legibilidade das informações. Além disso, excluímos colunas que não são relevantes para nosso objetivo de previsão do acesso à eletricidade. A normalização foi aplicada às variáveis independentes para garantir que as diferentes escalas das características não afetem negativamente o desempenho dos algoritmos.

### Aplicação de Técnicas de Mineração de Dados

**Justificação:** Optamos por aplicar três técnicas de mineração de dados: Regressão Linear, Random Forest Regressor e XGBoost Regressor. Essas técnicas foram escolhidas porque são adequadas para problemas de previsão, e estamos interessados em prever o "Acesso à eletricidade (% da população)" com base em outros indicadores. A Regressão Linear é uma escolha sólida para um início, enquanto os modelos de Random Forest e XGBoost são mais avançados e podem capturar relações complexas entre variáveis.

**Resultados:** Através da aplicação desses algoritmos, obtivemos métricas de erro, como Mean Squared Error (MSE), Mean Absolute Error (MAE) e R-squared (R²), tanto para os dados de treinamento quanto para os de validação. Essas métricas nos fornecem informações sobre o desempenho dos modelos na previsão do "Acesso à eletricidade (% da população)".
