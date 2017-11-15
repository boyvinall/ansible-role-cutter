# ansible-role-cutter

This is a simple [cookiecutter](https://cookiecutter.readthedocs.io/) template which
can be used to create a new ansible role.  See also [ansible-cutter](https://github.com/boyvinall/ansible-cutter)
which generates a top-level project.

## Installing cookiecutter

    pip install cookiecutter

if you get a bunch of errors on a mac then try this:

    sudo -H pip install --ignore-installed cookiecutter

## Using this template

You can easily add this to your `~/.cookiecutterrc` something like this:

    abbreviations:
      ansible-role: https://github.com/boyvinall/ansible-role-cutter.git

Then you can run the following command to create a new ansible project:

    cookiecutter ansible-role
