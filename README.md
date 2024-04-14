# Python Workflows

Workflows para o seu código Python.

## Lint - Flake8

```yaml
name: Python Workflow
on: [push]

jobs:
  lint:
    uses: PedroHPAlmeida/actions-workflows-python/.github/workflows/flake8.yaml@1.2
    with:
      python-version: '3.10' 
```

Para mais detalhes sobre o funcionamento consulte o arquivo: [flake8.yaml](https://github.com/PedroHPAlmeida/actions-workflows-python/blob/master/.github/workflows/flake8.yaml).

## Testes - Pytest

```yaml
name: Python Workflow
on: [push]

jobs:
  test:
    uses: PedroHPAlmeida/actions-workflows-python/.github/workflows/pytest.yaml@1.2
    with:
      python-version: '3.10' 
```

Para mais detalhes sobre o funcionamento consulte o arquivo: [pytest.yaml](https://github.com/PedroHPAlmeida/actions-workflows-python/blob/master/.github/workflows/pytest.yaml).
