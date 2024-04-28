# Installation

*Conda users, please make sure to `conda install pip` before running any pip installation if you want to install `tareeq` into your conda environment.*

`tareeq` is published on PyPI. So, to install the latest version from PyPI, simply run the following code to install the package:

```bash
pip install tareeq
```
If you also want to download the dependencies needed to run optional tutorials, please use `pip install tareeq[dev,docs]` or `pip install 'tareeq[dev,docs]'` (for `zsh` users).

#### Building from source

To build `tareeq` from source, pip install using:

```bash
git clone git@github.com:TareeQ-AI/tareeq.git tareeq
cd tareeq
pip install --upgrade .
```

If you also want to download the dependencies needed to run optional tutorials, please use `pip install --upgrade .[dev,docs]` or `pip install --upgrade '.[dev,docs]'` (for `zsh` users).

#### Installation for Devs

If you intend to contribute to this project, please install `tareeq` in editable mode as follows:
```bash
git clone git@github.com:TareeQ-AI/tareeq.git tareeq
cd tareeq
pip install -e .[dev, docs]
```

Please use `pip install -e '.[dev, docs]'` if you are a `zsh` user.

Installing the package in the usual non-editable mode would require a developer to upgrade their pip installation (i.e. run `pip install --upgrade .`) every time they update the package source code.
