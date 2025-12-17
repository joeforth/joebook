This repo will host book content for CHEM502 Chemical Data, Discovery and Design.

The book uses [Jupyter Book](https://jupyterbook.org/en/stable/intro.html)

The module book is available at https://joeforth.github.io/chem502_book/.

To create a conda environment, use the environment.yml file.

`conda env create --file environment.yml`

The requirements_conda[_mac].txt files might also work to create a conda environment with the same versions as the code was created:

`conda create --name <env> --file requirements_conda[_mac].txt`

but using the yaml file via the earlier command is probably less likely to cause issues.

The book is based on the original version by Sam Chong who still owns the copyright © 2024-25 Sam Chong and is released under under the CC BY-NC-SA 4.0.
