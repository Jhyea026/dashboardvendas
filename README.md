# 📊 Dashboard de Vendas - Power BI

Este repositório contém um dashboard de vendas desenvolvido no Power BI, com o objetivo de fornecer uma visão clara e interativa sobre o desempenho de vendas de uma empresa fictícia. A análise foca nos principais indicadores de performance (KPIs) e na segmentação por diferentes dimensões do negócio.

## 📌 Objetivo do Projeto

O projeto foi criado para:
- Visualizar o faturamento total ao longo do tempo.
- Avaliar o desempenho de vendas por produto, loja, pagamento e período.
- Identificar padrões de comportamento e sazonalidade nas vendas.
- Auxiliar a tomada de decisão com base em dados confiáveis e bem estruturados.

## 🔍 Análise de Dados

A análise foi conduzida em diversas etapas:

### 1. **Modelagem dos Dados**
- Foi utilizada a tabela `Vendas`, contendo colunas como:
  - `Data da Venda`
  - `Valor da Venda`
  - `Produto`, `Categoria`, `Loja`, etc.

### 2. **Criação de Métricas DAX**
Algumas das principais métricas calculadas incluem:
- `Total de Vendas`: Soma de `Vendas[Valor Venda]`
- `Quantidade Vendida`
- `Ticket Médio`
- `Comissão`

### 3. **Visualizações**
O relatório conta com diferentes tipos de gráficos:
- Cartões de KPIs com valor total de vendas
- Gráficos de colunas, linhas e barras para análise temporal e comparativa
- Tabelas e matrizes para detalhamento de dados
- Filtros visuais para segmentar o faturamento por produto

### 4. **Interatividade**
Todos os elementos do dashboard são interativos. O usuário pode:
- Filtrar os dados por período
- Explorar por categoria, produto ou loja
- Observar tendências e variações ao longo do tempo

## 🛠️ Ferramentas Utilizadas

- Power BI Desktop
- Linguagem DAX (Data Analysis Expressions)
- Transformações no Power Query (ETL)
- Modelagem Relacional

## 🗂️ Arquivo Disponível
- `bd_dados.xlsx`: arquivo CSV contendo a base dos dados brutos analisados.
- `Template.jpg`: arquivo JPG referente ao template utilizado como tela de fundo para melhorar o visual do dashboard
- `Vendas.pbix`: arquivo do Power BI contendo todas as etapas de análise, modelagem e visualização.

## 📎 Como Utilizar

1. Faça o download do repositorio.
3. Abra Power BI Desktop para utilizar o arquivo `Vendas.pbix`.
4. Ou então abra o Excel para visualizar os dados em formato de tabela através do arquivo `bd_dados.xlsx`.
5. Explore as páginas do relatório e interaja com os filtros para obter insights.

## 🤝 Contribuições

Sugestões e melhorias são bem-vindas! Sinta-se livre para abrir uma *issue* ou *pull request*.

---

🧠 **Insight Final:** este dashboard permite compreender melhor o comportamento de vendas e fornece suporte visual e analítico para decisões estratégicas baseadas em dados.

