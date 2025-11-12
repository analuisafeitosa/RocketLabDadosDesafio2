#RocketLab Dados - Desafio 2

Este repositório contém a resolução do **Desafio 2** do programa **RocketLab Dados**.  
O processo foi dividido em duas principais etapas: **LAND → BRONZE** e **BRONZE → SILVER**, seguindo a arquitetura de camadas de dados.

---

##Etapa 1 — LAND → BRONZE

1. Realizei o **download do dataset** no kaggle.  
2. Criei os **databases** necessários no ambiente de trabalho.  
3. Configurei um **volume** para consumir os dados brutos.  
4. Criei as **tabelas da camada Bronze**, armazenando os dados exatamente como estavam na origem (sem transformações).

---

##Etapa 2 — BRONZE → SILVER

1. Para cada tabela da camada Bronze, realizei o **tratamento e limpeza dos dados**, conforme os **requisitos definidos no desafio**.  
2. As transformações incluíram:
   - Correção de tipos de dados;
   - Padronização de colunas;
   - Tratamento de valores nulos e inconsistentes;
   - Criação de novas colunas derivadas (quando aplicável).  
3. Após o tratamento, os dados foram **carregados na camada Silver**, prontos para análise e modelagem.

