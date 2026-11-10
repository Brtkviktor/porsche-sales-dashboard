# 🏎️ Porsche Sales Dashboard

Dashboard interativo para análise de vendas de veículos Porsche, desenvolvido como projeto de análise de dados e visualização de informações.

O projeto permite explorar indicadores comerciais, comparar modelos, analisar métodos de pagamento e identificar os estados com maior volume de vendas.

## 📊 Visão geral

O dashboard apresenta uma visão consolidada dos dados de vendas, utilizando indicadores e gráficos interativos para facilitar a interpretação das informações.

### Principais indicadores

- **Receita total:** soma dos valores das vendas.
- **Quantidade de vendas:** total de registros analisados.
- **Ticket médio:** valor médio das vendas.
- **Preço médio por veículo:** indicador de preço calculado a partir dos registros.

### Visualizações

- Ranking dos 10 modelos com maior receita.
- Distribuição das vendas por método de pagamento.
- Estados com maior quantidade de vendas.
- Filtros interativos por modelo, estado, ano do veículo e método de pagamento.

## 🛠️ Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript
- Chart.js
- Git e GitHub
- GitHub Pages

## 📁 Estrutura do projeto

```text
porsche-sales-dashboard/
│
├── data/
│   └── porsche_sales_sanitized.csv
│
├── screenshots/
│   └── .gitkeep
│
├── index.html
└── README.md
```

## 🧹 Tratamento dos dados

A base de dados utilizada foi preparada antes da implementação do dashboard.

As principais etapas foram:

1. Seleção dos campos relevantes para a análise.
2. Remoção de informações pessoais e campos que não eram necessários para os indicadores.
3. Conversão dos valores numéricos para formatos adequados.
4. Padronização dos campos utilizados nos gráficos e filtros.
5. Tratamento de datas inválidas, convertendo 24 registros com datas inválidas para valores nulos.
6. Preservação dos 100 registros da base original.

A base disponibilizada no projeto contém somente os campos utilizados na análise.

## 🎯 Perguntas de negócio

O dashboard foi desenvolvido
