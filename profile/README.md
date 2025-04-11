# Statheron - Inventory ERP

Statheron é um ERP voltado para a gestão de inventário. Nosso objetivo é criar uma base sólida e escalável para empresas que precisam de controle mais eficiente sobre seus produtos, movimentações e processos logísticos internos.

## Sobre o projeto

Esse é um side project criado com foco em boas práticas de arquitetura e código limpo. Estamos utilizando os conceitos do Domain-Driven Design (DDD) para modelar bem os domínios, aplicar regras de negócio com clareza e tornar o sistema fácil de manter e evoluir.

A stack utilizada inclui:

- **Backend:** C# com .NET 8, aplicando DDD, Value Objects, Services, Repositories, validações, etc.
- **Frontend:** Angular com TypeScript, criando uma interface responsiva e moderna.
- **Banco de dados:** PostgreSQL

## Principais funcionalidades

- Cadastro e edição de produtos
- Entrada e saída de estoque
- Visualização de movimentações
- Geração de relatórios
- Controle de localizações e setores de armazenamento
- Cadastro de fornecedores

## Estrutura do projeto

O projeto está dividido entre backend e frontend em repositórios separados. O backend segue a divisão de camadas:

- **Domain**: onde está a modelagem do negócio, com Entities, Value Objects e Interfaces
- **Application**: casos de uso e serviços de aplicação
- **Infrastructure**: implementação de repositórios, integração com banco de dados e providers externos
- **API**: camada de exposição REST

## Status

O projeto está em desenvolvimento ativo. Algumas funcionalidades ainda estão sendo implementadas e testadas.
