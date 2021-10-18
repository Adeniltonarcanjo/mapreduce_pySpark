# mapreduce_pySpark
Essa atividade faz parte da matéria de Sistemas Distribuídos e tem como objetivo o uso da programação mapreduce e pySpark com o objetivo de processar dados.


#Especificação:


Utilizando PySpark, você deve implementar um algoritmo que:
- Imprima os 100 filmes (um filme por linha) com as maiores médias (em ordem decrescente) no formato: "<nome do filme>, <média>"
- A média deve ser apresentada com duas casas decimais.


Você só pode utilizar funções transformation do tipo map*, reduce* para implementar a lógica, onde o * indica um sufixo. Por exemplo, a função reduceByKey se encaixa no padrão reduce*.


Você não pode utilizar data frame nem função aggregate.


Você só pode utilizar par chave-valor.


Exemplo de saída:
Filme1, 10.00
Filme2, 9.95
Filme3, 9.94
