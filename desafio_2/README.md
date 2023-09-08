# Desafio 2: Cadastro usuário

**Enunciado**: 눈_눈

Criar um projeto do tipo "Console App" com suporte a CRUD (Create, Read, Update, Delete).
O projeto deve ser desenvolvido na versão 3.11.5 do Python.
Contemplar um menu para as operações de cadastro, consulta, edição e exclusão de usuário. 
O banco de dados deve ser desenvolvido em SQLite, não utilizar ferramentas de ORM (Object-Relational Mapping).

## Campos
name: str
email: str
password: str
confirm_password: str

## Criação de ambiente
Obs: Alterar o nome "name-project" para um nome padrão.

```bash
New-item -Name "name_project" -ItemType Directory

cd .\name-project\

New-item -Name "name_project" -ItemType Directory

python -m venv .\venv_name_project\

.\venv_name_project\Scripts\activate
```

## Dependências

```bash
pip install pylint

pip install --upgrade autopep8
```

## Gerar arquivo de dependências

Linux: ✔

```bash
pip freeze | grep -E 'autopep8|pycodestyle|pylint|pytest' > requirements.txt
```

Windows:

```bash
pip freeze | findstr 'autopep8 pycodestyle pylint pytest' > requirements.txt
```