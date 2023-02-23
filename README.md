# Bank Account
## Este é um programa em Java que simula um sistema de conta bancária. Ele permite criar uma conta, depositar e sacar fundos e verificar o saldo.

## Como usar
Para executar este programa, você precisa ter o Java instalado em seu computador.

Clone ou faça o download do repositório para sua máquina local.

Abra o terminal e navegue até o diretório onde salvou os arquivos.

Compile o programa usando o seguinte comando:

javac application/Program.java

Execute o programa usando o seguinte comando:

java application.Program

## Uso
Ao executar o programa, você será solicitado a inserir as seguintes informações para criar uma nova conta:

Número da conta
Nome do titular da conta
Saldo inicial
Limite de saque
Após criar a conta, você pode realizar as seguintes ações:

Depositar fundos
Sacar fundos
Verificar o saldo
Ao fazer um saque, o programa verificará se o valor que você está tentando sacar está dentro do limite de saque e se o saldo da sua conta é suficiente. Se uma dessas condições não for atendida, o programa exibirá uma mensagem de erro.

## Estrutura do código
O programa consiste em três arquivos:

Program.java: Este arquivo contém o método principal onde o usuário pode interagir com o programa através do console.
Account.java: Este arquivo contém a classe Account que representa uma conta bancária. Ela possui quatro variáveis de instância: number, holder, balance e withdrawLimit.
BusinessException.java: Este arquivo contém a classe BusinessException que estende a classe RuntimeException. Ela é lançada quando uma regra de negócio é violada.
Tratamento de Erros
Quando uma BusinessException é lançada, o programa captura a exceção e exibe uma mensagem de erro para o usuário.

## Conclusão
Este programa demonstra como criar um sistema simples de conta bancária em Java. Com algumas modificações, ele pode ser expandido para incluir recursos adicionais, como transferência de fundos entre contas, aplicação de taxas de juros e gerenciamento de várias contas.
