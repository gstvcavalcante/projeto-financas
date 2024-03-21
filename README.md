# projeto-financas

Esse projeto tem o objetivo de acompanhar meus gastos com o cartão de crédito, analisando minhas faturas anteriores e criando um dashboard no PowerBI.

Tercnologias utilizadas:
- Python, Jupyter Notebook - para analisar e tratar os dados.
- SQL, MySQL - construção do banco de dados com a tabela contendo as informações dos arquivos CSV das faturas que solicitei ao meu banco.
- PowerBI - criação do dashboard interativo com gráficos e tabelas para análise dos gastos.

Os notebooks contidos nesse repositório estão comentados, sendo possível acompanhar o passo a passo do raciocínio utilizado na construção do código e das análises.
Em resumo:
- O arquivo 'criar_tabela_dados' (Jupyter Notebook) faz a leitura das faturas de setembro/2023 até fevereiro/2024, gerando um dataframe com esses dados e insere em uma tabela no banco de dados do MySQL.
- O arquivo 'tratamento_dados_cartao' (Jupyter Notebook) é onde eu realizo a consulta no banco de dados e crio um novo dataframe com as informações da tabela de faturas. Depois, realizo limpeza, formatação e transformação de alguns dados, além de algumas análises iniciais para entender o perfil de gasto e planejar a construção do dashboard. Também criei uma nova tabela no banco de dados com as informações atualizadas.
- 'dashboard_gastos_cartao' é o arquivo do PowerBI com os gráficos e tabelas interativas que mostram meu gasto mensal, por categoria, e outras informações para acompanhamento dos gastos.

----------------------------------------------------------------------------------------------------------------------------------------------------------------
### Próximos passos

Para incrementar esse projeto, pretendo desenvolver o código para que quando um novo arquivo de fatura seja incluído na pasta, o banco de dados atualize e inclua na tabela as novas informações. Fazer o tratamento desses dados (limpeza, formatação e transformação) e atualizar o dashboard com as informações das novas fatuas.
