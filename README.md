# FastAPI - Documentação 📚

## Guia de Instalação e Uso do Ambiente Virtual no Python 💻

Este guia fornece instruções sobre como configurar e usar um ambiente virtual no Python, juntamente com o comando `pip freeze` para gerenciar dependências.

### Configurando o Ambiente Virtual

1. **Instalação do Python Virtualenv**:

    No Linux, você pode instalar o `virtualenv` usando o `pip`. Certifique-se de ter o Python e o `pip` instalados. Execute o seguinte comando no seu terminal:

    ```bash
    sudo apt-get install python3-venv
    ```

2. **Criando um Ambiente Virtual**:

    No diretório do seu projeto, execute o seguinte comando para criar um ambiente virtual:

    ```bash
    python3 -m venv myenv
    ```

    Isso criará um novo ambiente virtual chamado `myenv`.

3. **Ativando o Ambiente Virtual**:

    Para ativar o ambiente virtual, execute:

    ```bash
    source myenv/bin/activate
    ```

### Gerenciando Dependências com pip freeze

- Para instalar dependências em seu ambiente virtual, você pode usar o `pip` normalmente. Por exemplo:

    ```bash
    pip install nome-da-dependencia
    ```

- Para listar todas as dependências instaladas em seu ambiente virtual, você pode usar o comando `pip freeze`:

    ```bash
    pip freeze > requirements.txt
    ```

    Isso irá salvar todas as dependências e suas versões em um arquivo chamado `requirements.txt`.

- Para instalar todas as dependências listadas em um arquivo `requirements.txt`, execute:

    ```bash
    pip install -r requirements.txt
    ```

Lembre-se de substituir `nome-da-dependencia` pelos nomes reais das suas dependências.

## Instalação do FastAPI

[Documentação do FastAPI](https://github.com/tiangolo/fastapi#installation)
