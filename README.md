# 📊 Análise de Dados de Crédito – SQL & Python

## 🧠 Introdução
Este projeto realiza uma **análise exploratória de dados de crédito** de clientes de um banco, com o objetivo de compreender o perfil dos clientes e os fatores que influenciam seus **limites de crédito**.  
Foram utilizados **AWS Athena (SQL)** para consultas e **Python (Pandas e Matplotlib)** para visualização e exploração dos dados.

---

## 🗂️ Sobre os Dados
O conjunto de dados contém informações sobre clientes, incluindo:
- Idade, sexo e estado civil  
- Nível de escolaridade e faixa salarial  
- Tipo de cartão e limite de crédito  
- Quantidade e valor de transações nos últimos 12 meses  

Os dados originais foram disponibilizados em:  
🔗 [EBAC Course Utils – Dataset](https://github.com/andre-marcos-perez/ebac-course-utils/tree/main/dataset)

---

## ⚙️ Etapas da Análise
1. **Exploração inicial dos dados** com SQL (`SELECT`, `COUNT`, `DISTINCT`)  
2. **Tratamento de valores ausentes** (substituição de `'na'` por “Não informado”)  
3. **Criação de tabela limpa no Athena**  
4. **Consultas analíticas** sobre renda, gênero, escolaridade e limite de crédito  
5. **Visualizações com Python** para identificar padrões e correlações  

---

## 📈 Principais Insights
- A maioria dos clientes possui **renda acima de 40K**.  
- **Homens com renda superior a 80K** têm os maiores limites de crédito.  
- **Escolaridade** influencia pouco o limite.  
- **Idade entre 40 e 50 anos** está associada aos maiores limites.  
- **Solteiros e divorciados** movimentam mais dinheiro que casados.  

---

## 🧰 Tecnologias Utilizadas
- **SQL (AWS Athena)**
- **Amazon S3**
- **Python 3 (Pandas, Matplotlib)**
- **Jupyter Notebook**




