# Projeto -Python para Controle Financeiro - Python Puro

## Descrição

Este projeto é uma aplicação em Python puro para gestão de contas bancárias. Ele permite a criação de contas, movimentação de saldos, transferências entre contas, desativação de contas, análise de histórico financeiro e geração de gráficos.

## Tecnologias Utilizadas

- Python
- SQLite (via SQLModel)
- Matplotlib (para geração de gráficos)

## Configuração do Ambiente

Para executar o projeto, primeiro crie um ambiente virtual:

### Criar ambiente virtual:

#### Linux:

```sh
python3 -m venv venv
```

#### Windows:

```sh
python -m venv venv
```

### Ativar ambiente virtual:

#### Linux:

```sh
source venv/bin/activate
```

#### Windows:

```sh
venv\Scripts\Activate
```

Caso encontre problemas de permissão no Windows, execute:

```sh
Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned
```

### Instalar dependências:

```sh
pip install sqlmodel matplotlib
```

## Estrutura do Projeto

```
Projeto1/
│── models.py         # Modelos e configuração do banco de dados
│── view.py           # Funções para manipulação de contas e movimentação financeira
│── templates.py      # Interface de linha de comando para interação com o usuário
│── database.db       # Banco de dados SQLite (criado automaticamente na execução)
```

## Como Executar

1. Certifique-se de que o ambiente virtual está ativado.
2. Execute o arquivo principal para iniciar a interface interativa:

```sh
python .\templates.py
```

## Funcionalidades

1. **Criar conta:** Permite criar uma conta bancária.
2. **Desativar conta:** Desativa contas sem saldo.
3. **Transferir dinheiro:** Transferência de saldo entre contas.
4. **Movimentar dinheiro:** Registrar entradas e saídas de dinheiro.
5. **Total de todas as contas:** Soma de saldo das contas ativas.
6. **Filtrar histórico:** Exibir movimentações dentro de um período.
7. **Gerar gráfico:** Exibir um gráfico de saldo por banco.


Projeto desenvolvido com Python puro, SQLModel e Matplotlib para fins de aprendizado e gestão financeira.

