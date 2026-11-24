# Sistema de Análise de Vendas

## Sobre o projeto

Este projeto tem como objetivo realizar uma análise exploratória de dados de vendas de uma empresa brasileira do setor de tecnologia e eletrônicos, utilizando Python e suas principais bibliotecas de análise de dados.

A partir de uma base histórica de vendas, foram realizadas etapas de tratamento, organização e análise dos dados, buscando identificar padrões comerciais e indicadores relevantes para a tomada de decisões.

## Objetivos

- Realizar o tratamento e a limpeza da base de dados.
- Analisar o faturamento bruto e líquido.
- Identificar os produtos mais vendidos.
- Avaliar o desempenho das categorias de produtos.
- Analisar a evolução temporal das vendas.
- Comparar o desempenho dos vendedores.
- Identificar as preferências de pagamento dos clientes.
- Avaliar a distribuição geográfica do faturamento.
- Desenvolver visualizações para facilitar a interpretação dos resultados.

## Tecnologias utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Base de dados

A análise utiliza uma base de dados fictícia de vendas, contendo 50.000 registros iniciais e 15 colunas.

Os dados abrangem o período de 2021 a 2023 e apresentam informações sobre pedidos, produtos, clientes, vendedores, pagamentos e valores das vendas.

## Etapas do projeto

1. **Exploração inicial:** análise da estrutura, dimensões e tipos de dados.
2. **Tratamento dos dados:** identificação e tratamento de valores ausentes, duplicidades e inconsistências.
3. **Análise do faturamento:** cálculo do faturamento bruto e líquido.
4. **Volume de vendas:** identificação dos dez produtos com maior quantidade de unidades vendidas.
5. **Desempenho por categoria:** comparação do faturamento entre as categorias.
6. **Evolução temporal:** análise mensal e anual do faturamento.
7. **Desempenho dos vendedores:** identificação dos cinco vendedores com maior faturamento e cálculo do ticket médio.
8. **Formas de pagamento:** análise da participação de cada modalidade nos pedidos concluídos.
9. **Análise geográfica:** comparação do faturamento entre os estados.
10. **Visualização dos dados:** elaboração de gráficos para facilitar a interpretação dos resultados.

## Principais resultados

- Faturamento bruto das vendas concluídas: 117.583.055,20 reais.
- Faturamento líquido das vendas concluídas: 110.552.144,81 reais.
- Categoria com maior faturamento: Informática.
- Produto com maior volume de vendas: Teclado Mecânico RGB.
- Vendedor com maior faturamento: Carlos Eduardo.
- Forma de pagamento mais utilizada: Cartão de Crédito.
- Estado com maior faturamento: Paraná.
- Ano com maior faturamento: 2023.

## Visualizações

O projeto apresenta sete gráficos desenvolvidos com Matplotlib, contemplando:

- Evolução mensal do faturamento.
- Faturamento por categoria.
- Dez produtos mais vendidos.
- Cinco vendedores com maior faturamento.
- Participação das formas de pagamento.
- Faturamento por estado.
- Comparação do faturamento anual.

## Como executar o projeto

1. Clone este repositório.
2. Instale as bibliotecas necessárias:

   ```bash
   pip install pandas numpy matplotlib jupyter
   ```

3. Certifique-se de que o arquivo `vendas.csv` esteja no diretório esperado pelo notebook.
4. Abra o Jupyter Notebook e execute as células na sequência apresentada.

## Considerações finais

O projeto permitiu explorar diferentes aspectos do desempenho comercial da empresa, desde a qualidade dos dados até a identificação de padrões de faturamento, produtos, vendedores e comportamento dos clientes.

As análises demonstram como Python e suas bibliotecas podem ser utilizadas para transformar dados brutos em informações relevantes para apoiar decisões de negócio.
