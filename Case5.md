# Resposta Case 5 

`SELECT * FROM users_emails` *a função `SELECT` irá selecionar todas as colunas da tabela users_emails e o `FROM` seleciona a tabela que queremos*

`WHERE` *a função `WHERE` filtra os resultados que declaramos a partir da condição que definimos*

`data_cadastro >= DATE_SUB(CURRENT_DATE(), INTERVAL 30 DAY);` *É a coluna na tabela "users_emails" que armazena a data de cadastro.*

`DATE_SUB(CURRENT_DATE(), INTERVAL 30 DAY):` *Essa parte calcula a data atual menos 30 dias.*
    *`CURRENT_DATE()` retorna a data atual, e `DATE_SUB()` subtrai um intervalo de tempo (30 dias, neste caso) dessa data atual, resultando na data limite dos últimos 30 dias.*
