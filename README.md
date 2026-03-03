# Análise Exploratória de Dados – Construfácil

Este repositório contém um notebook Jupyter com a análise de dados de vendas
das lojas de material de construção da rede Construfácil. Os dados foram
extraídos de um arquivo Excel e diversas etapas de limpeza, transformação
e visualização foram realizadas para entender o comportamento de vendas,
lucratividade e outras métricas relevantes.

## Estrutura do notebook

1. **Importação de bibliotecas**: `pandas`, `numpy` e `plotly.express`.
2. **Carregamento dos dados**: leitura do Excel em `df`.
3. **Inspeção inicial**: `df.info()`, tipos de dados e valores nulos.
4. **Tratamento de dados**:
    - Conversão da coluna `Data_Venda` para datetime.
    - Limpeza dos nomes dos vendedores (remoção de prefixos).
    - Cálculo de custo total, lucro e classificação de resultado (lucro/prejuízo).
5. **Análises exploratórias**:
    - Quantidade e valor total de vendas por método de pagamento.
    - Quantidade e valor de vendas por vendedor.
    - Vendas por categoria de produto.
6. **Visualizações**:
    - Gráficos de barras para métodos, vendedores e categorias.
    - Funis para produtos mais lucrativos e os que geraram prejuízo.
    - Gráficos de vendas e lucro mensais com média móvel de 3 meses.
7. **Análises financeiras**:
    - Lucro total, prejuízo e vendas mensais.
    - Projeções via média móvel e avaliação de sazonalidade.
8. **Insights potenciais**:
    - Produtos estratégicos que merecem mais estoque/marketing.
    - Possíveis causas de prejuízo (preço mal definido, custo alto ou produto encalhado).
    - Perguntas sobre lucratividade crescente, sazonalidade e manutenção de
      determinados produtos.

## Requisitos

- Python 3.x
- pandas
- numpy
- plotly
