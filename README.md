# Atividade Ponderada - Semana 3: Implementação e Testes em C#

## Introdução

Durante o desenvolvimento deste projeto na linguagem C#, pude revisar conceitos de programação orientada a objetos, tratamento de exceções e, especialmente, pude experienciar a criação e execução de testes unitários. A tecnologia e as práticas adotadas visaram garantir a confiabilidade do software desenvolvido, um sistema simulado de gerenciamento de contas bancárias.

## Tecnologia e Conceitos Aprendidos

### C# e .NET

C# é uma linguagem de programação que oferece uma sintaxe clara e tipos seguros. Utilizando o .NET, um framework extensivo, pude construir uma aplicação testável. Aprendi a aplicar princípios de programação orientada a objetos, como encapsulamento, ao criar a classe `BankAccount`, definindo propriedades e métodos para manipular os dados da conta bancária de forma segura.

### Tratamento de Exceções

Ao implementar os métodos `Debit` e `Credit`, percebi a importância do tratamento de exceções para lidar com entradas inválidas, como valores negativos ou montantes que excedem o saldo disponível. Aprendi a utilizar `ArgumentOutOfRangeException` para comunicar de forma clara esses erros aos usuários da classe, melhorando a usabilidade e a segurança do sistema.

### Testes Unitários com MSTest

A parte mais reveladora do projeto foi a implementação de testes unitários usando o MSTest. Compreendi que testar cada unidade do software isoladamente é crucial para identificar e corrigir bugs precocemente no ciclo de desenvolvimento. Através da criação de testes específicos para o método `Debit`, pude verificar o comportamento do código sob diferentes condições, garantindo que apenas as operações válidas fossem realizadas.

### Prática de Refatoração

Ao seguir as instruções do passo a passo e corrigir o código intencionalmente incorreto, pratiquei a refatoração para melhorar a legibilidade e a manutenção do código. Ajustei o método `Debit` para subtrair corretamente os valores e modifiquei as mensagens de exceção para serem mais descritivas. Essas mudanças tornaram o código mais claro e fácil de entender, tanto para mim quanto para outros desenvolvedores que possam trabalhar no projeto no futuro.

## Conclusão

Este projeto foi desafiador mas me permitiu aprimorar minhas habilidades em C# e .NET, além de compreender melhor o tratamento de exceções, e testes unitários. A prática de escrever código testável e a experiência de refatorar o software para melhorar sua qualidade foram agradáveis. Tenho confiança que esse aprendizado ajudará no desenvolvimento do projeto atual.