# Modelando um Dashboard de E-commerce com Power BI utilizando fórmulas DAX

## Objetivo do desafio

Remodelar a tabela Financial Sample original (Financial Sample.xlsx) para um Star Schema.

## Estrutura do Projeto

A partir da cópia da tabela original, serão selecionadas as colunas que irão compor a visão da nova tabela.

**Financials_origem** (modo oculto – backup)

Serão criadas as tabelas:  

**F_Vendas** (SK_ID , ID_Produto, Produto, Units Sold, Sales Price, Discount  Band, Segment, Country, Salers, Profit, Date (campos)) 

**D_Produtos** (ID_produto, Produto, Média de Unidades Vendidas, Médias do valor de vendas, Mediana do valor de vendas, Valor máximo de Venda, Valor mínimo de Venda)

**D_Descontos** (ID_produto, Discount, Discount Band) 

**D_Detalhes** (*) 

**D_Calendário** – Criada por DAX com calendar() 

![image](https://github.com/user-attachments/assets/b9a0ae2f-fcbf-4708-bcd5-c79259cfc3ca)

Interface gráfica do usuário, Aplicativo

Descrição gerada automaticamente com confiança médiaD_Produtos_Detalhes(ID_produtos, Discount Band, Sale Price,  Units Sold, Manufactoring Price) 









