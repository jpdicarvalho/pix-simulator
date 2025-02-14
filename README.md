# Sistema Bancário - PIX
Author: João Pedro Braga de Carvalho

## Documento de Visão

### 1.  Introdução
    
Este projeto tem como objetivo a criação de um sistema distribuído de transações financeiras via PIX, que simula a comunicação entre bancos e um banco central, ilustrando o funcionamento de APIs bancárias em um contexto prático. Além disso, o sistema será utilizado em uma disciplina de Sistemas Distribuídos, focando em demonstrar a interação entre sistemas através de APIs com operações de registro, consulta e transferência de fundos entre contas.


### 2.  Objetivos do Sistema

- Simular um sistema bancário para transferências instantâneas entre contas distintas por meio de PIX, com múltiplos bancos e clientes.
- Ensinar o conceito de comunicação entre APIs em um ambiente distribuído.
- Exibir operações como controle de chaves PIX, registro de contas e usuários, saldo e extrato.
- Demonstrar o fluxo de comunicação entre clientes, bancos e um banco central para garantir a segurança e integridade das transações.



## 3. Escopo do Projeto

O sistema será composto por três componentes principais:

- **API Banco Central**: Responsável pela gestão de chaves PIX e pela comunicação com os bancos.
- **API Banco**: Gerencia operações financeiras e facilita a comunicação entre o Banco Central e os clientes.
- **App Cliente**: Interface de usuário para que os clientes possam realizar cadastros e operações bancárias como consultas de saldo, extrato e transferências.

O desenvolvimento será realizado utilizando **React** para a interface do cliente e **Node.js** para o back-end das APIs. O foco será simular transações PIX e garantir uma comunicação fluida entre os serviços para validar a transação de forma correta.

## 4. Visão Geral dos Usuários

O sistema atende três tipos de usuários:

- **Clientes**: Pessoas físicas que utilizam o App Cliente para acessar serviços bancários, como consultar saldo, extrato e realizar transferências PIX.
- **Bancos**: Instituições financeiras que utilizam a API Banco para oferecer serviços aos clientes e se comunicam com o Banco Central.
- **Banco Central**: Entidade central que gerencia as chaves PIX e controla os bancos autorizados, garantindo a integridade das transações.

7. Diagrama de Componentes

![alt text](/documents/diagramaDeComponetes.png)

8. Para o executar na sua máquina é necessário a instalação dos seguintes:
    8.1 Nodejs
    8.2 Npm
    8.3 Xaamp

9. Banco de dados:

    Encontrar na pasta documents:

    9.1 banco_1;

    9.2 banco_2;
    
    9.3 banco_3;
