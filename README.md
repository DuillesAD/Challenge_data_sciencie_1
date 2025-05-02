# Challenge_data_sciencie_1

# Análise de Dados das Lojas AluraStore

Este projeto realiza uma análise exploratória dos dados de vendas de quatro lojas da AluraStore. O objetivo é fornecer insights sobre o desempenho de cada loja em relação ao faturamento, categorias de produtos, produtos mais vendidos, avaliação dos clientes e custos de frete.

## Metodologia

1.  **Importação dos Dados:** Os dados de cada loja são importados de arquivos CSV utilizando a biblioteca Pandas.
2.  **Análise do Faturamento:** É calculado o faturamento total, a quantidade de produtos vendidos e o ticket médio para cada loja.
3.  **Vendas por Categoria:** As vendas são agrupadas por categoria de produto para identificar as categorias mais lucrativas em cada loja.
4.  **Produtos Mais Vendidos:** Os 5 produtos mais vendidos em cada loja são identificados para entender as preferências dos clientes.
5.  **Frete Médio por Loja:** O custo total de frete e o custo médio de frete são calculados para cada loja.
6.  **Visualização dos Dados:** Gráficos de barras são gerados para comparar o faturamento total, o faturamento por categoria e a avaliação média entre as lojas.
7.  **Relatório:** Um relatório final é elaborado com as principais conclusões da análise e recomendações.

## Resultados

A análise revela que a Loja 1 possui o maior faturamento total e ticket médio, enquanto a Loja 4 apresenta o menor desempenho nesses quesitos. As categorias de eletrônicos e eletrodomésticos são as que mais contribuem para o faturamento em todas as lojas. A avaliação média dos clientes é semelhante entre as lojas, com uma ligeira variação. Os custos de frete também variam entre as lojas.

### Gráficos

#### Faturamento por Loja

![Faturamento por Loja](data:image/png;base64,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...
