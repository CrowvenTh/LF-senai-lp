Projeto Gestão de Restaurante
Contexto
O restaurante "Churrasquinho do Maranhão" deseja informatizar sua gestão de comandas e pedidos, permitindo um controle eficiente dos pratos pedidos por cada mesa. 
O sistema precisa registrar as comandas abertas, os pratos e/ou bebidas do cardápio e os pedidos realizados, garantindo que cada comanda possa conter múltiplos itens.

Requisitos do Sistema
O sistema deve armazenar as seguintes informações:

Comanda
Cada comanda possui um número.
Cada comanda possui o número da mesa.
O nome do cliente pode ser registrado, mas não é obrigatório.
Data e hora de abertuta.
Data e hora de fechamento.

Cardápio
Cada item possui um nome, uma descrição, um preço e uma quantidade em estoque(não obrigatório).

Pedidos
Cada pedido está associado a uma comanda e possui uma data e hora.
Um pedido pode conter um ou mais pratos, com a respectiva quantidade.

Objetivo
Você deve criar um banco de dados relacional para armazenar essas informações e desenvolver os comandos SQL necessários para:

Criar o modelo conceitual (DER-Conceitual).
Criar o modelo lógico (DER-Lógico).
Criar o banco e as tabelas seguindo a modelagem proposta (DDL).
Inserir dados no banco representando diferentes cenários de comandas e pedidos (DML).

Executar consultas para extrair informações importantes do banco (DQL), como:
Listar todas as comandas abertas.
Consultar o cardápio completo.
Obter o histórico de pedidos realizados.
Verificar quais pratos foram pedidos em uma determinada comanda.
Calcular o total gasto por cada comanda.

Desafios Extras
Implemente uma consulta SQL para identificar qual prato foi o mais pedido e quantas vezes ele foi solicitado.
Criar um procedure que atualize a quantidade de um item do cardápio.
Criar um trigger que subtraia a quantidade de um tem do cardápio quando for solicitado em um pedido.