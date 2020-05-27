English / [Japanese](./README_JP.md)

<!-- ![](./res/) -->

# python-template

Template repository for Python project.

## Features

Includes

* Python
* Pipenv

## Installation

```sh
git clone https://github.com/not-dev/python-template.git
```

## Usage

```sh
SET PIPENV_VENV_IN_PROJECT=1
py -m pipenv install --dev
```

## License

* Code: MIT License
* Logos: CC BY-ND
* This project includes open source software.

## How to make

```sh
# .venv, Pipfile, Pipfile.lock
SET PIPENV_VENV_IN_PROJECT=1
pipenv install --dev flake8 mypy
pipenv install --dev --pre yapf
---
GitHub >> .git, .gitignore, LICENSE, README.md
ADD >> README_JP.md, src/, src/__init__py, src/__main__py, setup.cfg, setup.py
```
