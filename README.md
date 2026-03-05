# Sales Analytics Data Platform

Projeto de **Data Analytics e Business Intelligence** desenvolvido em Python para simular uma arquitetura moderna de análise de dados utilizada em empresas.

O projeto transforma dados brutos em **insights analíticos através de um pipeline completo de dados e um dashboard interativo**.

---

# 📊 Visão Geral

Este projeto demonstra como construir um fluxo de dados completo:

Data Source → ETL Pipeline → Data Warehouse → Machine Learning → Dashboard

O objetivo é automatizar a análise de vendas e permitir que gestores tomem decisões baseadas em dados.

---

# 🧠 Funcionalidades

✔ Extração automática de dados
✔ Transformação e limpeza com Python
✔ Armazenamento em Data Warehouse
✔ Treinamento de modelo de Machine Learning
✔ Dashboard interativo com visualizações analíticas

---

# 🛠 Tecnologias Utilizadas

Python
Pandas
SQLite
Scikit-learn
Streamlit
Plotly

---

# 📈 Dashboard

O dashboard permite visualizar:

* Total de vendas
* Performance por produto
* Tendência de vendas ao longo do tempo
* Distribuição de vendas
* Análise exploratória de dados

---

# ⚙️ Como executar o projeto

Clone o repositório:

git clone https://github.com/Paulobenicpv/Data-Analytics-e-Automa-o-de-BI-

Instale as dependências:

pip install -r requirements.txt

Execute o pipeline de dados:

python main.py

Inicie o dashboard:

streamlit run dashboard/app.py

---

# 📌 Possíveis melhorias

* integração com APIs de vendas
* uso de bancos de dados analíticos
* previsões de vendas mais avançadas
* deploy em nuvem

---

# 👨‍💻 Autor

Paulo Beni



# Arquitetura do projeto

            +---------------------+
            |     Data Source     |
            |      CSV / API      |
            +----------+----------+
                       |
                       v
            +---------------------+
            |     ETL Pipeline    |
            |    Python / Pandas  |
            +----------+----------+
                       |
                       v
            +---------------------+
            |    Data Warehouse   |
            |       SQLite        |
            +----------+----------+
                       |
                       v
            +---------------------+
            |   Machine Learning  |
            | Sales Forecast Model|
            +----------+----------+
                       |
                       v
            +---------------------+
            |      Dashboard      |
            |   Streamlit + Plotly|
            +---------------------+
