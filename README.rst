Version Switcher Test
=====================

The aim of the project is to test PyData Sphinx Theme
`Version switcher dropdown <https://pydata-sphinx-theme.readthedocs.io/en/stable/user_guide/version-dropdown.html>`_
in local development mode.

Tested on Python version: 3.10.14

Steps to reproduce:

.. code-block:: console

    pip install -r requirements.txt
    sphinx-build -M html docs/source docs/build

Open `./docs/build/html/index.html` in browser.
