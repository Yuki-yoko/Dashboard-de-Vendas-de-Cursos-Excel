# Dashboard de Vendas de Cursos — Excel

<img width="1317" height="600" alt="image" src="https://github.com/user-attachments/assets/765fb740-d61f-4bd3-9180-f4d43790ca7d" />

Dashboard interativo desenvolvido no Microsoft Excel para analisar o faturamento de cursos online (Excel, Power BI, Python e VBA), com filtros por produto e por ano, ranking de vendedores e destaque para o melhor vendedor.



## Objetivo do Projeto

Transformar uma base de dados de vendas em uma ferramenta visual e interativa, facilitando a análise do desempenho comercial por produto, ano, região e vendedor.

O dashboard permite analisar:

- Faturamento mensal ao longo do ano;
- Faturamento por região do Brasil;
- Faturamento por vendedor;
- Quantidade total de vendas;
- Faturamento por forma de pagamento;
- Melhor vendedor do período, com foto e desempenho por região;
- Comparação de resultados entre diferentes cursos e anos.

## Dados Utilizados

A base contém o registro de cada venda realizada, com as seguintes informações:

| Campo | Descrição |
|---|---|
| Data | Data em que a venda foi realizada |
| Vendedor | Vendedor responsável pela venda |
| Cliente | Nome do cliente |
| Região | Região do cliente (Norte, Nordeste, Centro-Oeste, Sudeste e Sul) |
| Produto | Curso vendido (Excel, Power BI, Python ou VBA) |
| Valor | Valor da venda em reais |
| FormaPgto | Forma de pagamento (Boleto Bancário, Cartão de Crédito ou Cartão de Débito) |


## Funcionalidades do Dashboard

### Filtros Interativos (Segmentação de Dados)

Todo o dashboard é atualizado automaticamente de acordo com os filtros selecionados:

- **Produto:** Excel, Power BI, Python e VBA
- **Ano:** 2019, 2020 e 2021

### Indicadores (KPIs)

Cartões no topo do dashboard mostram, para o filtro selecionado:

- **Quantidade Total** de vendas;
- **Faturamento Total**;
- Faturamento por **Boleto Bancário**;
- Faturamento por **Cartão de Crédito**;
- Faturamento por **Cartão de Débito**.

### Faturamento por Mês

Gráfico de linhas com o faturamento de janeiro a dezembro, permitindo identificar os meses de maior e menor desempenho e a evolução das vendas ao longo do ano.

### Faturamento por Região

Gráfico de barras que compara o faturamento entre as regiões Sul, Sudeste, Norte, Nordeste e Centro-Oeste, mostrando onde estão concentradas as vendas.

### Faturamento por Vendedor

Gráfico de colunas com o faturamento total de cada vendedor, ordenado do maior para o menor, o que facilita a comparação de desempenho da equipe.

### Melhor Vendedor em Destaque

Painel lateral que exibe automaticamente:

- **Foto** do vendedor com maior faturamento no período selecionado;
- **Nome** do vendedor;
- Faturamento dele em **cada região**;
- **Total** vendido.

A foto e as informações mudam dinamicamente conforme os filtros de produto e ano.

## Recursos do Excel Utilizados

- Tabelas e organização da base de dados;
- Tabelas Dinâmicas;
- Gráficos dinâmicos (linhas, barras e colunas);
- Segmentação de Dados conectada a várias tabelas dinâmicas;
- Fórmulas e funções de busca e referência (ex.: PROCV / ÍNDICE + CORRESP);
- Gerenciador de Nomes (para exibir a foto dinâmica do vendedor);
- Formatação condicional e personalizada;
- Design de dashboard com ícones e layout customizado.


## Objetivo de Aprendizado

Projeto desenvolvido para praticar Excel aplicado à análise de dados: construção de dashboards interativos, tabelas dinâmicas, segmentação de dados, rankings e visualização de informações.

## Autor

**Cristina Yuki Yokomizo**

Projeto desenvolvido para fins de estudo e construção de portfólio na área de Análise de Dados.
