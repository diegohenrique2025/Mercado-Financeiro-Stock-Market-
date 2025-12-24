# 📈 Dashboard de Análise de Mercado de Ações (Stock Market)

Este projeto apresenta uma análise técnica e histórica de ativos financeiros, permitindo monitorar a evolução de preços e volumes de negociação de grandes empresas.

## 🎯 Objetivos do Projeto
* **Evolução de Preços**: Analisar as variações de fechamento (*Close*), abertura (*Open*), máximas e mínimas.
* **Volume de Negociação**: Identificar períodos de alta liquidez e interesse do mercado.
* **Benchmarking**: Comparar a performance relativa entre diferentes empresas (ex: IBM vs Walmart).
* **Volatilidade**: Visualizar a amplitude de variação diária dos ativos.

## 🛠️ Tecnologias Utilizadas
* **Power BI**: Criação de gráficos de linha temporais e cartões de KPI.
* **DAX**: Cálculos de variação percentual (YoY/MoM) e médias móveis.
* **Modelagem**: Calendário inteligente para análise de períodos financeiros.

## 📊 Estrutura dos Dados
O dataset contém informações detalhadas de pregão:
* **Empresa**: Nome do ativo analisado.
* **Data**: Série histórica das negociações.
* **Métricas de Preço**: Open, High, Low e Close.
* **Volume**: Quantidade de ações negociadas no dia.

## 💡 Métricas Chave (DAX)
* **Variação Diária (%)**: Diferença percentual entre a abertura e o fechamento.
* **Média Móvel**: Suavização de tendências para identificar suportes e resistências.
* **Volume Acumulado**: Soma total de negociações no período filtrado.

## 📸 Demonstração
*(Adicione aqui o print do seu dashboard)*
![Dashboard Mercado Financeiro](screenshots/performance_ativos.png)

---
*Projeto focado em análise técnica e visualização de dados financeiros de alta frequência.*
