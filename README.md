# Task Py

A prescriptive Python [Task][] runner.

## Prescriptivity

* Code linting by [flake8][]
* The [pytest][] test framework
* Source formatting with [Black][] and [isort][]
* Packaging and dependency management with [Poetry][]

## Install

Install [Task][]:

    $ brew install go-task

Install Taskfile into project:

    $ curl -o Taskfile.yml https://raw.githubusercontent.com/retr0h/task-py/main/Taskfile.yml
    $ task

Install Poetry:

    * See full [installation documentation][]

## Usage

Check dependencies are installed:

    $ task deps

Module maintenance:

    $ task mod

Report likely mistakes in packages:

    $ task vet

Run Python program:

    $ task run

Test packages:

    $ task unit

Test all:

    $ task test

Generate coverage:

    $ task cov

Reformat files whose formatting differs from `py_fmt_command`:

    $ task fmt

Check files whose formatting differs from `py_fmt_command`:

    $ task fmt:check

List targets:

    $ task

## License

The [MIT] License.

[Task]: https://github.com/go-task/task
[flake8]: https://flake8.pycqa.org/en/latest/
[pytest]: https://docs.pytest.org/en/7.3.x/
[Black]: https://pypi.org/project/black/
[isort]: https://pycqa.github.io/isort/
[Poetry]: https://pypi.org/project/poetry/
[installation documentation] https://python-poetry.org/docs/#installing-with-the-official-installer
[MIT]: LICENSE
