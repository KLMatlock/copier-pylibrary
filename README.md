# Copier PDM

[![ci](https://github.com/pawamoy/copier-pdm/workflows/ci/badge.svg)](https://github.com/pawamoy/copier-pdm/actions?query=workflow%3Aci)
[![documentation](https://img.shields.io/badge/docs-mkdocs%20material-blue.svg?style=flat)](https://pawamoy.github.io/copier-pdm/)
[![gitter](https://badges.gitter.im/join%20chat.svg)](https://app.gitter.im/#/room/#copier-pdm/community:gitter.im)

[Copier](https://github.com/copier-org/copier) template
for Python projects, forked from [PDM](https://github.com/pdm-project/pdm).

## Features

- Documentation built with [MkDocs](https://github.com/mkdocs/mkdocs)
  ([Material theme](https://github.com/squidfunk/mkdocs-material)
  and "autodoc" [mkdocstrings plugin](https://github.com/mkdocstrings/mkdocstrings))
- Pre-configured tools for code formatting, quality analysis and testing:
    - [black](https://github.com/psf/black),
    - [blacken-docs](https://github.com/adamchainz/blacken-docs),
    - [ruff](https://github.com/charliermarsh/ruff),
    - [mypy](https://github.com/python/mypy),
    - [safety](https://github.com/pyupio/safety)
- Tests run with [pytest](https://github.com/pytest-dev/pytest) and plugins, with [coverage](https://github.com/nedbat/coveragepy) support
- Cross-platform tasks with [duty](https://github.com/pawamoy/duty)
- Support for GitHub workflows
- Python 3.9 or above
- All licenses from [choosealicense.com](https://choosealicense.com/appendix/)
- Makefile for convenience

## Quick setup and usage

Make sure all the
[requirements](/docs/requirements.md)
are met, then:

```bash
copier copy --trust "https://github.com/pawamoy/copier-pdm.git" /path/to/your/new/project
```

Or even shorter:

```bash
copier copy --trust "gh:pawamoy/copier-pdm" /path/to/your/new/project
```

See the [documentation](https://pawamoy.github.io/copier-pdm)
for more details.
