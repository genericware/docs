# docs
[![pre-commit.ci status](https://results.pre-commit.ci/badge/github/genericware/docs/master.svg)](https://results.pre-commit.ci/latest/github/genericware/docs/master)

Documentation containing designs, guides, and notes.

## Dependencies

| Name                                       | Description                                |
|--------------------------------------------|--------------------------------------------|
| [poetry](https://github.com/python-poetry) | Python packaging and dependency management |

## Install

```shell
poetry install
poetry shell
pre-commit install
```

## Build

```shell
poetry build
```

## Usage

[//]: # (todo: doc build command)

test:
```shell
pytest .
```

check:
```shell
pre-commit run
```
