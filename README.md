<h1 align="center">Olá, e seja Bem-vindo! 🤖 </h1>

<p align="center">
  Estudante de Banco de Dados focado em Análise e Engenharia de Dados
</p>

<p align="center">
  <a href="https://linkedin.com/in/thiago-costa-dados"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:thcosta.dados@outlook.com"><img src="https://img.shields.io/badge/E--mail-0078D4?style=for-the-badge&logo=maildotru&logoColor=white"/></a>
</p>

---

## Sobre mim

📊 Estudante de Tecnologia em Banco de Dados no Mackenzie  
🏪 Empreendedor desde 2021, sempre tomando decisões com base em números (margem, estoque, compras)  
🛠️ Hoje construo pipelines de dados com Python, SQL e PostgreSQL  
🎯 Buscando meu primeiro estágio em Dados, BI ou Analytics  
📍 Rio de Janeiro, RJ

---

## Tecnologias

### Linguagens
<table>
  <tr>
    <td align="center" width="96">
      <a href="https://www.python.org/"><img src="images/python.svg" width="56" height="56" alt="Python"/></a>
      <br>Python
    </td>
    <td align="center" width="96">
      <a href="https://www.postgresql.org/docs/current/sql.html"><img src="images/sql.svg" width="56" height="56" alt="SQL"/></a>
      <br>SQL
    </td>
  </tr>
</table>

### Bibliotecas
<table>
  <tr>
    <td align="center" width="96">
      <a href="https://pandas.pydata.org/"><img src="images/pandas.svg" width="56" height="56" alt="Pandas"/></a>
      <br>Pandas
    </td>
    <td align="center" width="96">
      <a href="https://numpy.org/"><img src="images/numpy.svg" width="56" height="56" alt="NumPy"/></a>
      <br>NumPy
    </td>
    <td align="center" width="96">
      <a href="https://docs.pytest.org/"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.16.0/icons/pytest/pytest-original.svg" width="56" height="56" alt="pytest"/></a>
      <br>pytest
    </td>
  </tr>
</table>

### Bancos de dados
<table>
  <tr>
    <td align="center" width="96">
      <a href="https://www.postgresql.org/"><img src="images/postgresql.svg" width="56" height="56" alt="PostgreSQL"/></a>
      <br>PostgreSQL
    </td>
    <td align="center" width="96">
      <a href="https://www.mysql.com/"><img src="images/mysql.svg" width="56" height="56" alt="MySQL"/></a>
      <br>MySQL
    </td>
  </tr>
</table>

### BI e Ferramentas
<table>
  <tr>
    <td align="center" width="96">
      <a href="https://www.microsoft.com/power-platform/products/power-bi"><img src="images/powerbi.svg" width="56" height="56" alt="Power BI"/></a>
      <br>Power BI
    </td>
    <td align="center" width="96">
      <a href="https://www.microsoft.com/microsoft-365/excel"><img src="images/excel.svg" width="56" height="56" alt="Excel"/></a>
      <br>Excel
    </td>
    <td align="center" width="96">
      <a href="https://git-scm.com/"><img src="images/git.svg" width="56" height="56" alt="Git"/></a>
      <br>Git
    </td>
    <td align="center" width="96">
      <a href="https://github.com/features/actions"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.16.0/icons/githubactions/githubactions-original.svg" width="56" height="56" alt="GitHub Actions"/></a>
      <br>GitHub Actions
    </td>
    <td align="center" width="96">
      <a href="https://www.docker.com/"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.16.0/icons/docker/docker-original.svg" width="56" height="56" alt="Docker"/></a>
      <br>Docker
    </td>
  </tr>
</table>

---

## Projetos em destaque

### [steam-cost-per-hour](https://github.com/thcosta-dados/steam-cost-per-hour)
Quanto me custou cada hora jogada na Steam? Um estudo de caso com os dados da minha própria conta.

- Coleta diária em Python no GitHub Actions desde 23/10/2026, gravando no PostgreSQL (Supabase). O histórico de compras vem de uma página HTML salva, lida com BeautifulSoup
- 34 regras de negócio na especificação, calculadas em views SQL, e painel no Power BI (projeto PBIP) com 5 páginas, drillthrough e medidas DAX
- 83 testes com pytest a cada push, contra um PostgreSQL em container, e 32 consultas SQL que reconciliam cada fato do painel. Os principais números foram conferidos com as páginas da própria Steam
- O SteamID só entra no banco como HMAC-SHA256, e o Row Level Security fecha a API pública do Supabase
- Em 13/11/2026, Rainbow Six Siege saiu a R$ 0,16 por hora, e uma hora de Phasmophobia custou o mesmo que 163 horas de Rainbow Six

### [Duthi E-commerce Analytics](https://github.com/thcosta-dados/duthi-ecommerce-analytics)
Análise de ponta a ponta com dados reais de um e-commerce de semijoias (200 pedidos, jul/2024 a set/2025).

- ETL em Python (Pandas) com validação de chaves e anonimização SHA-256
- Modelo em PostgreSQL com tabela fato, 9 views e 19 queries (CTEs, window functions, cohort de retenção)
- Dashboard em Power BI
- Principal achado: 93% dos clientes compraram uma única vez, o que direcionou a recomendação de foco em recompra

---

## Certificações

- SQL, FGV
- Python for Data Science, AI & Development, IBM (nota 98,5%)
- Data Analytics Essentials, IBM
- Excel Basics for Data Analysis, IBM
- Fundamentos de Engenharia de Dados, DSA
