# Apache Spark com Delta Lake e Apache Iceberg

## Integrantes
- William Manoel Bitencourt Mesquita

---

## Sobre o Projeto

Este projeto tem como objetivo demonstrar o uso do **Apache Spark (PySpark)**
em conjunto com os formatos de tabela **Delta Lake** e **Apache Iceberg**,
evidenciando operações ACID (INSERT, UPDATE e DELETE) em um contexto de
arquitetura de dados do tipo **Lakehouse**.

O trabalho faz parte da disciplina de Arquitetura de Dados e atende aos
requisitos propostos pelo professor, incluindo implementação prática,
documentação e reprodutibilidade do ambiente.

---

## Tecnologias Utilizadas

- Apache Spark 3.5.x
- PySpark
- Delta Lake
- Apache Iceberg
- Python 3.10+
- Poetry (gerenciamento de dependências)
- Jupyter Lab / Notebook
- Java 11+

---

## Estrutura do Repositório

```text
.
├── delta/
│   ├── pyproject.toml
│   ├── poetry.lock
│   └── notebook_delta.ipynb
│
├── iceberg/
│   ├── pyproject.toml
│   ├── poetry.lock
│   └── notebook_iceberg.ipynb
│
├── mkdocs/
│   └── site (conteúdo do MKDocs)
│
└── README.md
```

## Gerenciamento de Dependências

O projeto utiliza exclusivamente o **Poetry** como gerenciador de dependências,
conforme solicitado.

Foram criados **ambientes independentes** para **Delta Lake** e **Apache Iceberg**
com o objetivo de evitar conflitos de versões entre bibliotecas do Apache Spark,
Delta Lake e Apache Iceberg, prática comum em projetos reais de Engenharia de
Dados.

Cada diretório (`delta/` e `iceberg/`) possui seu próprio `pyproject.toml` e
`poetry.lock`, garantindo isolamento, estabilidade e reprodutibilidade do
ambiente.

---

## Como Executar o Projeto

### Pré-requisitos

- Python 3.10 ou superior  
- Java 11  
- Poetry instalado  
- Apache Spark compatível com as versões utilizadas  

### Ambiente Delta Lake

```bash
cd delta
poetry install --no-root
poetry run jupyter lab
```

### Ambiente Apache Iceberg

```bash
cd iceberg
poetry install --no-root
poetry run jupyter lab
```