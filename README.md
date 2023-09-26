# Banco-QuemPoupaTem-primeiro-semestre-
Eu e minha amiga @luanabortko2004 realizamos esse código de um banco na matéria de Fundamentos de Algoritmo no primeiro semestre da faculdade FEI. 
Ao rodar o código “parte5” aparecerá 9 opções:  
  
A primeira (1. Novo Cliente) cria um novo cliente com base nas informações pedidas ao usuário (razão social, CNPJ, tipo de conta, valor inicial e senha). Todavia, o código só roda se, em “tipo de conta”, o usuário digitar “comum” ou “plus”, com letra minúscula. 
  
A segunda (2. Apaga Cliente) apaga um cliente da lista após o usuário informar o CNPJ do cliente que deseja apagar. 
A terceira (3. Listar clientes) lista todas as informações dos clientes cadastrados menos a senha, e se o valor é modificado (por meio de depósito, débito ou transferência) aparece o valor após a modificação. 
A quarta (4. Débito) o usuário informa o CNPJ, senha e o valor que deseja retirar da conta. A quinta (5. Depósito) pede ao usuário o CNPJ e o valor a ser depositado. 
A sexta (6. Extrato) pede ao usuário o CNPJ e a senha do cliente que deseja ver o extrato e aparece as informações: Data e hora que a movimentação monetária foi realizada, além da tarifa e do saldo. Nesse exemplo criamos um cliente com razão social: eu, CNPJ: 23, Tipo de, conta: comum, Valor inicial da conta: 30, Senha: 123 e debitamos dele 10 reais, assim, ao clicar no 6, o extrato é esse: 
  
A sétima (7. Transferência entre contas) é necessário que já existam duas contas e, para a transferência, é preciso colocar corretamente o CNPJ e senha da conta que doará o dinheiro e o CNPJ correto da conta que receberá o dinheiro, e o valor a ser transferido, caso isso ocorra, aparecerá dessa forma: 
  
Assim, para ver como as contas ficaram após essa transferência é só listar clientes ou ver o extrato delas. 
Caso algum dos valores (CNPJ ou senha) sejam errados, aparece assim:  
  
A oitava (8. Cadastrar Clientes) cadastra clientes de acordo com a necessidade, ou seja, você digita quantos clientes deseja cadastrar e aparece as informações do novo cliente consecutivamente, sem ter que digitar “1” para aparecem, dessa forma: 
  
A nona (9. Sair) faz com que o loop de perguntar qual opção o usuário quer (1. Novo Cliente, 2. Apagar Cliente....) encerre. Somente ao digitar 9 que as informações coletadas no programa serão salvas no arquivo “banco.txt”. 
  
 
