# Requisitos do Sistema — SIGA

## Objetivo
Sistema de controle de inventário (SIGA), permitindo cadastro, consulta e gestão de itens em estoque.

## Requisitos Funcionais
- RF01: Cadastrar item no inventário
- RF02: Consultar itens por código/nome
- RF03: Atualizar quantidade em estoque
- RF04: Gerar relatório de estoque

## Requisitos Não Funcionais
- RNF01: Sistema deve rodar em Python 3.x
- RNF02: Persistência de dados em PostgreSQL
- RNF03: Configurações sensíveis via variáveis de ambiente (.env)

## Estrutura do Projeto
- `src/` — código-fonte da aplicação
- `db/migrations/` — scripts de migração do banco de dados
- `docs/` — documentação do projeto
- `tests/` — testes automatizados
