# 📊 Análise Exploratória de índice de Desenvolvimento Humano (IDH) por País e Continente  
### 🧠 Exploratory Data Analysis of Human Development Index (HDI) by Country and Continent  

---

## ⚠️ Aviso Importante / Important Notice

Os dados utilizados neste projeto são **fictícios** e foram criados apenas para fins educacionais e de prática em análise de dados.  
The data used in this project are **fictional**, created solely for educational and practice purposes.

---

## 🇧🇷 **Descrição do Projeto**

Este projeto realiza uma **análise exploratória de dados (EDA)** com foco em indicadores de **desenvolvimento humano (IDH)**, **PIB per capita** e **anos médios de escolaridade** por país.  
O objetivo é compreender **padrões de desenvolvimento entre continentes**, explorando relações entre variáveis econômicas e sociais.  

A análise foi desenvolvida em **Python** utilizando o **Jupyter Notebook**, com base em dados organizados em uma planilha Excel contendo duas abas:  
- 📄 *“País - Desenvolvimento”*  
- 📄 *“País - Continente”*

---

## 🌍 **Project Description (English)**

This project performs an **Exploratory Data Analysis (EDA)** focused on **Human Development Index (HDI)**, **GDP per capita**, and **average years of schooling** by country.  
The main goal is to identify **patterns of human development among continents**, exploring relationships between economic and social variables.  

The analysis was built in **Python** using **Jupyter Notebook**, based on an Excel file with two sheets:  
- 📄 *“Country - Development”*  
- 📄 *“Country - Continent”*

---

## ⚙️ **Etapas do Projeto / Project Steps**

### 1. Importação dos Dados / Data Import  
- Leitura de múltiplas abas do Excel com `pandas.read_excel()`.  
- Verificação de existência e estrutura dos arquivos.

### 2. Limpeza e Padronização / Cleaning and Standardization  
- Conversão de texto para minúsculas.  
- Remoção de pontos e espaços extras.  
- Padronização dos nomes dos países.  

### 3. Tratamento de Dados Ausentes / Missing Data Handling  
- Verificação com `isna()` e `info()`.

### 4. Análises Estatísticas / Statistical Analysis  
- Cálculo do **IDH médio global**.  
- Média do **IDH por continente**.  
- Contagem de **número de países por continente**.  
- Identificação e percentual de países **acima da média global de IDH**.

### 5. Visualizações / Visualizations  
- Gráfico de dispersão: **PIB per capita × IDH**.  
- Gráfico de dispersão: **Anos de escolaridade × IDH**.  
- Gráfico de barras: **Média do IDH por continente**.  
- Gráfico de barras: **Percentual de países acima da média global**.

---

## 📈 **Principais Insights / Key Insights**

🇧🇷  
- Existe uma **forte relação positiva** entre o PIB per capita e o IDH.  
- O nível de escolaridade também está fortemente associado ao desenvolvimento humano.  
- Continentes com maior média de IDH concentram maior número de países acima da média global.  

🌎  
- There is a **strong positive correlation** between GDP per capita and HDI.  
- Education levels show a consistent influence on human development.  
- Continents with higher average HDI also have more countries above the global average.

---

## 🧰 **Tecnologias Utilizadas / Technologies Used**
- Python 🐍  
- Pandas 📊  
- Matplotlib 📈  
- Jupyter Notebook 📘  
- Excel 📑  

---

## 👩‍💻 **Autora / Author**
**Joy Carvalho**  
Projeto desenvolvido como prática de análise de dados.  
*Project developed for data analysis practice.*
---
