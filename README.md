# 📊 Sistema de Monitorização de Reclamações Online — Câmara Municipal da Marinha Grande

## 📄 Descrição

Este projeto consiste num sistema de recolha e monitorização de reclamações do Portal da Queixa.

Utiliza Python com Playwright para aceder a uma página dinâmica e extrair os dados, que são posteriormente
filtrados e organizados em formato JSON.

A automatização do processo é feita através de um script Bash, que permite executar o scraping, guardar os dados
e realizar uma análise simples.

---

## ⚙️ Como executar

No terminal:

```bash
bash run.sh

## 📂 Estrutura do projeto

- test_scraping.py → scraping e tratamento de dados  
- run.sh → automação  
- dados/ → ficheiros gerados

## 🔧 Tecnologias utilizadas
Python
Playwright
Bash
JSON

## ✔ Checklist de Funcionalidades

- [x] Scraping com Playwright  
- [x] Filtragem de dados  
- [x] Exportação para JSON  
- [x] Automação com Bash  
- [x] Organização por data  
- [x] Contagem de reclamações  
- [x] Histórico de execuções


 Conclusão: 
O sistema desenvolvido demonstrou ser capaz de recolher e analisar informações
relevantes de forma automatizada,permitindo identificar tendências e principais temas
nas reclamações analisadas.
Este projeto contribuiu para a consolidação de conhecimentos em automação, web scraping
e utilização de APIs, evidenciando a utilidade prática destas ferramentas na análise de dados reais.

