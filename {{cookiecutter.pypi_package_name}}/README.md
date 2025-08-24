# {{ cookiecutter.project_name }}

![PyPI version](https://img.shields.io/pypi/v/{{ cookiecutter.pypi_package_name }}.svg)
[![Documentation Status](https://readthedocs.org/projects/{{ cookiecutter.pypi_package_name }}/badge/?version=latest)](https://{{ cookiecutter.pypi_package_name }}.readthedocs.io/en/latest/?version=latest)

{{ cookiecutter.project_short_description }}

* PyPI package: https://pypi.org/project/{{ cookiecutter.pypi_package_name }}/
* Free software: MIT License
* Documentation: https://{{ cookiecutter.pypi_package_name }}.readthedocs.io.

## Features

* TODO

## Development Notes
Create virtual environment and install packages:
```
uv venv
uv sync
```

Install pre-commit (needs to be done in venv):
```
source .venv/bin/activate
pre-commit install
```

Run Tests & Linters
```
nox
```

## Credits

This package was created with [Cookiecutter](https://github.com/audreyfeldroy/cookiecutter) and the [audreyfeldroy/cookiecutter-pypackage](https://github.com/audreyfeldroy/cookiecutter-pypackage) project template.
