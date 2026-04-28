# Apache Iceberg

Apache Iceberg é um formato de tabela para Data Lakes que fornece suporte a
operações ACID, versionamento e evolução de esquema.

## Estrutura de Catálogos e Namespaces

Neste projeto, foi utilizado um catálogo local com namespace padrão.

## Operações ACID no Iceberg

Através do Apache Spark, foram executadas operações de INSERT, UPDATE e DELETE
sobre tabelas Iceberg, demonstrando suporte transacional completo.

```sql
INSERT INTO local.default.policies VALUES (...);
```
