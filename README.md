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

O dashboard foi desenvolvido para ajudar a responder às seguintes perguntas:

- Qual é a receita total gerada pelas vendas?
- Quantos veículos foram vendidos?
- Qual é o ticket médio das vendas?
- Quais modelos geraram maior receita?
- Quais métodos de pagamento são mais utilizados?
- Quais estados apresentam maior volume de vendas?
- Como os resultados podem ser explorados por meio de filtros?

## 🚀 Como executar o projeto

O projeto utiliza uma estrutura estática, sem necessidade de instalação de dependências ou configuração de servidor backend.

1. Clone o repositório:

```bash
git clone https://github.com/Brtkviktor/porsche-sales-dashboard.git
```

2. Entre na pasta:

```bash
cd porsche-sales-dashboard
```

3. Abra o arquivo `index.html` no navegador.

## 🌐 Acesso online

O projeto foi preparado para publicação utilizando GitHub Pages.

**Repositório:**  
https://github.com/Brtkviktor/porsche-sales-dashboard

**Dashboard online:**  
Acesse após habilitar o GitHub Pages:  
https://brtkviktor.github.io/porsche-sales-dashboard/

## 📸 Screenshots

As capturas de tela do dashboard serão adicionadas nesta seção.

```text
screenshots/
```

## 🤖 Utilização de Inteligência Artificial

A Inteligência Artificial foi utilizada como ferramenta de apoio durante o desenvolvimento, auxiliando em:

- Estruturação do dashboard.
- Organização dos indicadores e gráficos.
- Implementação de filtros interativos.
- Revisão e documentação do código.
- Organização das etapas de desenvolvimento.

As decisões de implementação, validação dos resultados e organização final do projeto fizeram parte do processo de desenvolvimento.

## 📌 Objetivo do projeto

Este projeto foi desenvolvido com o objetivo de praticar análise de dados, manipulação de informações, visualização de indicadores e desenvolvimento de interfaces interativas.

Também faz parte da construção de um portfólio de projetos voltado à área de tecnologia.

---

**Desenvolvido por [Brtkviktor](https://github.com/Brtkviktor)**  
Projeto de estudo e portfólio.
