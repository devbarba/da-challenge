# Teste Back-end Digital Apps

Este teste tem como objetivo conhecer um pouco mais como você programa, e como você vai se organizar para montar um pequeno sistema de controle de estacionamento.

## 1. O que você precisa fazer?

Você poderá utilizar qualquer uma das linguagens abaixo descritas:
- Node.JS (Express, Adonis, Nest.JS, Happi).
- PHP (Laravel ou Lumen).

Esperamos que você desenvolva um serviço que forneça uma API REST que implemente os recursos a seguir e respeite os seguintes requisitos técnicos:

### 1.1. Autenticação:
  Nossa aplicação demendará de autenticação utilizando JWT.

### 1.2. Cadastro de usuários.
  Crie recursos para usuários c/ 2 níveis de acesso (Administrador, Colaborador) e realize restrição para que somente Administradores autenticados consigam acesso.
  
  #### 1.2.1. Endpoints Necessários
    - Listagem geral.
    - listagem por id.
    - Criação.
    - Edição.
    - Deleção.

### 1.3. Entrada de Veículos
  Crie recursos para Entrada de Veículos com restrição para que qualquer nível de usuário autenticado consiga acesso.
  
  #### 1.3.1. Dados Indispensáveis
    - Placa do veículo,
    - Modelo.
    - Marca.
    - Cor.
    - Horário de entrada.
    - Horário de saída.
    - Valor a ser pago pelo permanência.

  #### 1.3.2. Endpoints Necessários
    - Listagem geral.
    - listagem por id.
    - Criação.
    - Edição.
    - Deleção.

### 1.4. Entrada de Veículos
  Crie recursos para Valores de Permanência de Veículos no estacionamento com restrição para que somente administradores autenticados consigam acesso.
  
  #### 1.4.1. Dados Indispensáveis
    - Tipo de Veículo,
    - Quantidade de horas.
    - Valor.

  #### 1.4.2. Endpoints Necessários
    - Listagem geral.
    - listagem por id.
    - Criação.
    - Edição.
    - Deleção.

## 2. Observações

- Não se esqueça de criar um README explicando como faremos para rodar sua aplicação e demais informações que ache necessário.
- Poderá ser utilizado qualquer banco de dados SQL ou NoSQL.

## 3. Seria legal se você utilizasse

- Docker.
- Design Patterns.
- Testes Unitários e de Integração.

## 4. Método de avaliação
Avaliaremos seu desafio de código com base em alguns atributos de qualidade do sistema. Alguns nós consideramos indispensáveis, como correção, e serão avaliados em uma abordagem binária (funciona / segue ou não). Os outros, por não serem objetivos, não poderão sozinhos desabonar seu desafio. Estes são todos os atributos de qualidade que esperamos que você aborde:

- Correção: Seu código deve seguir todos os requisitos apresentados no item 1 e seus subsequentes até 1.4.2.
- Desempenho: Quanto mais dados você puder lidar e mais rápido você consultar, melhor.
- Testabilidade: Quão bem testado seu código é e quão fácil é adicionar novos testes ao seu código.
- Capacidade de manutenção: Como é fácil adicionar recursos extras ao seu código.
- Separação de Conceitos: (https://en.wikipedia.org/wiki/Separation_of_concerns).


## 5. Como enviar?
Crie um repositório público no Github e envie um e-mail para harbsprog@gmail.com com o link do mesmo.

## 6. Dúvidas?
Assunto: Challenge Backend Digital Apps.
E-mail: harbsprog@gmail.com

Boa sorte! :)
