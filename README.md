# cookiecutter-django

This is a cookiecutter template for Django projects, inspired by https://github.com/pydanny/cookiecutter-django and customized to my personal defaults and needs.

## Features

* Uses Django 1.10
* [Tox](https://tox.readthedocs.io/en/latest/) configuration
* [Pytest](http://pytest.org/latest/) for unit testing
* [Sphinx](http://www.sphinx-doc.org/en/stable/) documentation
* (Optional) [Bumpversion](https://github.com/peritus/bumpversion) for updating version information
* (Optional) Travis-CI configuration

## Usage

Install [cookiecutter](https://github.com/audreyr/cookiecutter):

    $ pip install cookiecutter

Initialize the package by using the cookiecutter template:

    $ cookiecutter https://github.com/hkage/cookiecutter-django
