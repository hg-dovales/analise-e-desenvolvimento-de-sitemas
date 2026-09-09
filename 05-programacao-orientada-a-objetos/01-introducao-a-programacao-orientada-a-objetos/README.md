🧩 O que é Programação Orientada a Objetos?

A Programação Orientada a Objetos (POO) é uma forma de organizar programas utilizando **classes e objetos** para representar elementos de um problema.

Em vez de manter dados e operações espalhados pelo programa, a POO permite agrupá-los de acordo com suas responsabilidades.

Exemplos de elementos que podem ser representados:

- Cliente
- Produto
- Pedido
- Conta
- Aluno
- Livro

🏗️ Classe

Uma **classe** funciona como uma estrutura que define quais características e comportamentos determinado elemento terá.

Exemplo:

**Produto**

Características:
- nome;
- preço;
- estoque.

Comportamentos:
- alterar preço;
- verificar estoque;
- exibir informações.

📦 Objeto

Um **objeto** é uma representação criada a partir de uma classe.

Se `Produto` for uma classe, podemos ter diferentes objetos:

- Produto: Notebook
- Produto: Teclado
- Produto: Monitor

Todos seguem a estrutura definida pela classe `Produto`, mas podem possuir dados diferentes.

📝 Atributos

Os **atributos** representam as características ou dados de um objeto.

Exemplo:

**Cliente**

- nome;
- CPF;
- e-mail;
- endereço.

⚙️ Métodos

Os **métodos** representam os comportamentos ou ações que um objeto pode realizar.

Exemplo:

**Cliente**

- atualizar endereço;
- exibir informações;
- realizar pedido.

🔗 Dados + comportamentos

Uma das ideias principais da POO é manter juntos os dados e os comportamentos relacionados.

Exemplo:

**Produto**

Atributos:
- nome;
- preço;
- estoque.

Métodos:
- alterar preço;
- reduzir estoque;
- exibir detalhes.

Assim, cada elemento do sistema possui responsabilidades mais bem definidas.

🔒 Encapsulamento

O encapsulamento ajuda a **proteger os dados** de um objeto.

Em vez de permitir que qualquer parte do programa altere diretamente uma informação, podemos controlar como essa alteração acontece.

Exemplo:

O saldo de uma conta bancária não deveria poder receber qualquer valor livremente. A própria classe pode definir métodos e regras para controlar suas alterações.

🔗 Relacionamento entre classes

As classes podem se relacionar.

Em um sistema de loja:

**Cliente → realiza → Pedido**

**Pedido → possui → ItemPedido**

**ItemPedido → representa → Produto**

Dessa forma, conseguimos representar no programa as relações existentes no problema real.

🏭 Construtores

Os **construtores** são utilizados para inicializar objetos quando eles são criados.

Eles permitem definir os dados necessários para que um novo objeto comece em um estado adequado.

🎯 Benefícios da POO

A Programação Orientada a Objetos ajuda a criar sistemas:

- mais organizados;
- mais legíveis;
- mais fáceis de manter;
- mais fáceis de expandir;
- com responsabilidades bem definidas;
- com maior proteção dos dados;
- com melhor reutilização de código.

🧠 Ideia principal

Na POO, procuramos identificar no problema:

**Entidades → Características → Comportamentos → Relacionamentos**

que podem ser transformados em:

**Classes → Atributos → Métodos → Relações entre objetos**

Exemplo:

Sistema de loja

Cliente
├── atributos: nome, CPF, e-mail
└── métodos: atualizar cadastro

Produto
├── atributos: nome, preço, estoque
└── métodos: atualizar preço

Pedido
├── atributos: data, status, cliente
└── métodos: adicionar item e calcular total

A ideia é fazer com que cada classe represente uma parte do problema e possua responsabilidades bem definidas.
