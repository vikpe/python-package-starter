# Python Package Starter
> Python 3.x package starter.

[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)

## Features
* Single `pyproject.toml` config ([PEP518](https://www.python.org/dev/peps/pep-0518/))
* Multi-version support (pyenv, TOX)
* Build/publish to PyPi (poetry)
* Continous integration (Travis CI)
* Code formatting (black)

## Installation
1. Clone repo: `git clone git@github.com:vikpe/python-package-starter.git [YOUR_PACKAGE_NAME]`
2. Install dependencies `poetry install`

## Development

### Tests
**Run tests in current Python version**
```sh
poetry run pytest
```

**Multi-version test using TOX**
```sh
tox
```

### Linting
```sh
black
```

## Production

### Build
```sh
poetry build
```

### Publish to PyPi
```sh
poetry publish
```

## Continous integration

### Travis CI
[todo]

### Code coverage
[todo]
