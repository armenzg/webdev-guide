# Frequently asked questions

## How to generate the docs locally

NOTE: We will be using `pipenv` as the virtual environment and package manager. Support for `pip`/`virtualenv` will be secondary. This means that the instructions will be focused on `pipenv`. If a `requirements.txt` file is found is due that it is necessary for some external service (e.g. readthedocs).

- From the root of repo, run:

```bash
pipenv install
pipenv run mkdocs serve
```

- Visit <http://127.0.0.1:8000> to view the docs.
- Source changes will result in automatic rebuilds and browser page reload.