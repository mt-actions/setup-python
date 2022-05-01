# Setup Python Action

- Sets up the python environment using actions/setup-python@v3
- Installs poetry
- Adds a private pypi repository (optional)
- Installs all the packages using poetry

## Inputs
- python-version: `[required]`
  - The python version to be used
- url: `[optional]`
    - The url of a private pypi repository that should be configured in poetry
- user: `[optional]`
    - The username to be used to connect to the private pypi repository
- password: `[optional]`
    - The password to be used to connect to the private pypi repository
