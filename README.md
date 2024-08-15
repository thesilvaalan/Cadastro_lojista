**Sistema de Gestão de Cadastros em Java**

Este projeto é um Sistema de Gestão de Cadastros desenvolvido em Java, utilizando conceitos de Programação Orientada a Objetos (POO). Ele foi criado para gerenciar o registro de usuários e a catalogação de clientes de uma forma simples e eficiente. O sistema é ideal para pequenas empresas ou aplicações que necessitam de um controle básico de usuários e clientes.

**Objetivo**

O objetivo principal deste software é fornecer uma solução básica para o gerenciamento de cadastros de usuários e clientes. Ele permite que os administradores ou operadores do sistema registrem novos usuários, cadastrem clientes, busquem informações específicas e listem todos os registros existentes.

**Funcionalidades**

_**1-Registro de Usuários:**_

Permite registrar novos usuários com nome, email e senha.
Armazena os dados dos usuários em uma lista interna, simulando um banco de dados.
_**2-Cadastro de Clientes:**_

Permite registrar novos clientes com nome, CPF e endereço.
Armazena os dados dos clientes em uma lista interna, simulando um banco de dados.
_**3-Listagem de Usuários:**_

Exibe uma lista de todos os usuários registrados no sistema.
_**4-Listagem de Clientes:**_

Exibe uma lista de todos os clientes cadastrados no sistema.
_**5-Busca de Usuário por Email:**_

Permite buscar e exibir as informações de um usuário específico usando seu email.
_**6-Busca de Cliente por CPF:**_

Permite buscar e exibir as informações de um cliente específico usando seu CPF.

**Como Funciona**

O sistema é operado por meio de uma interface de linha de comando (CLI), onde o usuário escolhe entre as opções disponíveis para realizar as operações de cadastro, busca ou listagem.

Ao iniciar o programa, um menu de opções é exibido, permitindo ao usuário escolher a ação desejada:

**º Registrar Usuário:** Solicita os dados (nome, email e senha) e os armazena.
**º Registrar Cliente:** Solicita os dados (nome, CPF e endereço) e os armazena.
**º Listar Usuários/Clientes:** Exibe todos os usuários ou clientes cadastrados.
**º Buscar Usuário/Cliente:** Busca e exibe os dados de um usuário ou cliente específico.
**º Sair:** Encerra o programa.

**Requisitos**

**Java 8 ou superior:** O sistema é desenvolvido em Java, então é necessário ter o Java Development Kit (JDK) instalado.
**IDE Java (opcional):** Você pode utilizar o IntelliJ IDEA, Eclipse ou qualquer outra IDE de sua preferência para compilar e executar o projeto.

**Estrutura do Código**
O código está organizado em uma única classe Main.java, mas está dividido conceitualmente em diferentes seções que representariam os pacotes model, repository, controller e view em um projeto maior e mais modularizado.

**Contribuições**
Sinta-se à vontade para contribuir com o projeto! Se encontrar bugs, tiver ideias para novas funcionalidades ou melhorias, abra uma issue ou envie um pull request.
