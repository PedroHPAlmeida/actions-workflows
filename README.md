# Python Workflows

Workflows para o seu código Python.

## Lint - Flake8

```yaml
name: Python Workflow
on: [push]

jobs:
  lint:
    uses: gh-actions-workflows/python-workflows/.github/workflows/flake8.yaml@1.2
    with:
      python-version: '3.10' 
```

Para mais detalhes sobre o funcionamento consulte o arquivo: [flake8.yaml](https://github.com/gh-actions-workflows/python-workflows/blob/master/.github/workflows/flake8.yaml).

## Testes - Pytest

```yaml
name: Python Workflow
on: [push]

jobs:
  test:
    uses: gh-actions-workflows/python-workflows/.github/workflows/pytest.yaml@1.2
    with:
      python-version: '3.10' 
```

Para mais detalhes sobre o funcionamento consulte o arquivo: [pytest.yaml](https://github.com/gh-actions-workflows/python-workflows/blob/master/.github/workflows/pytest.yaml).
