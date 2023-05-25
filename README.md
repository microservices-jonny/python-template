
# Python Project Template

A low dependency and really simple to start project template for Python Projects. 

### HOW TO USE THIS TEMPLATE

1. Wait until the first run of CI finishes  
   (Github Actions will process the template and commit to your new repo)
2. If you want [codecov](https://about.codecov.io/sign-up/) Reports and Automatic Release to [PyPI](https://pypi.org)  
  On the new repository `settings->secrets` add your `PYPI_API_TOKEN` and `CODECOV_TOKEN` (get the tokens on respective websites)
3. Read the file [CONTRIBUTING.md](CONTRIBUTING.md)

> **NOTE**: **WAIT** until first CI run on github actions before cloning your new project.

### What is included on this template?

- 🖼️ Templates for starting multiple application types:
  * **Basic low dependency** Python program (default) [use this template](https://github.com/rochacbruno/python-project-template/generate)
  * **Flask** with database, admin interface, restapi and authentication [use this template](https://github.com/rochacbruno/flask-project-template/generate).
  **or Run `make init` after cloning to generate a new project based on a template.**
- 📦 A basic [setup.py](setup.py) file to provide installation, packaging and distribution for your project.  
  Template uses setuptools because it's the de-facto standard for Python packages, you can run `make switch-to-poetry` later if you want.
- 🤖 A [Makefile](Makefile) with the most useful commands to install, test, lint, format and release your project.
- 📃 Documentation structure using [mkdocs](http://www.mkdocs.org)
- 💬 Auto generation of change log using **gitchangelog** to keep a HISTORY.md file automatically based on your commit history on every release.
- 🐋 A simple [Containerfile](Containerfile) to build a container image for your project.  
  `Containerfile` is a more open standard for building container images than Dockerfile, you can use buildah or docker with this file.
- 🧪 Testing structure using [pytest](https://docs.pytest.org/en/latest/)
- ✅ Code linting using [flake8](https://flake8.pycqa.org/en/latest/)
- 📊 Code coverage reports using [codecov](https://about.codecov.io/sign-up/)
- 🛳️ Automatic release to [PyPI](https://pypi.org) using [twine](https://twine.readthedocs.io/en/latest/) and github actions.
- 🎯 Entry points to execute your program using `python -m <python_template>` or `$ python_template` with basic CLI argument parsing.
- 🔄 Continuous integration using [Github Actions](.github/workflows/) with jobs to lint, test and release your project on Linux, Mac and Windows environments.

---
> **NOTE**: Feel free to delete above lines
# python_template

[![codecov](https://codecov.io/gh/microservices-jonny/python-template/branch/main/graph/badge.svg?token=python-template_token_here)](https://codecov.io/gh/microservices-jonny/python-template)
[![CI](https://github.com/microservices-jonny/python-template/actions/workflows/main.yml/badge.svg)](https://github.com/microservices-jonny/python-template/actions/workflows/main.yml)

Awesome python_template created by microservices-jonny

## Install it from PyPI

```bash
pip install python_template
```

## Usage

```py
from python_template import BaseClass
from python_template import base_function

BaseClass().base_method()
base_function()
```

```bash
$ python -m python_template
#or
$ python_template
```

## Development

Read the [CONTRIBUTING.md](CONTRIBUTING.md) file.
