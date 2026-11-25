<div align="center">

# Vítor Barra

**Cientista de Dados** · Físico, mestre pela UFJF · Juiz de Fora, MG

_Faço a pergunta, monto o pipeline e desconfio do resultado antes de acreditar nele._

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vitorbarra/)
[![E-mail](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vifebarra@outlook.com)
[![Gravidade Social](https://img.shields.io/badge/Projeto_em_destaque-Gravidade_Social-414A6C?style=for-the-badge&logo=jupyter&logoColor=white)](https://github.com/Kotige/gravidade-social-enem)

</div>

---

## Sobre mim

Sou cientista de dados em início de carreira, com formação em Física e mestrado pela UFJF. Na pesquisa, passei anos usando programação pra resolver problemas que não tinham solução analítica — e aprendi que boa parte do trabalho é decidir quais simplificações fazem sentido e até onde um modelo merece confiança. Em dados é exatamente a mesma coisa.

Hoje também dou aula de Física na rede estadual de Minas Gerais, e é de lá que vem boa parte das perguntas que me interessam: desempenho, desigualdade, o que um número mostra e o que ele esconde.

Gosto do ciclo inteiro: coletar e limpar os dados, modelar em SQL, analisar, testar hipóteses e transformar o resultado numa história ou numa ferramenta que outra pessoa consiga usar. Do desenvolvimento web eu trago o lado da entrega — interface, deploy e a preocupação de comunicar bem pra quem não vai abrir o notebook.

---

## Projeto em destaque

### [Gravidade Social](https://github.com/Kotige/gravidade-social-enem) — o peso da origem na nota de Ciências da Natureza do ENEM em Minas Gerais

Depois do ENEM 2026, ouvi de muitos alunos que a prova de Ciências da Natureza foi difícil. A pergunta que ficou foi outra: **quanto da nota de um estudante mineiro é explicado pela origem dele** — renda, escolaridade dos pais, rede de ensino e município — e em quais conteúdos essa diferença é maior?

O projeto usa os microdados do INEP de 2020 a 2025, filtrados para Minas Gerais, e está em desenvolvimento.

**O que já está construído:**

- Pipeline reprodutível: ingestão em Python para Parquet e um banco DuckDB montado em camadas SQL (staging, analítica e agregada)
- Harmonização de cerca de 80 variáveis ao longo de seis edições do exame
- 12 testes de dados rodando a cada build, incluindo reconciliação com números conferidos à mão — e os próprios testes foram validados corrompendo os dados de propósito pra ver se eles falhavam
- 8 decisões metodológicas documentadas, incluindo os problemas que os dados trouxeram: a partir de 2024 o INEP separou as tabelas sem chave em comum, a identificação das escolas mudou entre 2023 e 2024, escolas pequenas têm código mascarado e há cartões em branco com nota zero

**Perguntas que o projeto responde:**

| #     | Pergunta                                                                        |
| ----- | ------------------------------------------------------------------------------- |
| Q1    | Como a nota varia por rede de ensino, renda per capita e escolaridade dos pais? |
| Q2    | Como os resultados se distribuem entre os municípios de Minas?                  |
| Q3    | O que mais pesa na nota?                                                        |
| Q4    | Quem deixa de fazer a prova?                                                    |
| Q5–Q6 | Análise por item das questões de Ciências da Natureza e TRI                     |

**Status:** dados e modelagem SQL concluídos · análise exploratória em andamento · modelagem estatística, TRI, app interativo e relatório final planejados.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logoColor=white)
![Parquet](https://img.shields.io/badge/Parquet-50ABF1?style=flat-square&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-0F172A?style=flat-square&logo=tailwindcss&logoColor=38BDF8)

---

## Outros projetos de dados

**[titanic-eda](https://github.com/Kotige/titanic-eda)** — Estatística descritiva e inferencial com dados reais: distribuições, outliers, viés amostral e um intervalo de confiança de 95% para a idade média dos passageiros. A parte que mais gostei foi testar um viés que parecia óbvio (sobrevivência por classe) e descobrir, nos próprios dados, que a leitura estava errada.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

**[pendulum-gravity-analyzer](https://github.com/Kotige/pendulum-gravity-analyzer)** — Script de linha de comando que analisa dados experimentais reais, coletados por alunos do ensino médio, para medir a aceleração da gravidade local com um pêndulo simples. Escrevi em Python puro, só com a biblioteca nativa `csv`, de propósito: queria entender a lógica de leitura, limpeza e cálculo sem depender de biblioteca pronta.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![CSV](https://img.shields.io/badge/csv-555555?style=flat-square)

---

## Desenvolvimento web

Sites feitos para clientes e para mim, do design ao deploy.

| Projeto                                                | Descrição                                                         |
| ------------------------------------------------------ | ----------------------------------------------------------------- |
| [log-narrado](https://github.com/Kotige/log-narrado)   | Meu blog de experiências pessoais, física, dados e hobbies        |
| [portfolio](https://github.com/Kotige/portfolio)       | Portfólio de Ciência de Dados em React + Tailwind (em construção) |
| [ninacamurca](https://github.com/Kotige/ninacamurca)   | Portfólio profissional de fotografia e cobertura de eventos       |
| [modv-estudio](https://github.com/Kotige/modv-estudio) | Site para empresa de Design Gráfico                               |

---

## Stack

**Dados**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logoColor=white)

**Web**

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-0F172A?style=flat-square&logo=tailwindcss&logoColor=38BDF8)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Ferramentas**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

**Próximos passos:** `scikit-learn` `statsmodels` `TRI`

---

## GitHub Stats

<div align="center">

[![GitHub stats](https://github-stats-extended.vercel.app/api?username=Kotige)](https://github.com/stats-organization/github-stats-extended)

</div>

---

## Formação & Atividade Atual

|                                                            | Instituição                                          | Status            |
| ---------------------------------------------------------- | ---------------------------------------------------- | ----------------- |
| **Bacharelado em Física** (ênfase em Física Computacional) | UFSJ — Universidade Federal de São João del-Rei      | Concluído (2016)  |
| **Licenciatura em Física**                                 | UFSJ — Universidade Federal de São João del-Rei      | Concluído (2017)  |
| **Mestrado em Física**                                     | UFJF — Universidade Federal de Juiz de Fora          | Concluído (2020)  |
| **Professor de Física**                                    | IEE — Instituto Estadual de Educação de Juiz de Fora | Atual, desde 2023 |

---

## Vamos conversar

Estou aberto a oportunidades como **cientista ou analista de dados júnior** e a trocar ideia com quem trabalha com dados educacionais, estatística aplicada ou dados públicos. Feedback no Gravidade Social também é muito bem-vindo.

<div align="center">

[![Fale comigo no LinkedIn](https://img.shields.io/badge/Fale_comigo_no_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vitorbarra/)

_Se tem uma coisa que a Física me ensinou é desconfiar de resultado bonito demais._

</div>
