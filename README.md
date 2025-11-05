# 🧠 Análise Descritiva de Vendas — Projeto em Python

Este projeto foi desenvolvido durante o curso de **Python para Data Science** do **SENAI**, com o objetivo de aplicar os principais conceitos de **análise descritiva de dados** utilizando **Python** no **Google Colab**.  
A análise foi feita a partir de **planilhas de vendas e gerentes**, aplicando técnicas de exploração, limpeza e consolidação de dados com a biblioteca **Pandas**.

---

## 📊 Objetivo do Projeto

O objetivo principal foi realizar uma **análise descritiva de vendas**, integrando diferentes planilhas e explorando indicadores de desempenho.  
Foram verificadas inconsistências, duplicidades, valores ausentes e realizadas análises para compreender o comportamento das vendas mensais.

---

## 🚀 Tecnologias Utilizadas

- **Python 3**
- **Google Colab**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Excel (como fonte de dados)**

---

## 🧩 Etapas do Desenvolvimento

1. **Importação dos dados**  
   Leitura de múltiplos arquivos Excel (`Vendas.xlsx`, `Vendas - Dez.xlsx`, `Gerentes.xlsx`).

2. **Exploração inicial**  
   Utilização dos métodos `head()`, `info()`, `describe()` e `isna()` para entender o conjunto de dados.

3. **Limpeza e tratamento**  
   - Remoção de linhas duplicadas (`drop_duplicates()`);  
   - Verificação e tratamento de valores nulos;  
   - Padronização dos nomes de colunas.

4. **Análise descritiva**  
   - Estatísticas básicas (média, mediana, soma de vendas);  
   - Comparação entre meses;  
   - Cruzamento entre vendas e gerentes.

5. **Visualização de dados** *(se aplicável)*  
   Criação de gráficos simples com **Matplotlib** e **Seaborn** para destacar padrões.

6. **Conclusões**  
   Identificação de pontos fortes, possíveis falhas e oportunidades de melhoria nos dados de vendas.

---

## 💡 Principais Aprendizados

Durante o desenvolvimento deste projeto, pude:
- Consolidar o uso de **Pandas para leitura e tratamento de dados reais**.  
- Realizar **integração de múltiplos arquivos Excel** em um único DataFrame.  
- Aplicar **análise exploratória e descritiva** com foco em negócios.  
- Desenvolver boas práticas de **organização e limpeza de dados**.  
