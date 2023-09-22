# desafio-back-end 1

 Crie um servido que receba:
 -id
 -Nome
 -Vaga
 -Salário 
 de cada funcionário
 
 Posteriormente, possibilite a edição e exclusão de cada usuário

# desafio-back-end 2

Seu desafio será implementar um serviço que determine quais modalidades de empréstimo uma pessoa tem acesso.

As modalidades de empréstimo que serão analisadas são:

-Empréstimo pessoal: Taxa de juros de 4%.
-Empréstimo consignado: Taxa de juros de 2%.
-Empréstimo com garantia: Taxa de juros de 3%.

As modalidades de empréstimo disponíveis para uma pessoa são baseadas no salário e na função.

Seu serviço deve retornar uma resposta contendo o nome do cliente e uma lista de empréstimos aos quais ele tem acesso, com os respectivos tipos e taxas de juros.

Conceder o empréstimo pessoal se o salário do cliente for igual ou inferior a R$ 3000.
Conceder o empréstimo consignado se o salário do cliente for igual ou superior a R$ 5000.
Conceder o empréstimo com garantia se o salário do cliente for igual ou inferior a R$ 3000
