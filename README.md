# 📊 Projeto de Análise de Dados – BMW

Este projeto apresenta uma análise completa de dados da BMW utilizando **Power BI**, com foco em indicadores de vendas, comportamento do cliente e desempenho por região, modelo e cor.

---

## 🧱 Estrutura do Projeto

**1. Visão Geral**
- Total de Vendas: US$ 3,75 bilhões  
- Receita Total: US$ 19,01 trilhões  
- Nº de Clientes: 50 mil  
- Melhor ano: **2022**, com receita de US$ 1,34 tri

**2. Produto / Cliente**
- Cores preferidas: vermelho, branco e prata  
- Tipos de motor com melhor desempenho: 3.8L, 2.5L, 4.5L, 1.9L e 2.6L  
- Combustíveis mais usados: híbrido e petróleo  
- Transmissão: manual (50,31%) e automática (49,69%)

**3. Região**
- Melhor desempenho: **Ásia**  
- Melhor preço médio: **América do Sul**  
- Menor desempenho: **África (receita e vendas)**  

**4. Ranking**
- Top 5 Modelos: 7 Series, 3 Series, i8, 5 Series, i3  
- Top 3 Regiões: Ásia, América do Norte, Oriente Médio  
- Top 3 Cores: Vermelho, Branco, Prata  

---

## 🧮 Medidas DAX principais

**DAX**

QTD Vendas = SUM(Fato[Sales_volume])
Total Vendas = SUM(Fato[Price_USD])
Receita Total = SUMX(Fato, Fato[Sales_volume] * Fato[Price_USD])

## 🧠 Insights

- Oscilações significativas de desempenho entre anos.

- Maior estabilidade na Ásia.

- Preferência por motores intermediários e cores vibrantes.

- Potencial de crescimento em veículos híbridos e elétricos.

 ## 🛠️ Ferramentas utilizadas

- Power BI Desktop

- DAX

- CSV / Kaggle Dataset 
