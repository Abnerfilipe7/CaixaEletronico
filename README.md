# Caixa Eletrônico Simulado

Este projeto é uma aplicação de console em C# que simula um caixa eletrônico, permitindo ao usuário gerenciar duas contas: Conta Corrente e Conta Poupança. As operações disponíveis incluem depósitos, saques, consultas de saldo, extratos e transferências.

## Funcionalidades

- **Seleção de Tipo de Conta**: O usuário pode escolher entre Conta Corrente e Conta Poupança.
- **Operações Disponíveis**:
  - **Depósito**: Adiciona um valor ao saldo da conta.
  - **Saque**: Retira um valor do saldo, se houver saldo suficiente.
  - **Saldo**: Consulta o saldo atual da conta.
  - **Extrato**: Exibe todas as transações realizadas na conta.
  - **Transferência**: Realiza transferências, se houver saldo suficiente.
  - **Sair**: Sai do gerenciamento da conta.

## Estrutura do Código

- **Variáveis**:
  - `depositoC`, `depositoP`: Valores de depósito para as contas Corrente e Poupança.
  - `saqueC`, `saqueP`: Valores de saque para as contas Corrente e Poupança.
  - `transC`, `transP`: Valores de transferência para as contas Corrente e Poupança.
  - `saldoC`, `saldoP`: Saldos das contas, iniciados em 0.
  - `extratoC`, `extratoP`: Strings para o histórico de transações.

- **Estruturas de Controle**:
  - Laços `while` para interação contínua até o usuário decidir sair.
  - Estruturas `switch` para gerenciar as opções escolhidas.

## Instruções para Uso

1. Execute o programa em um ambiente que suporte C#.
2. Selecione o tipo de conta (1 para Conta Corrente, 2 para Conta Poupança, 3 para Sair).
3. Escolha a operação desejada na conta selecionada.
4. Siga as instruções exibidas no console para realizar as transações.

## Exemplo de Uso

- Ao iniciar, escolha "1" para Conta Corrente.
- Escolha "1" para Depósito e insira um valor.
- Para verificar o saldo, escolha "3".
- Para sair, escolha "6" e depois "3".

## Notas

- O programa possui verificações para garantir a validade dos valores inseridos.
- Saques e transferências são limitados ao saldo disponível.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para sugerir melhorias ou novas funcionalidades.
