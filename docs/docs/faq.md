# Frequently asked questions

## How to generate the docs locally

NOTE: We will be using `pipenv` as the virtual environment and package manager. Support for `pip`/`virtualenv` will be secondary. This means that the instructions will be focused on `pipenv` and the `requirements.txt` file could be out-of-date.

- From the root of repo, run:

  ```bash
  cd docs
  pipenv run mkdocs serve
  ```

- Visit <http://127.0.0.1:8000> to view the docs.
- Source changes will result in automatic rebuilds and browser page reload.