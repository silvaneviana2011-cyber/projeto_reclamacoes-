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

´´´

## 🏛️ Potencial de Impacto Institucional

Este projeto apresenta potencial de aplicação em contextos institucionais, nomeadamente em autarquias 
e organismos públicos, ao permitir uma análise estruturada das reclamações submetidas por cidadãos.

Através da organização e monitorização de dados, a solução desenvolvida pode contribuir para:
Melhoria da eficiência dos serviços públicos, através da identificação de padrões recorrentes de reclamações
Apoio à tomada de decisão, com base em dados concretos e atualizados.

Aumento da transparência institucional, facilitando o acompanhamento e resolução de ocorrências
Identificação de áreas críticas, permitindo a priorização de intervenções.
Promoção da satisfação do cidadão, através de respostas mais rápidas e informadas.

Este tipo de abordagem orientada por dados pode ser aplicado em contextos municipais e 
em organizações públicas, contribuindo para a modernização administrativa e melhoria da governação.


## 📊 Exemplo de Output

O sistema gera ficheiros JSON com as reclamações recolhidas:

PS C:\Users\silva\Desktop\projeto_reclamacoes> python test_scraping.py

  {
    "id": 2,
    "reclamacao": "Reclamação da rua Do Bairro da Benta venho por este meio solicitar a reparação de um buraco que se abriu na Rua do Bairro da Benta que torna perigoso pois circulam…"
  },
  {
    "id": 3,
    "reclamacao": "Venho por este meio apresentar uma reclamação formal relativa ao estado de abandono em que se encontra a freguesia de Vieira de Leiria e Praia da Vieira, após a…"
  },
  {
    "id": 4,
    "reclamacao": "Venho, por este meio, apresentar nova reclamação relativamente à qualidade da água fornecida pela rede pública, situação esta que já foi anteriormente reportada…"
  },
  {
    "id": 5,
    "reclamacao": "Venho por este meio comunicar o meu desagrado em relação á informação (ou falta dela) da ausência de água em certas alturas na rua clube desportivo da Garcia, hoje…"
  },
  {
    "id": 6,
    "reclamacao": "Em menos de uma semana presenciei 2 carros em altíssima velocidade na Rua das Figueiras em BoaVista, mais precisamente na altura do Supermercado Quintino, carros…"
  },
  {
    "id": 7,
    "reclamacao": "Gostava de saber para que serve o Regulamento Municipal para o ruído,que foi aprovado e supostamente á data já deveria estar em execução á mais de 1 ano?"
  },
  {
    "id": 8,
    "reclamacao": "Na data de 16/12/2024, redigi por escrito uma queixa na Câmara, á qual perdi tempo no emprego,para trazer a declaração carimbada,na esperança de alguma resposta.…"
  },
  {
    "id": 9,
    "reclamacao": "Prezados Senhores, Venho por meio desta reclamar sobre o serviço de religação de água prestado pela vossa empresa. No dia de ontem, foi-me informado que a religação…"
  },
  {
    "id": 10,
    "reclamacao": "É lamentável o estado de falta de limpeza em que sencontra a Praia de Vieira de Leiria completamente deixada ao abandono em termos de limpeza. Muito gostava que…"
  },
  {
    "id": 11,
    "reclamacao": "Câmara Municipal da Marinha Grande - Direito a informação: data que a câmara responde ao processo de arquitetura aprovado em 31/10/22"
  },
  {
    "id": 12,
    "reclamacao": "A sentença referente ao processo 505/21 00T9 MGR..ponto 17 sentenciou : ora há um claro fim de persecução pública: celeridade dos procedimentos municipais, imparcialidade…"
  }
]


## 📌 Conclusão

O sistema desenvolvido permite recolher e analisar automaticamente reclamações do Portal da Queixa,
organizando os dados de forma estruturada em formato JSON.
A integração de Python com Playwright e Bash demonstrou a eficácia da automatização na recolha,
tratamento e organização da informação, tornando o processo mais eficiente e reutilizável.
Esse modelo de projecto envolveu aprendizagens ativas, através da aplicação prática de conceitos de
programação, automação e web scraping, no âmbito da UF10806 - Linguagens de scripting e 
linha de comandos, lecionada pelo Prof.Dr. Joaquim Patriarca. Teve como objetivo capacitar o formando 
para apresentar soluções a problemas reais.
A resolução de problemas reais permitiu consolidar conhecimentos e desenvolver competências técnicas
de forma autónoma. O processo contribuiu para uma melhor compreensão das ferramentas utilizadas e da
sua aplicação em contextos reais.
Como perspetiva futura, o sistema poderá ser melhorado com a integração de bases de dados e análise
mais avançada dos dados recolhidos, a dar resposta para as necessidades do mercado de trabalho, para a prestação de
serviços eficiente.


