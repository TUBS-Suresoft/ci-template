# ci-template

This repository contains a minimal example for a GitHub workflow to automatically

- test Python code using [pytest](https://docs.pytest.org/en/7.2.x/)
- type-check Python code using [mypy](https://mypy-lang.org/)

All checks are automatically performed with three different Python versions. To use the contents of this repository
as a starting point for your development, simply replace the `mypkg` folder with your actual package code, delete the
file `tests/test_dummy.py` and place your tests in the `tests` folder. Finally, replace this `README.md` file with a
description of your project.
