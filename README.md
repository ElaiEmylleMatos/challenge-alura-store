# Análise Comparativa de Lojas para Decisão de Venda

## Introdução

Este projeto realiza uma análise comparativa de quatro lojas fictícias para auxiliar na decisão de qual delas seria a mais indicada para ser vendida. Através da análise de dados de vendas, faturamento, avaliação de clientes, produtos mais/menos vendidos e custos de frete, o objetivo é identificar os pontos fortes e fracos de cada loja e fornecer uma recomendação justificada.

## Estrutura do Projeto

O projeto é desenvolvido em um notebook Google Colab, contendo as seguintes etapas:

1.  **Importação dos dados:** Carregamento dos dados de vendas de cada uma das quatro lojas a partir de arquivos CSV hospedados no GitHub.
2.  **Análise de Faturamento:** Cálculo e visualização do faturamento total de cada loja.
3.  **Vendas por Categoria:** Análise e visualização da distribuição das vendas por categoria de produto em cada loja, utilizando um mapa de calor para comparação percentual.
4.  **Média de Avaliação de Clientes:** Cálculo da média de avaliação dos clientes para cada loja.
5.  **Produtos Mais e Menos Vendidos:** Identificação dos produtos com maior e menor volume de vendas em cada loja.
6.  **Frete Médio:** Cálculo e visualização do frete médio por loja, comparado à média geral.
7.  **Relatório Final:** Síntese das análises e recomendação de qual loja vender, com justificativa detalhada.

## Como Executar o Projeto

Este projeto pode ser executado diretamente no Google Colab.

1.  Abra o notebook no Google Colab.
2.  Certifique-se de ter acesso à internet para carregar os dados dos URLs fornecidos.
3.  Execute as células de código sequencialmente.

### Dependências

As principais bibliotecas utilizadas neste projeto são:

*   `pandas`: Para manipulação e análise de dados.
*   `matplotlib`: Para criação de visualizações.
*   `seaborn`: Para criação de visualizações mais avançadas (utilizado para o mapa de calor e barplot).

Todas essas bibliotecas já vêm pré-instaladas no ambiente Google Colab, portanto, não é necessária nenhuma instalação adicional.

### Execução

Basta executar todas as células do notebook em ordem. O notebook irá importar os dados, realizar as análises, gerar os gráficos e apresentar o relatório final com a recomendação.

## Resultados e Conclusão

O relatório final, presente na última célula markdown do notebook, apresenta uma análise detalhada dos indicadores de desempenho de cada loja e justifica a recomendação de qual loja deve ser vendida com base nos dados analisados.

## Possíveis Problemas e Soluções

*   **Erro ao carregar os dados:** Verifique se os URLs dos arquivos CSV estão corretos e se você tem conexão com a internet.
*   **Erros de código:** Certifique-se de executar as células na ordem correta. Se um erro ocorrer, verifique a mensagem de erro para entender o problema e corrigi-lo.
