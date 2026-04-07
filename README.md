# AdventureWorks – Data Analytics Project

Projeto de Data Analytics desenvolvido para analisar o desempenho de vendas da empresa fictícia AdventureWorks, utilizando SQL, Python e Power BI, desde a exploração dos dados até a entrega de um dashboard executivo.

---

## 📌 Contexto

A AdventureWorks é uma empresa fictícia do setor de varejo, amplamente utilizada em estudos de Business Intelligence e Analytics.  
Este projeto tem como objetivo analisar o comportamento das vendas ao longo do tempo, identificar produtos estratégicos, entender o perfil dos clientes e avaliar padrões de sazonalidade.

---

## 🎯 Desafio

O principal desafio do projeto foi desenvolver uma solução completa de análise de dados em um ambiente corporativo com **restrições de instalação de ferramentas locais**, exigindo um pipeline robusto, organizado e adaptável.

Era necessário garantir:
- Confiabilidade e clareza dos dados
- Separação adequada entre tratamento e visualização
- Entrega de insights objetivos para tomada de decisão

---

## 🛠️ Solução Desenvolvida

O projeto foi estruturado seguindo um pipeline completo de Data Analytics:

1. **Exploração inicial em SQL (SQLite)**
   - Análise de vendas por período
   - Identificação de produtos e clientes com maior volume
   - Avaliação inicial de concentração e sazonalidade

2. **ETL em Python**
   - Normalização e tratamento dos dados
   - Criação de métricas de negócio (vendas, margem e volume)
   - Consolidação da tabela fato
   - Geração de datasets prontos para consumo no BI

3. **Visualização no Power BI Web**
   - Construção de dashboard executivo
   - Storytelling focado em tomada de decisão
   - Visualização de KPIs, produtos, clientes e sazonalidade

Devido às restrições do ambiente, toda a lógica de negócio e métricas foi concentrada no ETL em Python, utilizando o Power BI Web exclusivamente para visualização.

---

## 📊 Principais Insights

- Crescimento consistente do volume de vendas entre 2015 e 2017  
- Portfólio de produtos orientado a alto giro, com destaque para o *Water Bottle – 30 oz.*  
- Base de clientes altamente pulverizada: os 10 maiores clientes representam apenas **1,18%** do volume total de vendas  
- Forte influência de sazonalidade, com picos de vendas entre **abril e junho**, além de um pico significativo em **dezembro**

---

## 🧰 Tecnologias Utilizadas

- SQL (SQLite)
- Python (Pandas, NumPy, Requests)
- Ingestão de dados via HTTP
- Power BI Web
- Git & GitHub

---

## 📁 Estrutura do Repositório

adventureworks-data-analytics/
├── data/
│   ├── raw/              # Dados brutos
│   └── processed/        # Dados tratados e prontos para análise
├── notebooks/            # Notebooks de ETL e análise
├── dashboards/           # Evidências visuais do dashboard
├── README.md

---

## ✅ Status do Projeto

✔ Projeto concluído  
✔ Pipeline completo de dados  
✔ Dashboard executivo finalizado  
✔ Pronto para portfólio e apresentação profissional
