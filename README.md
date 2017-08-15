# opinionated-widget-cookiecutter
#### A cookiecutter template for creating a custom Jupyter widget project

A [cookiecutter](https://github.com/audreyr/cookiecutter) template for a custom
Jupyter widget project.

## What is widget-cookiecutter?

With **widget-cookiecutter** you can create a custom Jupyter interactive
widget project with sensible defaults. widget-cookiecutter helps custom widget
authors get started with best practices for the packaging and distribution
of a custom Jupyter interactive widget library.

## Usage

Install [cookiecutter](https://github.com/audreyr/cookiecutter):

    $ pip install cookiecutter

After installing cookiecutter, use the widget-cookiecutter:

    $ cookiecutter https://github.com/vidartf/opinionated-widget-cookiecutter.git

As widget-cookiecutter runs, you will be asked for basic information about
your custom Jupyter widget project. You will be prompted for the following
information:

- `author_name`: your name or the name of your organization,
- `author_email`: your project's contact email,
- `github_project_name`: name of your custom Jupyter widget's GitHub repository,
- `github_organization_name`: name of your custom Jupyter widget's GitHub user or organization,
- `python_package_name`: name of the Python "back-end" package used in your custom widget.
- `npm_package_name`: name for the npm "front-end" package holding the JavaScript
  implementation used in your custom widget.
- `npm_package_version`: initial version of the npm package.
- `jlab_extension_name`: name for the jupyterlab extension npm package (must be different
  from `npm_package_name`).
- `jlab_extension_id`: extension ID to supply to JupyterLab when registering the extension.
  The recommended format is "jupyter.extensions.<Your UNIQUE designator here>".
- `project_short_description` : a short description for your project that will
  be used for both the "back-end" and "front-end" packages.

After this, you will have a directory containing files used for creating a
custom Jupyter widget. You will now be able to easily package and distribute
your custom Jupyter widget.