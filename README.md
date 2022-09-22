# cdktf-remote-template-python-poetry

A [terraform-cdk](https://github.com/hashicorp/terraform-cdk) CLI template for Python projects using [PDM](https://pdm.fming.dev/latest/) for dependency management.

> This template was forked from https://github.com/johnfraney/cdktf-remote-template-python-poetry.

## Usage

Before starting a project with this template, make sure [PDM](https://python-poetry.org/docs/#installation) is installed on your system.

Then, in the `--template` argument to `cdktf init`, include the URL to a `.zip` file of this project.
The `.zip` file can either be a branch:

```bash
cdktf init --template="https://github.com/menzenski/cdktf-remote-template-python-poetry/archive/refs/heads/main.zip" --local
```

Or a tag:

```bash
cdktf init --template="https://github.com/menzenski/cdktf-remote-template-python-poetry/archive/refs/tags/v1.1.0.zip --local
```
