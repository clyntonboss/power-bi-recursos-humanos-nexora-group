# Documentação das Medidas: Projeto Recursos Humanos — Nexora Group

Este documento lista todas as medidas criadas no modelo Power BI, suas regras de negócio, dependências e retornos esperados.

---

## Medidas de Contagem

### quatidade_colaboradores

```DAX
quantidade_colaboradores = 

-- Medida:
--      quantidade_colaboradores
--
-- Descrição:
--      Quantidade total de colaboradores registrados na dimensão de colaboradores
--
-- Tabela origem:
--      dColaboradores
--
-- Regra de negócio:
--      Conta todas as linhas da tabela dColaboradores, representando o total de colaboradores
--
-- Dependência:
--      dColaboradores
--
-- Retorno:
--      Número inteiro representando a quantidade total de colaboradores
--
-- Observação:
--      COALESCE é utilizado para evitar retorno BLANK()

VAR _Resultado =
    COUNTROWS(
        dColaboradores
    )

RETURN
    COALESCE(
        _Resultado,
        0
    )
```

Descrição: Quantidade de colaboradores participantes.

### quantidade_cargos

```DAX
quantidade_cargos = 

-- Medida:
--      quantidade_cargos
--
-- Descrição:
--      Quantidade distinta de cargos existentes na dimensão de cargos
--
-- Tabela origem:
--      dCargos
--
-- Regra de negócio:
--      Conta os cargos únicos registrados na dimensão de cargos
--
-- Dependência:
--      dCargos
--
-- Retorno:
--      Número inteiro representando a quantidade de cargos distintos
--
-- Observação:
--      COALESCE é utilizado para evitar retorno BLANK()

VAR _Resultado =
    COUNTROWS(
        dCargos
    )

RETURN
    COALESCE(
        _Resultado,
        0
    )
```
Descrição: Quantidade de cargos monitorados.

### quatidade_perguntas

```DAX
quantidade_perguntas = 

-- Medida:
--      quantidade_perguntas
--
-- Descrição:
--      Quantidade total de perguntas registradas na tabela de entrevistas
--
-- Tabela origem:
--      fEntrevistas
--
-- Regra de negócio:
--      Conta todas as linhas da tabela fEntrevistas, representando o total de perguntas
--
-- Dependência:
--      fEntrevistas
--
-- Retorno:
--      Número inteiro representando a quantidade total de perguntas
--
-- Observação:
--      COALESCE é utilizado para evitar retorno BLANK()

VAR _Resultado =
    COUNTROWS(
        fEntrevistas
    )

RETURN
    COALESCE(
        _Resultado,
        0
    )
```
Descrição: Quantidade perguntas durante as entrevistas.
