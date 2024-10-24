# Desafio de Data Science: Prever a Satisfação do Cliente em um E-commerce

## Contexto
Você trabalha em um e-commerce que deseja melhorar a satisfação dos clientes com base nos dados de suas interações e comportamento no site. O objetivo é construir um modelo que preveja se um cliente ficará satisfeito ou insatisfeito com sua compra.

## Dataset
O dataset contém dados fictícios de clientes e suas interações no site do e-commerce. As variáveis fornecidas são:

- **ID do Cliente**: Um identificador único para cada cliente.
- **Idade**: A idade do cliente.
- **Gênero**: Masculino/Feminino/Outro.
- **Localização**: A cidade de onde o cliente acessa o site.
- **Número de Visitas**: Quantidade de vezes que o cliente visitou o site nos últimos 6 meses.
- **Valor Total Gasto**: O total de dinheiro gasto pelo cliente no site nos últimos 6 meses.
- **Número de Itens Comprados**: Quantidade de itens comprados em todas as visitas.
- **Tempo de Sessão Médio**: O tempo médio que o cliente passa no site por visita.
- **Número de Cupons Usados**: Quantidade de cupons de desconto utilizados nas compras.
- **Método de Pagamento Preferido**: Cartão de Crédito, Débito, PayPal, etc.
- **Satisfação do Cliente**: Satisfeito ou Insatisfeito (variável alvo para previsão).

## Passo a Passo do Desafio

### 1. Exploração de Dados (EDA)
- Carregar o dataset (CSV ou outro formato).
- Obter uma visão geral do dataset: verificar tipos de variáveis, estatísticas descritivas (média, mediana, desvio padrão, etc.).
- Identificar e lidar com valores ausentes.
- Criar gráficos para entender a distribuição das variáveis numéricas e categóricas.
- Verificar correlações entre as variáveis (matriz de correlação).

### 2. Limpeza e Preparação de Dados
- Tratar valores faltantes ou incorretos.
- Codificar variáveis categóricas em numéricas (one-hot encoding).
- Normalizar ou padronizar variáveis contínuas (se necessário).
- Criar variáveis derivadas, como o gasto médio por visita ou itens comprados por visita.

### 3. Análise Estatística e Hipóteses
- Analisar a relação entre a satisfação do cliente e variáveis preditivas.
- Realizar testes de hipótese (ex: verificar se a idade média de clientes satisfeitos é diferente dos insatisfeitos).

### 4. Construção do Modelo Preditivo
- Separar os dados em treino e teste (70% para treino, 30% para teste).
- Iniciar com um modelo de regressão logística.
- Avaliar o modelo usando métricas de classificação (acurácia, precisão, recall, F1-score).
- Testar modelos mais complexos (árvores de decisão, Random Forest, Gradiente Boosting).
- Realizar ajuste de hiperparâmetros (grid search).

### 5. Validação e Interpretação do Modelo
- Validar o modelo com um conjunto de validação.
- Examinar a importância das variáveis (ex: com Random Forest).
- Usar matriz de confusão e curva ROC para entender melhor o desempenho.

### 6. Visualização e Comunicação dos Resultados
- Criar gráficos para visualizar os resultados, como gráficos de barras, curvas ROC e heatmaps.
- Gerar um relatório final explicando as descobertas e insights gerados.

## Extras (opcionais)
- **Segmentação de Clientes:** Usar técnicas de clustering para agrupar clientes.
- **Análise de Séries Temporais:** Se houver dados temporais, prever satisfação ao longo do tempo.

## Dataset Real (opcional)
- [Kaggle - E-commerce Data](https://www.kaggle.com/olistbr/brazilian-ecommerce)
- [UCI Repository - Online Retail Data](https://archive.ics.uci.edu/ml/datasets/Online+Retail)
