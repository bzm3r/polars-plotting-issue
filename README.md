# polars-plotting-issue

Minimal reproducible not-working example for Polars + Altair plotting issue. 

## Environment setup

I am using [`rye`](https://rye.astral.sh/) to easily set up the environment for the test, but the `pyproject.toml` should be compatible with other tools too. If you want to use `rye`, here are some instructions to help out:

### Installing Rye

**Note:** if you are on Windows, make sure to [enable developer mode](https://rye.astral.sh/guide/faq/#windows-developer-mode) before installing `rye`.

- Install [`rye`](https://rye.astral.sh/guide/installation/#installing-rye).
  - Choose `uv` as the preferred package installer
  - Choose `Run a Python installed and managed by Rye` for which Python should be used in a Rye managed project.
  - Choose the latest version of Python available
    - this project will always use the latest version available
- change directory to where this project is
- run `rye sync`
- **unnecessary unless you really need to**:
  - to activate the virtual environment created by `rye` manually (e.g. within a terminal), [follow the typical instructions for activating a virtual environment](https://docs.python.org/3/tutorial/venv.html); in this project's case, the virtual environment folder is called `.venv` (automatically created by `rye`), so you would run
    - (if on Linux): `source ./.venv/bin/activate`
    - (if on Windows): `./.venv/Scripts/activate`

## Running the examples

Execute the Jupyter Notebook located at: `src/polars-plotting-issue/color_scheme.ipynb`. 
