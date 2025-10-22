# Contributing to Forevergreen

Thank you for considering working on Forevergreen!

Forevergreen is a sub-component of the University at Buffalo IEEE Student Chapter's Automated Greenhouse project. This repository currently only accepts feature contributions from UB community members that are known to our club officers including students, faculty, staff, and alumni. If you have a contribution that you want to add, we ask that you open a pull request and stop by one of our weekly Automated Greenhouse meetings to discuss your cod with our officers. 

If you are not a member of th UB community, you are free to fork this repository and make any modifications that you need. 

## Contributor's Agreement

By contributing in any way to this project, you agree to release your work under the terms of the included license file(s) in the project.

## Managing the Development Environment

### Using `uv`

This project makes use of [uv](https://docs.astral.sh/uv/), a powerful python package manager and build tool. You can [download uv here](https://docs.astral.sh/uv/getting-started/installation/). 


You can then run most of the commands you would normally run for django using the `uv run` utility. For example, to run the integrated test server use `uv run manage.py runserver`. You can also run the integrated test suite using `uv run manage.py test`. 


### Using `ruff`

This project uses [ruff](https://docs.astral.sh/ruff/) for linting and formatting. You can find the full list of rulesets being checked for in the project's `pyproject.toml`. Before submitting a PR, please make sure to test your code against the project's linting and formatting. 

You can check for linting violations using `uv run ruff check` and fix them using `uv run ruff check --fix`. 

You can check for formatting violations using `uv run ruff format --check` and fix them using `uv run ruff format`. 

## Guidelines for Submitting Contributions

Generally the workflow for this project is to first create GitHub issue describing the changes you want or need to make and getting feedback from others on the project. Once you have received approval from a project lead that you proposed contribution is aligned with the project, you can go ahead and start writing code and submitting pull requests for review. Please allow for time for PRs to be reviewed. This process can be sped up by coming in person to meetings and discussing your implementations with the Automated Greenhouse project lead(s). 

All contributions should generally include a suite of test cases that at least covers all unique paths through a function. This project uses the test suite as an effective form of documentation, allowing new contributors to get up to speed quickly on understand how the system works.
