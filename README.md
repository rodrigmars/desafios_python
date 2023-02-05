# Desafios Python

## Exercício-1: Cálcular frete de produto

**Enunciado**: 눈_눈

Desenvolva um módulo em python usando o paradigma funcional para cálcular frete de produto.
Usar o arquivo [produtos](https://github.com/rodrigmars/desafios_python/tree/de7f38b2346543099e48ea2eaa06a1954e251ba5/exercicio_1) para acesso a lista de produtos

**Fórmula**: ⥀.⥀

Valor do frete = [(Valor total do produto na nota ÷ valor total da nota) x Valor do frete]/100.

**Exemplo**: (Ծ‸ Ծ)

Valor do frete = (5000÷5000) x 300) ÷ 100

- ## 𓀎 Guia de procedimentos

  - [Convenções](#convenções)
  - [Versão Python](#versão-python)
  - [Criar ambiente](#criar-ambiente)
  - [Ativar ambiente](#ativar-ambiente)
  - [Instalar bibliotecas](#instalar-bibliotecas)
  - [Gerar arquivo de dependências](#gerar-arquivo-de-dependências)

## Convenções

Adotar convenções da [PEP 8 – Style Guide for Python Code](https://peps.python.org/pep-0008/).

## Versão Python

Versão [python 3.9.2](https://www.python.org/downloads/release/python-392/)  necessária L(° O °L)

Para instalação do python, selecione uma das ferramentas:

- Linux
  - [Simple Python Version Management: pyenv](https://github.com/pyenv/pyenv)
  - [asdf-python](https://github.com/asdf-community/asdf-python)

- Windows
  - [pyenv for Windows](https://github.com/pyenv-win/pyenv-win)
  - [chocolatey - python 3.9.2](https://community.chocolatey.org/packages/python/3.9.2)

## Criar ambiente

```bash
mkdir exercicio_1 && cd exercicio_1
python -m venv venv-exercicio_1
mkdir exercicio_1
```

## Ativar ambiente

Linux: ✔

```bash
source venv-exercicio_1/bin/activate
```

Windows:

```bash
venv-exercicio_1\Scripts\activate
```

ಥ Dúvidas sobre [venv](https://docs.python.org/3/library/venv.html)

## Instalar bibliotecas

[autopep8](https://github.com/hhatto/autopep8)

```bash
pip install --upgrade autopep8
```

[pycodestyle](https://github.com/PyCQA/pycodestyle)

```bash
pip install --upgrade pycodestyle
```

[pylint](https://github.com/PyCQA/pylint)

```bash
pip install --upgrade pylint
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

(╯°□°）╯︵ ┻━┻

Agora é só aguardar pelo próximo desafio
