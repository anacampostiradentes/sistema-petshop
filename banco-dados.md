# Banco de Dados

## Entidades principais

### Cliente
- id_cliente (PK)
- nome
- telefone
- email
- endereco

### Pet
- id_pet (PK)
- nome
- especie
- raca
- idade
- id_cliente (FK)

### Serviço
- id_servico (PK)
- nome
- descricao
- preco
- duracao

### Agendamento
- id_agendamento (PK)
- data
- horario
- status
- id_cliente (FK)
- id_pet (FK)
- id_servico (FK)

### Produto
- id_produto (PK)
- nome
- categoria
- preco
- estoque

### Venda
- id_venda (PK)
- data
- valor_total
- id_cliente (FK)

### ItemVenda
- id_item (PK)
- quantidade
- preco_unitario
- id_venda (FK)
- id_produto (FK)

## Relacionamentos
- Um cliente pode possuir vários pets.
- Um pet pertence a um cliente.
- Um cliente pode possuir vários agendamentos.
- Um serviço pode aparecer em vários agendamentos.
- Uma venda possui vários itens.
- Um produto pode aparecer em vários itens de venda.
