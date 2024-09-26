Teste Técnico de Conhecimentos em SQL As consultas realizadas foram as seguintes, na ordem:

1.Consulta de Funcionários: Escreva uma query para listar todos os funcionários ativos, mostrando as colunas id, nome, salario. Ordene o resultado pelo nome em ordem ascendente;

2.Funcionários com Salário Acima da Média: Escreva uma query para listar os funcionários que possuem um salário acima da média salarial de todos os funcionários. A consulta deve mostrar as colunas id, nome, e salario, ordenadas pelo salario em ordem descendente;

3.Resumo por cliente: Escreva uma query para listar todos os clientes e o valor total de pedidos já transmitidos. A consulta deve retornar as colunas id, razao_social, total, ordenadas pelo total em ordem descendente;

4.Situação por pedido: Escreva uma query que retorne a situação atual de cada pedido da base. A consulta deve retornar as colunas id, valor, data e situacao. A situacao deve obedecer a seguinte regra: -Se possui data de cancelamento preenchido: CANCELADO -Se possui data de faturamento preenchido: FATURADO -Caso não possua data de cancelamento e nem faturamento: PENDENTE;

5.Produtos mais vendidos: Escreva uma query que retorne o produto mais vendido ( em quantidade ), incluindo o valor total vendido deste produto, quantidade de pedidos em que ele apareceu e para quantos clientes diferentes ele foi vendido. A consulta deve retornar as colunas id_produto, quantidade_vendida, total_vendido, clientes, pedidos. Caso haja empate em quantidade de vendas, utilizar o total vendido como critério de desempate.

Utilizei as tabelas e dados presentes no arquivo schema.sql. Certifiquei de que os nomes das colunas no resultado sejam exatamente os especificados e retornados nos desafios. Validei minhas respostas utilizando o compilador online https://sqlfiddle.com/postgresql/online-compiler.
