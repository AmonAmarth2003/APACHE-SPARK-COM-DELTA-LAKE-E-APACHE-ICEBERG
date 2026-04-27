# APACHE-SPARK-COM-DELTA-LAKE-E-APACHE-ICEBERG
Integrantes: William Manoel Bitencourt Mesquita

## Apache Spark com Delta Lake e Apache Iceberg

### Requisitos
- Python 3.10+
- Java 11+
- Poetry
- Apache Spark 3.5.x

### Estrutura do projeto
- delta/ → Notebook com Delta Lake
- iceberg/ → Notebook com Apache Iceberg

### Ambiente Delta
```bash
cd delta
poetry install --no-root
poetry run jupyter lab
``## Apache Spark com Delta Lake e Apache Iceberg

### Requisitos
- Python 3.10+
- Java 11+
- Poetry
- Apache Spark 3.5.x

### Estrutura do projeto
- delta/ → Notebook com Delta Lake
- iceberg/ → Notebook com Apache Iceberg

### Ambiente Delta
```bash
cd delta
poetry install --no-root
poetry run jupyter lab
``

### Gerenciamento de Dependências e Ambiente

Para este projeto, foi adotado exclusivamente o Poetry como gerenciador de
dependências. Optou-se pela criação de ambientes independentes para Delta Lake
e Apache Iceberg a fim de evitar conflitos de versões entre bibliotecas do Apache
Spark e seus formatos de tabela, garantindo maior estabilidade e reprodutibilidade
do ambiente.