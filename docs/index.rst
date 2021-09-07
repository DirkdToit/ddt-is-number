is-number
=========

.. image:: https://img.shields.io/pypi/v/ddt-is-number
    :target: https://pypi.org/project/ddt-is-number/
    :alt: PyPI

.. image:: https://github.com/DirkdToit/ddt-is-number/actions/workflows/ci.yaml/badge.svg
    :target: https://github.com/DirkdToit/ddt-is-number/actions/workflows/ci.yaml
    :alt: GitHub Actions - CI

.. image:: https://github.com/DirkdToit/ddt-is-number/actions/workflows/pre-commit.yaml/badge.svg
    :target: https://github.com/DirkdToit/ddt-is-number/actions/workflows/pre-commit.yaml
    :alt: GitHub Actions - pre-commit

.. image:: https://img.shields.io/codecov/c/gh/DirkdToit/ddt-is-number
    :target: https://app.codecov.io/gh/DirkdToit/ddt-is-number
    :alt: Codecov

A Python library to determine if something is a number.

Installation
------------

.. code-block:: bash

   pip install ddt-is-number

Usage
-----

.. code-block:: python

   >>> from is_number import is_number
   >>> is_number(10)
   True
   >>> is_number("hello")
   False


.. toctree::
   :maxdepth: 2
   :caption: Contents:

   api
   faq

