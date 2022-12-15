## investment_analysis
  Status do projeto (em andamento)

## Objetivo

O objetivo desse projeto é analisar a importância da constância em investimentos. Para isso, observei o desempenho de quatro ETFs, abrangendo o mercado americano, mercados emergentes (inclui o Brasil) e mercados desenvolvidos fora dos EUA.

ETF é uma sigla que na língua inglesa significa Exchange Traded Funds, traduzindo, Fundos de Índices. É um tipo de fundo de investimento, que tem taxa de administração baixa e é negociado na bolsa de valores.

Sobre as ETFs escolhidas:

* IVV: replica o S&P 500, principal índice da Nasdaq, que é a bolsa onde estão as 500 maiores empresas de tecnologia dos EUA, como por exemplo o Google, Facebook, Microsoft, Apple, Disney, Netflix, Visa e tantas outras.

* SLYV: acompanha o índice S&P 600, small cap no mercado americano. Tendo como destaque as empresas do setor financeiro, indústrias e consumos cíclicos que correspondem a aproximadamente 60% do portfólio do fundo. Tendo também exposição aos setores de TI, imobiliário, energia, assistência médica, entre outros.

* VEA: rastreia um índice ponderado por capitalização de mercado de ações de grande, média e pequena capitalização de mercados desenvolvidos fora dos EUA.

* VWO:  exposição nos mercados emergentes, entre eles Brasil, China e Índia.
  
## Técnicas
  - Extração
  - Limpeza e processamento
  - Visualização
  - Exportação
  - Automação 
  - Dashboard
    
## Ferramentas 
  * SQL
    * MySQL
  * Tableau
  * Jupyter
  * Python
      * datetime
      * dotenv
      * email
      * logging
      * matplotlib
      * numpy
      * os
      * pandas
      * pandas_datareader
      * plotly.express
      * plotly.graph_objects
      * pretty_html_table
      * pymysql
      * seaborn
      * sklearn.preprocessing
      * smtplib
      * sqlalchemy
    
## Etapas
  - Extração pelo Yahoo Finance, importando as colunas já com o ticker do ativo.
  - Unificação dos dados em um único data frame.
  - Normalização com MinMaxScaler na coluna Adj_Close para utilizar os dados no gráfico.
  - Geração de gráficos com Python com a finalidade de ter uma primeira visualização dos dados.
  - Exportação para o banco de dados do MySQL.
  - Envio automatizado de e-mails.
  - Geração de arquivo de log.
  - Construção de dashboard no Tableau com filtros interativos


![image](https://user-images.githubusercontent.com/112282677/207751381-334c5090-fb3c-4ab0-b4bb-9d9fe55fb846.png)

![image](https://user-images.githubusercontent.com/112282677/207751455-b9bec284-965a-405a-9109-3096d3f776d3.png)

![image](https://user-images.githubusercontent.com/112282677/207751522-0517081c-772d-46cf-93da-600a19acfc49.png)

![image](https://user-images.githubusercontent.com/112282677/207751581-264b4675-d045-45b8-b199-fcaa4c289e0d.png)

![image](https://user-images.githubusercontent.com/112282677/207751636-4a02355e-e6d2-44b4-8673-83a4a6378da4.png)


## Conclusão

Os gráficos, com os dados desta amostra de mercado, sugerem que quem foca no longo prazo e tem constância obtém ótimos resultados. O investidor que conseguiu ter “sangue frio” e manteve seus investimentos de longo prazo durante a pandemia, em 2022 já recuperou as perdas de 2020 e teve aumento de capital.
  
## Tableau

[Link para Public Tableau] (https://public.tableau.com/app/profile/lena.grumbach/viz/investment_analysis_dashboard/IVV?publish=yes)



![image](https://user-images.githubusercontent.com/112282677/207752469-9e232ba1-d78d-4614-aaa1-e7d31cd019bd.png)

![image](https://user-images.githubusercontent.com/112282677/207752683-48736ea6-276a-4a12-baab-5816d28baba1.png)

![image](https://user-images.githubusercontent.com/112282677/207752876-98fbdb63-0c64-4d63-a84d-b66707d10dc2.png)

![image](https://user-images.githubusercontent.com/112282677/207752952-681da14a-bd3c-475e-900c-1f2581eba094.png)



📫 Se você tiver algum comentário ou sugestão, por favor me avise!
    
    https://www.linkedin.com/in/lenagrumbach/
    
    lenagrumbach@gmail.com
