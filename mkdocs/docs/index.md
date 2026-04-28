# Contextualização do Trabalho

Uma arquitetura de dados descreve como os dados são coletados, armazenados,
processados e consumidos dentro de uma organização, desde a origem até o uso
final pelos usuários e sistemas analíticos.

Com o crescimento do volume, variedade e velocidade dos dados, surgiram
arquiteturas voltadas para Big Data, como Data Lakes e Data Warehouses.
Mais recentemente, o conceito de **Lakehouse** consolidou-se como uma abordagem
que combina a flexibilidade dos Data Lakes com as garantias transacionais dos
Data Warehouses.

Neste contexto, formatos de tabela como **Delta Lake** e **Apache Iceberg**
tornaram-se fundamentais, pois permitem operações ACID diretamente sobre dados
armazenados em Data Lakes.

Este projeto utiliza o **Apache Spark (PySpark)** como engine de processamento
para demonstrar, de forma prática, a criação de tabelas e a execução de
operações `INSERT`, `UPDATE` e `DELETE` utilizando Delta Lake e Apache Iceberg,
