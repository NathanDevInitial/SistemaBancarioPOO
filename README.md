# SistemaBancarioPOO
Utilização de POO na linguagem de programação Python


#  Classe de Sistema Bancário em Python

Este projeto Python implementa um sistema bancário simples com classes para clientes, contas e transações. O código oferece funcionalidades para criar e gerenciar contas bancárias, depositar e sacar fundos, bem como visualizar o histórico de transações.

Estrutura das Classes

1.  Cliente: Representa um cliente bancário com nome, data de nascimento, CPF (número de identificação brasileiro) e endereço. Os clientes podem ter uma ou mais contas bancárias.

2.  Conta: A classe base para contas bancárias, com atributos para número da conta, saldo e um histórico de transações. Ela fornece métodos para depositar e sacar fundos.

3.  ContaCorrente: Uma subclasse de Conta que representa uma conta corrente com recursos adicionais, como um limite de crédito e um número máximo de saques permitidos.

4.  Historico: Uma classe para armazenar o histórico de transações, incluindo o tipo de transação, o valor e o carimbo de data/hora.

5.  Transacao (Classe Abstrata): Uma classe abstrata base para transações, com métodos abstratos para o valor da transação e o registro.

6.  Saque: Uma subclasse de Transacao que representa uma transação de saque.

7.  Deposito: Uma subclasse de Transacao que representa uma transação de depósito.

#  Funcionalidade Principal

-  A função menu fornece um menu de texto simples para que os usuários escolham várias operações bancárias, incluindo depósito, saque, visualização de extrato, criação de novos clientes e contas bancárias, listagem de contas existentes e saída do aplicativo.

-  O código permite criar novos clientes e contas bancárias, depositar e sacar fundos e visualizar o histórico de transações. Ele também impõe limites de saques para contas correntes.

#  Uso

-  Para utilizar este código, basta executar a função main, e você será solicitado a escolher entre várias operações bancárias usando o menu fornecido.

***  Sinta-se à vontade para adaptar e aprimorar este código para o seu caso específico ou usá-lo como base para implementações mais avançadas de sistemas bancários.

#  ***  Observação: Este código é um exemplo simples e não lida com transações financeiras reais ou preocupações de segurança.
