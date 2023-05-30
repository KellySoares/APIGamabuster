# APIGamabuster


Instruções gerais
Olá! Nosso objetivo de hoje é construir um banco de dados para uma empresa de locação de filmes e jogos chamada GamaBuster. 

O cliente informou quais são as funcionalidades e fluxos que existem na operação dele, e com base nesses detalhes devemos criar estruturas de dados para salvar as principais informações. Nessa estrutura deverá descrever cada entidade, seus atributos e relações.

Filmes

Hoje a empresa trabalha com filmes no formato de DVD e possui uma planilha que controla a quantidade de unidades do mesmo filme. Essa mesma planilha permite ter o controle de informações como: 

Nome do filme
Gêneros que ele pertence
Ano de lançamento
Duração em minutos

Clientes

O cadastro de clientes que contém as seguintes informações:

Nome e Sobrenome
CPF
Endereço completo incluindo o CEP
Telefone para contato
E-mail
Idade (possuem uma campanha de desconto no dia do aniversário)

Reserva de Filmes

O cliente pode reservar vários filmes em uma só reserva. É gerado um número de pedido que fica vinculado ao seu cadastro, assim é possível ter o controle de quais filmes foram pegos e se já foram devolvidos ou não. 

Eles guardam também o dia que foi feita a reserva e quando deve ser feita a devolução que são sempre no prazo de 30 dias.

Todas as reservas têm um valor fixo de R$ 5 reais por filme, sendo preciso deixar descrito no número do pedido o valor total da reserva.

DICA: Não esqueça de definir cada coluna das tabelas e os relacionamento para que o fluxo de reserva de filmes funcione corretamente.
