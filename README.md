## investment_analysis
  Status do projeto (finalizado)
 
## Objetivo

O objetivo desse projeto é analisar os efeitos de uma estratégia de investimento com visão de longo prazo. Para isso, observei o desempenho de quatro ETFs, abrangendo o mercado americano, mercados emergentes (inclui o Brasil) e mercados desenvolvidos fora dos EUA.

ETF é uma sigla que na língua inglesa significa Exchange Traded Funds, traduzindo, Fundos de Índices. É um tipo de fundo de investimento, que tem taxa de administração baixa e é negociado na bolsa de valores.

Sobre as ETFs escolhidas:

* IVV: replica o S&P 500, que é considerado o principal indicador de ações de companhias de grande porte dos Estados Unidos. Reúne cerca de 500 empresas de capital aberto domiciliadas no país, listadas na Bolsa de Valores de Nova York (NYSE, na sigla em inglês) e na Nasdaq.

* SLYV: acompanha o índice S&P 600, small cap no mercado americano. Tendo como destaque as empresas do setor financeiro, indústrias e consumos cíclicos, que correspondem a aproximadamente 60% do portfólio do fundo. Tendo também exposição aos setores imobiliário, tecnologia, energia, assistência médica, entre outros.

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

📊 Gráficos - Python

* Gráfico com as quatro ETFs juntas, com informações desde 2008. Aqui podemos ver que em 2022, três ETFs já recuperaram  as perdas de 2020 com ampla vantagem. Apenas a ETF de mercados emergentes não teve um desempenho tão bom, recuperou a perda mas não teve ganho expressivo.

![image](https://user-images.githubusercontent.com/112282677/207751381-334c5090-fb3c-4ab0-b4bb-9d9fe55fb846.png)

* O gráfico Bollinger Band é uma ferramenta de análise técnica desenvolvida por John Bollinger. É um indicador de volatilidade, formado por duas médias móveis, uma superior e outra inferior, que indicam se um ativo mostra sinais de estar sobre-vendido ou sobre-comprado. Quando o preço do ativo ultrapassa a banda superior, observamos uma tendência de alta do ativo. Por outro lado, se o preço fica abaixo da banda inferior, há então uma tendência de baixa. Pode ser usado em uma análise combinada com o gráfico de candles. 

* Nesse projeto, o uso desse tipo de gráfico se justifica na análise exploratória dos dados para verificar se a escolha da amostra de ativos está adequada.

![image](https://user-images.githubusercontent.com/112282677/207751455-b9bec284-965a-405a-9109-3096d3f776d3.png)

![image](https://user-images.githubusercontent.com/112282677/207751522-0517081c-772d-46cf-93da-600a19acfc49.png)

![image](https://user-images.githubusercontent.com/112282677/207751581-264b4675-d045-45b8-b199-fcaa4c289e0d.png)

![image](https://user-images.githubusercontent.com/112282677/207751636-4a02355e-e6d2-44b4-8673-83a4a6378da4.png)


## Conclusão

Baseado na amostra de mercado, que abrangeu EUA, mercados desenvolvidos fora dos EUA e mercados emergentes, podemos concluir que o investidor que tem foco no longo prazo e tem constância, obtém ótimos resultados. O investidor que conseguiu ter “sangue frio” e manteve seus investimentos de longo prazo durante a pandemia, já em 2022 recuperou as perdas de 2020 e obteve aumento de capital.
  
## Tableau

[Link para Public Tableau] (https://public.tableau.com/app/profile/lena.grumbach/viz/investment_analysis_dashboard/IVV?publish=yes)

.

![image](https://github.com/lenagrumbach/investment_analysis_project/blob/main/ezgif.com-gif-maker.gif)

. 



📫 Se você tiver algum comentário ou sugestão, por favor me avise!
    
    https://www.linkedin.com/in/lenagrumbach/
    
    lenagrumbach@gmail.com
