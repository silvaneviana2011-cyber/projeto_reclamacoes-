# 📊 Sistema de Monitorização de Reclamações Online — Câmara Municipal da Marinha Grande

## 📄 Introdução

Este projeto consiste no desenvolvimento de um sistema automatizado de recolha e monitorização de 
reclamações públicas disponíveis no Portal da Queixa.

A necessidade de analisar feedback dos cidadãos motivou a criação de uma solução que permita recolher, 
organizar e interpretar dados de forma eficiente.

---

## 🎯 Objetivo

O principal objetivo deste projeto é desenvolver um sistema capaz de:

- Recolher automaticamente reclamações de uma plataforma online  
- Filtrar e organizar os dados relevantes  
- Armazenar a informação em formato estruturado (JSON)  
- Automatizar o processo de recolha e análise  

---

## ⚙️ Funcionamento

O sistema é composto por duas componentes principais:

### 🐍 Python (Playwright)
- Acede à página web dinâmica  
- Extrai o conteúdo textual  
- Filtra dados irrelevantes  
- Organiza os dados em formato JSON  

### 🖥️ Bash
- Executa o script Python  
- Cria diretórios automaticamente  
- Guarda os dados com data e hora  
- Realiza validação e análise simples  

---

## ▶️ Como executar

No terminal, dentro da pasta do projeto:


```
bash
bash run.sh



```


### 

## 📌 Conclusão

O sistema desenvolvido permite recolher e analisar automaticamente reclamações do Portal da Queixa,
organizando os dados de forma estruturada em formato JSON.
A integração de Python com Playwright e Bash demonstrou a eficácia da automatização na recolha,
tratamento e organização da informação, tornando o processo mais eficiente e reutilizável.
Esse modelo de projecto envolveu aprendizagens ativas, através da aplicação prática de conceitos de
programação, automação e web scraping.  
A resolução de problemas reais permitiu consolidar conhecimentos e desenvolver competências técnicas
de forma autónoma. O processo contribuiu para uma melhor compreensão das ferramentas utilizadas e da
sua aplicação em contextos reais.
Como perspetiva futura, o sistema poderá ser melhorado com a integração de bases de dados e análise
mais avançada dos dados recolhidos, a dar resposta para as necessidades do mercado de trabalho, para a prestação de
serviços eficiente.
