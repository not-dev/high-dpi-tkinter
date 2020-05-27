[英語](./README.md) / 日本語

<!-- ![](./res/) -->

# python-template

Pythonプロジェクトのためのボイラープレート。

## 特徴

これらを含む

* Python
* Pipenv

## インストール

```sh
git clone https://github.com/not-dev/python-template.git
```

## 使用方法

```sh
SET PIPENV_VENV_IN_PROJECT=1
py -m pipenv install --dev
```

## ライセンス

* コード: MIT License
* ロゴ: CC BY-ND
* このプロジェクトはOSSを含みます

## 生成方法

```sh
# .venv, Pipfile, Pipfile.lock
SET PIPENV_VENV_IN_PROJECT=1
pipenv install --dev flake8 mypy
pipenv install --dev --pre yapf
---
GitHub >> .git, .gitignore, LICENSE, README.md
ADD >> README_JP.md, src/, src/__init__py, src/__main__py, setup.cfg, setup.py
```
