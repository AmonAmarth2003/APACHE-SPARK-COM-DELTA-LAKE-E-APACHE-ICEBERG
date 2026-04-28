# Delta Lake

Delta Lake é um formato de tabela open source que adiciona suporte transacional
(ACID) ao Apache Spark, utilizando um **transaction log** para garantir
consistência, isolamento e durabilidade das operações realizadas sobre os dados.

## Características Principais

- Suporte a operações ACID
- Controle de versão dos dados
- Evolução de esquema
- Integração nativa com Apache Spark

## Delta Lake no Projeto

Neste projeto, o Delta Lake foi utilizado para criar uma tabela gerenciada pelo
Apache Spark e demonstrar operações transacionais básicas em um ambiente local.

As operações realizadas incluem:

- Inserção de registros (`INSERT`)
- Atualização de registros (`UPDATE`)
- Remoção de registros (`DELETE`)

Exemplo de operação de atualização executada via Spark SQL:

```sql
UPDATE policies
SET status = 'CANCELED'
WHERE policy_id = 1;
```