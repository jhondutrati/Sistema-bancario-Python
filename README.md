Sistema de Controle Financeiro Simples
Este é um sistema de controle financeiro básico implementado em Python. O sistema permite realizar operações simples como depósito, saque, exibição de extrato e sair do sistema.

Funcionalidades
Depositar
Permite adicionar fundos à sua conta.
Sacar
Permite retirar fundos da sua conta, sujeito a algumas condições:
Saldo suficiente.
Limite de saque diário não excedido.
Limite de quantidade de saques por dia não excedido.
Extrato
Exibe um resumo das transações realizadas e o saldo atual da conta.
Sair
Encerra o programa.
Uso
Ao iniciar o programa, será exibido um menu interativo.
Escolha uma das opções digitando a letra correspondente:
d para depositar.
s para sacar.
e para visualizar o extrato.
q para sair do sistema.
Siga as instruções na tela para concluir cada operação.
Observações
Depósito:
Você pode depositar qualquer valor positivo.
Saque:
O valor do saque não pode exceder seu saldo atual.
Há um limite diário de saques (LIMITE_SAQUES) definido como 3 saques por dia.
O valor do saque não pode exceder o limite diário definido (limite).
Extrato:
Exibe um registro das transações realizadas.
Mostra o saldo atual da conta.
Exemplo de Uso
python
Copy code
python controle_financeiro.py
Requisitos
Python 3.x (ou superior)
Melhorias Futuras
Implementar persistência de dados para salvar o estado da conta entre execuções.
Adicionar autenticação para acesso seguro ao sistema.
Permitir transferências entre contas.
Melhorar a interface do usuário com gráficos ou visualizações mais detalhadas.