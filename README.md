# multidim

Multidimensional Analysis WNE University of Warsaw

## Installation

```bash
$ git clone https://github.com/Polkas/multidim
$ # (optional) open multidim directory in VScode
$ # (optional) open (zsh or bash) terminal in VScode
```

optional part start - virtual env

```bash
$ cd multidim
$ python -m venv .venv
$ # useful for Windows https://docs.python.org/3/library/venv.html
$ # PowerShell command needed - 
$ # Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
$ # activate is only a one click in VScode
$ # on Windows sth like .venv\Scripts\activate
$ source .venv/bin/activate
```

optional part end - virtual env

```bash
$ pip install ".[all]"
$ now open any notebook from src/multidim/notebooks in VScode
$ # or use 
$ jupyter notebook
$ # when ready to end Ctrl-C
$ deactivate
```

or simply open the github codespaces and go to src/multidim/notebooks

When you want to contribute, then fork https://github.com/Polkas/multidim

```bash
$ git clone https://github.com/YOURUSER/multidim
...
```

Please, `git pull` regulary and `pip install ".[all]"` might be needed too].

## Contributing

Interested in contributing? Check out the contributing guidelines. Please note that this project is released with a Code of Conduct. By contributing to this project, you agree to abide by its terms.

## License

`multidim` was created by Maciej Nasinski. It is licensed under the terms of the MIT license.
