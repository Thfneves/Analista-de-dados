







Desafio1AlluraColab, arquivo em panda a proposta foi carregas os dados do arquivo de vendas e clientes, filtrar e limpar os bancos de dados, responder perguntas de negocio feitas pelo desafio e baixar para tratar os dados via SQL.
 Meu maior desafio foi converter e importar os dados para o SQL, um dos arquivos era convertido mas nao era aceito no SQL, em uma busca via IA identifiquei que o grande problema era o nome dos produtos na tabela vendas, pois tinham acentos e espaços nos nomes
 e o SQL nao filtrava essas informações.

A proposta abaixo foi identificar o faturamento e crescimento mensal
 |index|Mes|faturamento|crescimento\_pct|
|---|---|---|---|
|0|1|234634\.61|NaN|
|1|2|282351\.34|20\.336611891996693|
|2|3|293842\.93|4\.069961205071659|


Busquei entender o faturamento e representatividade de cada produto e categoria 

|index|categoria|faturamento|Participacao|
|---|---|---|---|
|6|Periféricos|307921\.82|37\.97617815487776|
|4|Livros|140285\.75|17\.301523596446145|
|3|Eletrônicos|124973\.54|15\.413059781491748|
|2|Decoração|109156\.43|13\.46232635423642|
|0|Colecionáveis|55658\.46|6\.864390424771254|
|1|Componentes|35468\.07|4\.374297817315042|
|7|Áudio|29281\.47|3\.611300820957438|
|5|Móveis|8083\.34|0\.9969230499041918|

---
