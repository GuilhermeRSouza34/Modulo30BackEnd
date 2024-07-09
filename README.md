# Projeto Java com Adição de Propriedade em Cliente e Integração com Tabela de Estoque

Este projeto Java foi desenvolvido para expandir a funcionalidade da classe Cliente ao adicionar uma nova propriedade, modificando simultaneamente o DAO genérico para suportar essa alteração. Além disso, foram realizadas modificações na classe Cliente e no método de atualização (update), estendendo essas mudanças para a classe Produto. Para complementar, foi implementada uma tabela de estoque e estabelecido um relacionamento entre a classe Produto e a nova tabela de Estoque.

## Tecnologias Utilizadas

- **Java**: Linguagem de programação principal do projeto.
- **Spring Framework**: Utilizado para injeção de dependências e configuração do aplicativo.
- **Hibernate**: Framework ORM para mapeamento objeto-relacional.
- **JUnit**: Framework de testes unitários para validação das modificações.
- **Banco de Dados Relacional**: Utilizado para persistência dos dados, possivelmente PostgreSQL, MySQL, ou similar.
- **Git**: Controle de versão utilizado para gerenciar o código-fonte do projeto.

## Funcionalidades Implementadas

- **Adição de Propriedade em Cliente**: Incorporação de uma nova propriedade na classe Cliente.
- **Modificação Genérica em DAO**: Adaptação do DAO genérico para suportar a nova propriedade e garantir a integridade dos dados.
- **Integração com Tabela de Estoque**: Criação da tabela de Estoque e estabelecimento de um relacionamento com a classe Produto.
- **Testes Unitários**: Utilização de testes automatizados com JUnit para validar as modificações implementadas.
