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

## 5. Resumo das Necessidades

O sistema deverá atender às seguintes necessidades:

- **Simulação de transações PIX**: Implementação de um sistema seguro e eficiente para transações de PIX.
- **Gestão de Chaves PIX**: Suporte a operações de cadastro, exclusão e listagem de chaves PIX.
- **Integração Bancária**: Comunicação entre os bancos e o Banco Central para garantir a verificação e autorização das transações.
- **Gestão de Contas e Usuários**: Funcionalidades básicas de controle de contas bancárias e usuários do sistema.

## 6. Requisitos Funcionais

#### RF1 - Cadastro de Usuários:
Permitir que o cliente cadastre-se no sistema, criando uma conta no banco.

#### RF2 - Registro de Contas
O cliente deve poder registrar uma conta associada ao seu perfil.

#### RF3 - Consulta de Saldo
O cliente deve poder consultar o saldo atual de sua conta bancária.

#### RF4 - Extrato Bancário
O cliente deve poder acessar o extrato detalhado das transações realizadas.

#### RF5 - Cadastro de Chave PIX
Permitir que o cliente registre uma chave PIX vinculada à sua conta no banco.

#### RF6 - Listagem de Chaves PIX
O cliente deve poder visualizar todas as chaves PIX cadastradas em sua conta bancária.

#### RF7 - Exclusão de Chave PIX
O cliente deve ter a capacidade de excluir uma chave PIX vinculada à sua conta.

#### RF8 - Transferência via PIX
Permitir que o cliente realize transferências via PIX para outras contas, utilizando a chave PIX associada à sua conta.

#### RF9 - Controle de Chaves PIX (Banco Central)
A API Banco Central deve permitir o registro e consulta das chaves PIX de cada cliente registrado pelos bancos.

#### RF10 - Controle de Bancos
O Banco Central deverá ser capaz de gerenciar os bancos participantes, garantindo que apenas instituições financeiras autorizadas possam registrar e realizar transferências.

#### RF11 - Interação entre API Banco e Banco Central
Cada banco deve se comunicar com a API Banco Central para validar e autorizar transações PIX entre contas.

#### RF12 - Simulação de Múltiplos Bancos e Clientes
O sistema deve suportar a existência de múltiplas instâncias do App Cliente e da API Banco para testar transações entre diferentes bancos.

7. Diagrama de Componentes

![alt text](/documents/diagramaDeComponetes.png)

8. Para o executar na sua máquina é necessário a instalação dos seguintes:
    8.1 Nodejs
    8.2 Npm
    8.3 Xaamp

