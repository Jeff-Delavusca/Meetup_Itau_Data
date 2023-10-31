# Meetup Itau Data
Nesse repositório você irá encontrar um script Jupyter em Python, contendo um exemplo prático de análise de dados de uma ação da bolsa de valores. 

## 1 Passo: Coleta e limpeza de dados
O primeiro passo é dedicado a fazer uma conexão via API no yfinance para extrair a série de dados da ação que será analisada. 
Posteriormente, faz-se a limpeza dos dados, ou seja, excluindo possíveis valores null ou em branco.

## 2 Passo: Manipulação de dados com pandas
Na segunda etapa, o foco esta na manipulação dos dados. 
Assim, foi necessário criar numa nova coluna com o retorno diário do ativo, com base no seu preço de fechamento de mercado.
Além disso, foram calculados os dados estatísticos, tais como: média, desvio padrão, mediana, valor máximo e mínimo diário.

## 3 Passo: Visualização de dados
Nesta etapa, foi feito a visualização do preço de fechamento diário da ação.
Também foi calculado o retorno diário acumulado e, posteriormente, plotado ambos os resultados em gráficos separados. 

## 4 Passo: Modelagem quantitativa
Por fim, foi exemplificado um modelo de precificação de ativo chamado de CAPM.
Este modelo calcula o retorno do ativo, a aprtir de um beta, que mede a sensibilidade do retorno do ativo em questão em relação a diferença do retorno de mercado com o retorno livre de risco. 
