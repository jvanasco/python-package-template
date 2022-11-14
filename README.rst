=======================
python-package-template
=======================

A cookiecutter (project template) for quickly stubbing out a new Python project.

This simply generates the core project directory and files.

This is a quick way to kickstart a python project with a generic scaffold that
has testing and code quality hooks.  This library is an abstraction of the
package configuration and layout used by multiple open source and proprietary
projects I maintain or assist in.  

The project is configured to only test `/tests_unit`, however namespaces are
created for `/tests_integrated` and `/tests_functional`.

Based on https://github.com/Pylons/pyramid-cookiecutter-starter

This project is released via the MIT license. Projects you generate with it may
use any open source, commercial or proprietary license you desire.

Requirements
------------

*   Python 3.6+
*   `cookiecutter <https://cookiecutter.readthedocs.io/en/latest/installation.html>`_


Usage
-----

#.  Generate a Project

    .. code-block:: bash

        $ cookiecutter gh:jvanasco/python-package-template
        
#.  Follow the directions to enter the project name and author info

The cookiecutter
