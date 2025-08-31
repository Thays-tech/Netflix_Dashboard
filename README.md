# 📊 Painel de Consumo Netflix  

Este projeto apresenta um **dashboard interativo em Power BI** que analisa o consumo de filmes e séries na plataforma Netflix entre **2020 e 2022**, cruzando informações de **visualizações** com dados de **temperatura média** (INMET – Curitiba) e **feriados nacionais**.  

O objetivo é demonstrar como a análise de dados pode gerar **insights comportamentais**, respondendo perguntas como:  
- Em quais dias da semana o usuário assiste mais filmes ou séries?  
- Qual a probabilidade de assistir algo em um feriado?  
- Como a temperatura influencia nos hábitos de consumo?  
- Quais são as séries mais assistidas e em quanto tempo foram concluídas?  

---

## 🚀 Funcionalidades principais  

- 📅 **Análise temporal**: consumo por ano, mês e dia da semana.  
- 🍿 **Distribuição por tipo de conteúdo**: filmes vs séries.  
- 🎬 **Séries mais assistidas** e quantidade de episódios por título.  
- 🕒 **Tempo total de visualização por série** (do início ao fim).  
- 🌡️ **Cruzamento com dados meteorológicos**: clima predominante e temperatura média nos dias de visualização.  
- 🎉 **Impacto de feriados**: probabilidade de assistir em dias de feriado.  
- 📊 **Filtros interativos** para explorar padrões de forma dinâmica.  

---

## 📂 Estrutura sugerida do repositório  

```plaintext
netflix-dashboard/
│
├── dashboard/
│   └── netflix.pbix     # Arquivo principal do Power BI
│
├── data/
│   ├── netflix/                   # Histórico de visualizações Netflix
│   │   └── NetflixViewingHistory.csv
│   │
│   ├── clima/                     # Temperatura média (INMET - Curitiba)
│   │   ├── INMET_S_PR_A807_CURITIBA_2020.csv
│   │   ├── INMET_S_PR_A807_CURITIBA_2021.csv
│   │   └── INMET_S_PR_A807_CURITIBA_2022.csv
│   │
│   ├── feriados/                  # Dataset de feriados (GitHub público)
│   │   ├── 2020.csv
│   │   ├── 2021.csv
│   │   └── 2022.csv
│
└── images/

> ⚠️ Observação: os arquivos de dados aqui são **amostras** extraídas de datasets públicos (não são bases massivas completas).  

---

## 📸 Exemplos de uso  

### Visão geral do painel:
![Dashboard Netflix](images/dashboard_overview.png)  

**Insights disponíveis:**  
- Total de títulos assistidos.  
- Dia da semana com maior consumo de filmes e séries.  
- Clima predominante no período de visualização.  
- Tempo acumulado para concluir cada série.  

---

## 🤝 Contribuição  

Contribuições são bem-vindas! Algumas boas práticas:  
- Abra uma *issue* para relatar bugs ou sugerir melhorias.  
- Crie *pull requests* bem documentados.  
- Inclua testes ou prints que comprovem a melhoria no dashboard.  

---

## 📚 Referências e créditos  

- 📌 **Netflix Viewing History**: dados exportados do histórico pessoal (2020–2022).  
- 📌 **Temperatura média Curitiba (2020–2022)**: [INMET – Instituto Nacional de Meteorologia](https://bdmep.inmet.gov.br/).  
- 📌 **Feriados nacionais**: dataset público disponível no GitHub (arquivos CSV por ano).  

👩‍💻 **Autor:** Thays P. Silveira  
✨ Agradecimentos especiais às comunidades de **Power BI** e **Data Analytics** que inspiraram a construção deste painel.  
