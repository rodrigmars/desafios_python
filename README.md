# Desafios Python

## Exercício-1: Cálcular frete de produto

> **Enunciado**: Desenvolva um módulo em python usando o paradigma funcional para cálcular frete de produto.
Usar o arquivo "exercise_1/produtos.dump" para acesso a lista de produtos

**Fórmula**:
Valor do frete = [(Valor total do produto na nota ÷ valor total da nota) x Valor do frete]/100.

**Exemplo**:
Valor do frete = (5000÷5000) x 300) ÷ 100

Usar a PEP-8(Python Enhancement Protocol 8) para convenções.

PEP 8 – Style Guide for Python Code
[PEP 8](https://peps.python.org/pep-0008/)

[Versão Python](#versão-python)

[Criar ambiente](#criar-ambiente)

[Instalar bibliotecas](#instalar-bibliotecas)

[Gerar arquivo de dependências](#gerar-arquivo-de-dependências)

## Versão Python

Versão necessária para
[python 3.9.2](https://www.python.org/downloads/release/python-392/)

Obs:Para uma instalação do python utilize a ferramenta pyenv
[pyenv-win](https://github.com/pyenv-win/pyenv-win)

## Criar ambiente

```bash
mkdir exercicio_1 && cd exercicio_1
python -m venv venv-exercicio_1
mkdir exercicio_1
```

Linux:

```bash
source venv-exercicio_1/bin/activate
```

Windows:

```bash
venv-exercicio_1\Scripts\activate
```

Dúvidas sobre [venv](https://docs.python.org/3/library/venv.html)

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

Linux:

```bash
pip freeze | grep -E 'autopep8|pycodestyle|pylint|pytest' > requirements.txt
```

Windows:

```bash
pip freeze | findstr 'autopep8 pycodestyle pylint pytest' > requirements.txt
```
