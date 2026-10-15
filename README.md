# Flix App

## Requisitos

Antes de começar, certifique-se de ter instalado:

- Python 3.14.5 ou superior (versão utilizada no desenvolvimento).
- Git.
- Pip, gerenciador de pacotes do Python.

## 1. Clonar os repositórios

Primeiro, clone o repositório da API:

```bash
git clone https://github.com/rimarassi/flix_api.git
```

Em seguida, clone o repositório da aplicação:

```bash
git clone https://github.com/rimarassi/flix_app.git
```

Entre na pasta da API:

```bash
cd flix_api
```

## 2. Configurar e executar a API

Crie um ambiente virtual:

```bash
python -m venv venv
```

Ative o ambiente virtual no Windows (PowerShell):

```powershell
.\venv\Scripts\Activate.ps1
```

Instale as dependências:

```bash
pip install -r requirements.txt
```

Inicie o servidor Django:

```bash
python manage.py runserver
```

Por padrão, a API estará disponível em:

http://127.0.0.1:8000

**Importante:** mantenha o terminal da API aberto enquanto estiver utilizando a aplicação.

## 3. Configurar e executar o Flix App

Abra um **novo terminal** e entre na pasta do projeto:

```bash
cd flix_app
```

Crie um ambiente virtual:

```bash
python -m venv venv
```

Ative o ambiente virtual no Windows (PowerShell):

```powershell
.\venv\Scripts\Activate.ps1
```

Instale as dependências do projeto:

```bash
pip install -r requirements.txt
```

Execute a aplicação:

```bash
streamlit run app.py
```

Após iniciar, acesse o sistema pelo navegador:

http://localhost:8501

## 4. Ordem de execução

Para utilizar o projeto corretamente, siga esta ordem:

1. Inicie a API Django (`flix_api`).
2. Mantenha a API em execução.
3. Inicie o Flix App (`flix_app`) em outro terminal.
4. Acesse a aplicação pelo navegador.
5. Faça login para acessar as funcionalidades disponíveis.
