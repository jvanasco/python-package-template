# {{cookiecutter.project_name}}

{{cookiecutter.project_name}} is a Python package utilizing the namespace
{{cookiecutter.package_name}}.

## Installation

Installing in a virtual environment is recommended.

    # Change directory into your newly created project if not already there. Your
    # current directory should be the same as this README.txt file and setup.py.
    $ cd {{cookiecutter.package_name}}

    # Create a Python virtual environment, if not already created.
    $ python3 -m venv env

    # Upgrade packaging tools.
    $ env/bin/pip install --upgrade pip setuptools

    # Install the project in editable mode with its testing requirements.
    $ env/bin/pip install -e ".[testing]"


## Testing

The project is configured to only test `/tests_unit`, however namespaces are
created for `/tests_integrated` and `/tests_functional`.
