# Python Workflows

Workflows for your Python code.

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

For more details on how it works, see the file: [flake8.yaml](https://github.com/gh-actions-workflows/python-workflows/blob/master/.github/workflows/flake8.yaml).

## Tests - Pytest

```yaml
name: Python Workflow
on: [push]

jobs:
  test:
    uses: gh-actions-workflows/python-workflows/.github/workflows/pytest.yaml@1.2
    with:
      python-version: '3.10' 
```

For more details on how it works, see the file: [pytest.yaml](https://github.com/gh-actions-workflows/python-workflows/blob/master/.github/workflows/pytest.yaml).
