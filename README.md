# Python Package Starter
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)

## Features
* Multi-version support ([pyenv](https://github.com/pyenv/pyenv), [tox](https://github.com/tox-dev/tox/))
* Simple config using the new standardized `pyproject.toml` ([PEP518](https://www.python.org/dev/peps/pep-0518/))
* Build/publish/dependency management using ([poetry](https://github.com/sdispater/poetry))
* Continous integration ([Travis CI](https://travis-ci.org/))
* Code formatting ([black](https://github.com/psf/black))

## Prerequisites
* [pyenv](https://github.com/pyenv/pyenv)

## Installation
1. Install the Python versions you want to support using pyenv.
2. Clone repo: `git clone git@github.com:vikpe/python-package-starter.git [YOUR_PACKAGE_NAME]`
3. Install dependencies `poetry install`

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
