# Trade

Explicação dos Ajustes
Inserção de Tickers com Sufixo .SA:

Adicionei .SA aos tickers ao inseri-los no banco de dados para garantir que sejam reconhecidos pelo Yahoo Finance.

Consulta dos Tickers do Banco de Dados:

A função get_tickers_from_database recupera os tickers do banco de dados, que agora incluem o sufixo .SA.

Filtragem de Ações com Preço Acima da SMA21:

A função filter_stocks_above_sma21 usa os tickers recuperados com o sufixo .SA para buscar dados no Yahoo Finance e filtrar as ações.

Ao executar este código, os tickers serão inseridos no banco de dados com o sufixo .SA e a filtragem para ações com preço acima da SMA21 será realizada corretamente.
