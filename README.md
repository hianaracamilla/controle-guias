# Controle de Guias

Este projeto contém um código em Python, implementado em um Jupyter Notebook, que processa e manipula dados de guias de viagens. O código realiza operações de limpeza e transformação em uma tabela extraída de um arquivo HTML.

## Pré-requisitos

- Python 3.6 ou superior
- Jupyter Notebook
- Bibliotecas:
  - `pandas` (para manipulação de dados)

## Uso

1. O notebook começa com a importação da biblioteca `pandas`, essencial para a manipulação dos dados.
2. Em seguida, um arquivo HTML contendo as guias de viagens é lido e convertido em uma lista de DataFrames.
3. O DataFrame que contém as informações relevantes é selecionado e processado:
   - Linhas desnecessárias são removidas.
   - Colunas não relevantes são descartadas.
   - Os dados são reorganizados e preparados para análise.

4. Após a execução do notebook, os dados estarão prontos para análises adicionais ou exportação para outros formatos.
