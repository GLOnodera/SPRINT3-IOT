# Sistema de Pontuação e Recompensas - Saúde Bucal

Este projeto gerencia o sistema de pontuação e recompensas para usuários, registrando hábitos bucais e fornecendo recompensas baseadas no desempenho. Utiliza um banco de dados Oracle para armazenar dados de usuários, hábitos e recompensas, além de um modelo de Machine Learning para fornecer recomendações personalizadas.

## Funcionalidades

- Cadastro de usuários e hábitos bucais.
- Atribuição de pontos com base nos hábitos.
- Cadastro e resgate de recompensas.
- Treinamento de modelo preditivo para recomendações.

## Tecnologias

- **Python 3.x**
- **OracleDB**
- **pandas**, **matplotlib**, **scikit-learn**

## Como Rodar

1. Instale as dependências:

    ```bash
    pip install pandas matplotlib scikit-learn oracledb
    ```

2. Configure a conexão com o banco de dados Oracle:

    ```python
    conn = oracledb.connect(user="seu_usuario", password="sua_senha", dsn="oracle.fiap.com.br:1521/orcl")
    ```

O script abrirá um menu interativo para cadastro de usuários, registro de hábitos, consulta de pontos, cadastro e resgate de recompensas, e treinamento do modelo de Machine Learning.

