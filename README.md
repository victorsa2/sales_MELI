# Desenvolvimento Desafio de Vendas Mercado Livre

## Consumo de dados da API do Mercado Livre de Produto e Vendas:

https://developers.mercadolivre.com.br/pt_br/itens-e-buscas#Buscar-itens-por-categoria
https://developers.mercadolivre.com.br/pt_br/gerenciamento-de-vendas

OBS: A API de vendas estava com problemas de permissão, então tive que sumilar os dados de vendas no chat GPT, com base na resposta da API de produtos (data_raw/products.csv)

Os resultados desta extração foram salvos na pasta "data_raw", para serem consumidos na próxima etapa do código.

## Exploração e tratamento inicial dos Dados
Realizei a exploração dos dados para verificar se haviam tratamentos necessários, como ajustes de tipo de colunas, valores nulos em campos chaves ou exclusão de colunas que não seriam enviadas para o banco e os salvei na pasta de "data_processed"

## Criação do Banco de Dados / DataWarehouse e resolução de exercícios

Criei o banco de dados e as tabelas, separando os dados crus com o prefíxo "raw" e as tabelas para o Data Warehouse com "dim" para dimensões e "fact" para a minha fato.
A ideia é criar um modelo de dados performatíco para ser consumido no Tableau.

Também realizei algunas consultas para responder algumas perguntas do desafio também.


## Arquivo do Tableau
Arquivo .TWB com algumas visões solicitadas no desafio.

## Relatório final
Relatório com algumas análises finais sobre os dados coletados e apresentados no Tableau.
