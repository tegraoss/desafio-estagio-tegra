# Desafio para Estágio na Tegra - Loja de Livros

Desafio para programa de estágio na Tegra 2020

Leia com atenção todos os pontos do desafio a seguir

1. [O Problema]()
2. [Requisitos da Aplicação]()
3. [Lista de Livros]()
4. [Diferenciais]()
5. [Entrega]()
6. [Observações]()

## O Problema

Você precisa implementar uma lógica de carrinho de compras de uma loja de livros. Temos uma lista de livros com seus respectivos autores, preço e quantidade em estoque.

## Requisitos da Aplicação

Sua aplicação deve:

- Permitir o cadastro, remoção, alteração e listagem de livros
  - Cadastro de novos livros com os seguintes dados: Nome do livro, Autor(es), Preço e Quantidade em Estoque
  - Remoção de livros, a partir do seu ID
  - Alteração de valores de um livro
  - Listagem de livros
- Permitir adicionar livros ao carrinho de compras
- Permitir remover livros do carrinho de compras
- Exibir o valor subtotal de cada livro no carrinho de compras
- Exibir o valor total do carrinho de compras
- Ao adicionar livros ao carrinho de compras, exibir um erro e impedir que o usuário tente adicionar uma quantidade de livros maior do que o disponível em estoque

## Lista de Livros

Utilize a seguinte lista de livros como estoque inicial da loja:

| Título                                                                                                   | Autor                             | Preço    | Quantidade em Estoque |
|----------------------------------------------------------------------------------------------------------|-----------------------------------|----------|-----------------------|
| O Programador Pragmático: De Aprendiz a Mestre                                                           | Andrew Hunt, David Thomas         | R$125,50 | 50                    |
| The Mythical Man-Month: Essays on Software Engineering                                                   | Frederick P. Brooks Jr.           | R$170,19 | 32                    |
| Expressões Regulares - Uma Abordagem Divertida                                                           | Aurelio Marinho Jargas            | R$47,20  | 10                    |
| Domain-Driven Design: Tackling Complexity in the Heart of Software                                       | Eric Evans                        | R$251,14 | 32                    |
| Padrões de Arquitetura de Aplicações Corporativas                                                        | Martin Fowler                     | R$101,59 | 25                    |
| The Design of Design: Essays from a Computer Scientist                                                   | Frederick P. Jr. Brooks           | R$161,75 | 5                     |
| Shell Script Profissional                                                                                | Aurelio Marinho Jargas            | R$62,35  | 37                    |
| NoSQL Essencial: Um Guia Conciso para o Mundo Emergente da Persistência Poliglota                        | Pramod J. Sadalage, Martin Fowler | R$52,00  | 19                    |
| Refactoring: Improving the Design of Existing Code                                                       | Martin Fowler                     | R$220,63 | 43                    |
| Clean Architecture: A Craftsman's Guide to Software Structure and Design                                 | Robert C. Martin                  | R$148,61 | 1                     |
| Clean Code: A Handbook of Agile Software Craftsmanship                                                   | Robert C. Martin                  | R$180,04 | 16                    |
| Clean Agile: Back to Basics                                                                              | Robert C. Martin                  | R$174,20 | 29                    |
| Building Microservices: Designing Fine-Grained Systems                                                   | Sam Newman                        | R$209,30 | 6                     |
| Designing Data-Intensive Applications: The Big Ideas Behind Reliable, Scalable, and Maintainable Systems | Martin Kleppmann                  | R$82,99  | 37                    |

## Diferenciais

Caso queira acrescentar algumas funcionalidades no desenvolvimento do seu teste, por favor, especifique no envio do seu teste. Listamos algumas sugestões para se destacar:

- Utilizar algum banco de dados (MySQL, banco de dados em memória, etc). Inclua as queries de criação da tabela, sequence, etc para a configuração do mesmo, caso seja necessário.
- Implementar a seguinte funcionalidade de aplicação de cupom de desconto: no carrinho de compras, caso o usuário inclua o cupom de desconto **TrabalheNaTegra**, proporcionar 10% de desconto nos livros do autor “Martin Fowler”, e 20% de desconto nos livros do autor “Robert C. Martin”.
- Implementar a seguinte funcionalidade de filtro na listagem: aplicar filtro por nome do autor
- Tratamento de erros
- Implementar testes em código (teste unitário, integração, etc)

## Entrega

A entrega deste desafio é composta por:

- Código desenvolvido para a solução
- Descrição de instruções para executar o código (utilize um arquivo [README.md]() para isso)
- Caso implemente alguma das funcionalidades descritas como diferencial, listar elas nas instruções

Você deve responder o email onde este teste foi enviado para você.

> **Dica:** De preferência, disponibilize o seu código em um repositório público no github. Porém, você também pode enviar os códigos em um arquivo compactado, em anexo no email.

## Observações

- Não se preocupe se não conseguir entregar todos os requisitos, faça o seu melhor, pois é isso que procuramos: quem se arrisca e supera seus desafios :)
- Esse teste não requer uma tecnologia específica, queremos que você mostre seus conhecimentos em qualquer linguagem que se sinta confortável. Por isso, você pode desenvolver:
  - Uma aplicação com interação direto por linha de comando; ou
  - Somente o front-end (com HTML, CSS e Javascript, ou o que desejar); ou
  - Somente o back-end, com uma API; ou
  - Uma aplicação completa, com front-end e back-end

  Use a tecnologia e os meios que achar melhor para isso, sem restrições.
