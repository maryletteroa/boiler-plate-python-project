# Abut 
Boiler plate Python project setup

```bash
# Install pipx if pipenv and cookiecutter are not installed
python3 -m pip install pipx
python3 -m pipx ensurepath

# Install pipenv using pipx
pipx install pipenv

# Use cookiecutter to create project from this template
pipx run cookiecutter gh:maryletteroa/boiler-plate-python-project

# Enter project directory
cd <repo_name>

# Initialise git repo
git init

# Install dependencies
pipenv install --dev

# Setup pre-commit and pre-push hooks
pipenv run pre-commit install -t pre-commit
pipenv run pre-commit install -t pre-push


# Create a virtual environment
pipenv shell
```

Reference: 
[How to set up a perfect Python project](https://sourcery.ai/blog/python-best-practices)
[ sourcery-ai/
python-best-practices-cookiecutter](https://github.com/sourcery-ai/python-best-practices-cookiecutter)