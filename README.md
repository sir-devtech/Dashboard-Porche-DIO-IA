# Porsche Sales Intelligence

Dashboard executiva de vendas da Porsche, desenvolvida para o projeto da DIO **Criando uma Dashboard da Porsche com Agentes de IA**.

A página roda 100% no navegador (HTML, CSS e JavaScript), com filtros, KPIs, gráficos e tabela operacional.

## Links da entrega

- Repositório: https://github.com/sir-devtech/Dashboard-Porche-DIO-IA
- GitHub Pages: https://sir-devtech.github.io/Dashboard-Porche-DIO-IA/

## O que a dashboard responde

- Quais modelos lideram no recorte (e por cidade, quando o filtro de cidade está ativo)
- Qual ano de modelo mais saiu
- Ranking de vendas e receita por estado
- Mix de pagamento e status das últimas vendas

## Filtros e indicadores

Filtros: modelo, ano de modelo, cidade e método de pagamento.

KPIs: vendas filtradas, receita total (com ticket médio), modelo líder e ano dominante.

## Dados públicos (cuidado do lab)

O GitHub Pages é aberto. Por isso este repositório **não publica**:

- nomes de clientes (`customer_name`)
- nomes de vendedores
- colunas brutas da planilha original

Entra só o recorte sanitizado usado na análise:

`SaleDateSanitized`, `PorscheModelSanitized`, `ModelYearSanitized`, `CitySanitized`, `StateSanitized`, `PayMethodSanitized`, `SalesPriceSanitized`, `DeliveryStatusSanitized`.

Datas inválidas aparecem como **Sem data**.

Fonte: [planilha base Porsche (Sanitizada)](https://hermes.dio.me/files/assets/8683bed0-cc33-4e06-bca9-04db9c31f9e2.xlsx), material complementar da DIO.

## Como abrir localmente

Abra `index.html` no navegador. Os gráficos usam Chart.js via CDN.

## Tecnologias

HTML, CSS, JavaScript e Chart.js. Estrutura e insights montados com apoio de IA (Cursor), a partir da base sanitizada do lab.
