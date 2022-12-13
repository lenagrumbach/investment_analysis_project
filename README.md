## investment_analysis
  Status do projeto (em andamento)

## Objetivo
  Projeto final do bootcamp [ elaborar e dar contexto para o projeto || Explicar o que são ETFs e o motivo de ter escolhido estas ]
  
## Técnicas
  - Extração
  - Limpeza e Processamento
  - Visualização
  - Exportação
  - Dashboard [ em construção ]
    
## Ferramentas 
  * SQL
    * MySQL
  * Tableau
  * Python
    * Jupyter
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
    
    
- No site https://research.stlouisfed.org/ pesquisei e identifiquei os dados que pudessem me ajudar a descobrir os índices cuja variação tem maior correlação com o índice dos preços dos imóveis nos Estados Unidos.
 - Filtrei os dados do S&P 500 para converter informações diárias em mensais e poder comparar com os índices que tem informação mensal. Fiz o mesmo processo com a taxa de juros.
 - Juntei todas as informações em um único dataframe.
 - Usei MinMaxScaler para normalizar os valores que foram utilizados nos gráficos.
 - Exportei os dados para o banco de dados no MySQL.
 - Fiz envio automático de e-mail com informações diárias.
 - Gerei arquivo de log.
    
    
## Etapas
  - Extração pelo Yahoo Finance, importando as colunas já com o ticker do ativo.
  - Uso de merge para ter todos os dados em um único data frame.
  - Normalização com MinMaxScaler dos dados da coluna Adj_Close para serem utilizados nos gráficos.
  - Geração de gráficos para ter uma primeira visualização dos dados.
  - Exportação para o banco de dados do MySQL.
  - Envio automatizado de e-mails.
  - Geração de arquivo de log.
  - [ To do: Dashboard no Tableau ]

![image](https://user-images.githubusercontent.com/112282677/207214022-a01f89b2-e58c-4e75-8080-71cc0910db25.png)

![image](https://user-images.githubusercontent.com/112282677/207213492-f8dc0b7d-88be-4497-91a8-30b063a0d9c4.png)

![image](https://user-images.githubusercontent.com/112282677/207213580-4acd3665-0449-41b2-994c-3c91555d5f55.png)

![image](https://user-images.githubusercontent.com/112282677/207213773-806ebcaf-d79a-4b48-a013-c19332d8ce9c.png)

![image](https://user-images.githubusercontent.com/112282677/207213839-de793c36-2b5d-4a20-9ef6-fb2f09264caf.png)


## Conclusões
  [ elaborar ]
  

📫 Se você tiver algum comentário ou sugestão, por favor me avise!
    
    https://www.linkedin.com/in/lenagrumbach/
    
    lenagrumbach@gmail.com
