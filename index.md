## SQL do Básico ao Avançado

# O Que é SQL ?

Structured Query Language, ou Linguagem de Consulta Estruturada ou SQL, é a linguagem de pesquisa declarativa padrão para banco de dados relacional.

## Podemos:

###1. Criar uma Base de Dados:

``` CREATE DATABASE [NOME DO BANCO];
```
Exemplo: 

``` CREATE DATABASE db_agencia; ```
``` USE db_agencia;```
O "USE" é para selecionar a base de dados recém criada para que, futuras queries adicionadas não cheguem a atingir outra base de dados.

###2. Inserir Tabelas e Colunas:

``` CREATE TABLE tb_cliente (
        cpf varchar (11) not null primary key,
        nome varchar (50) not null,
        endereco varchar (40) not null,
        bairro varchar (20) not null,
        complemento (50) not null);
```

``` CREATE TABLE tb_vendedor (

```

###3. Realizar Consultas

###4. Apagar os Dados de uma Tabela ou Coluna

###5. Deletar uma Tabela.

###6. Deletar um Banco de Dados.
