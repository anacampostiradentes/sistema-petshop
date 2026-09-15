# Arquitetura

## Visão geral
A proposta utiliza uma arquitetura em camadas:

1. **Interface:** telas acessadas pelos funcionários.
2. **Aplicação:** regras de negócio e processamento das operações.
3. **Persistência:** comunicação com o banco de dados.
4. **Banco de dados:** armazenamento das informações.

## Fluxo
`Usuário → Interface → Aplicação/Regras de Negócio → Banco de Dados`

## Tecnologias sugeridas
- HTML e CSS para a interface
- Python para a aplicação
- SQLite ou MySQL para o banco de dados
- Git e GitHub para versionamento e documentação
