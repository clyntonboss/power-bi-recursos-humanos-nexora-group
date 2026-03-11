# Documentação das Medidas: Projeto Recursos Humanos — Nexora Group

Este documento descreve as medidas criadas no modelo semântico do Power BI relacionadas às tabelas **dIntegrantes** e **fEntrevistas**.

Todas as medidas seguem o padrão de desenvolvimento adotado no projeto:

- Uso de `VAR` para armazenar resultados intermediários
- Uso de `COALESCE()` para evitar retorno `BLANK()`
- Documentação clara da regra de negócio
- Estrutura padronizada para facilitar manutenção e escalabilidade

---

# Medidas da Dimensão Integrantes

## quantidade_colaboradores

**Descrição**

Quantidade total de colaboradores registrados na dimensão de integrantes.

**Tabela origem**

`dIntegrantes`

**Regra de negócio**

Conta todas as linhas da tabela `dIntegrantes`, representando o total de colaboradores cadastrados.

**Retorno**

Número inteiro representando a quantidade total de colaboradores.

```DAX
quantidade_colaboradores =
VAR Resultado =
    COUNTROWS(
        dIntegrantes
    )
RETURN
    COALESCE(Resultado, 0)
```

---

## quantidade_cargos

**Descrição**

Quantidade distinta de cargos existentes na dimensão de integrantes.

**Tabela origem**

`dIntegrantes`

**Regra de negócio**

Conta os valores distintos da coluna `cargo`, representando a quantidade de cargos únicos existentes.

**Retorno**

Número inteiro representando a quantidade de cargos distintos.

```DAX
quantidade_cargos =
VAR Resultado =
    DISTINCTCOUNT(
        dIntegrantes[cargo]
    )
RETURN
    COALESCE(Resultado, 0)
```

---

# Medidas da Fato Entrevistas

## quantidade_perguntas

**Descrição**

Quantidade total de perguntas registradas na tabela de entrevistas.

**Tabela origem**

`fEntrevistas`

**Regra de negócio**

Conta todas as linhas da tabela `fEntrevistas`, representando o total de perguntas registradas no processo de entrevistas.

**Retorno**

Número inteiro representando a quantidade total de perguntas.

```DAX
quantidade_perguntas =
VAR Resultado =
    COUNTROWS(
        fEntrevistas
    )
RETURN
    COALESCE(Resultado, 0)
```

---

# Padrão adotado no projeto

Todas as medidas seguem os seguintes princípios de desenvolvimento:

- Clareza na regra de negócio
- Padronização de código
- Tratamento de valores nulos
- Facilidade de manutenção
- Documentação integrada ao projeto

Esse padrão garante maior **qualidade técnica**, **legibilidade do modelo semântico** e **facilidade de colaboração em ambientes versionados**, como projetos mantidos no GitHub.
