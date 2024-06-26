# EnzSolvStab

## Requirements

* Windows, Linux, and MacOS should be supported
* A recent installation of Python, version 3.9 or later
* The `virtualenv` package

We have tested the software successfully using Ubuntu 22.04, running Python 3.10.6, and these package versions:

```
jupyterlab 4.1.6
numpy 1.20.3
pandas 1.2.4
matplotlib 3.6.2
scipy 1.5.3
tqdm 4.61.0
```

The software was additionally tested on Red Hat Enterprise Linux 9.2 running Python 3.10.8, and these package versions:
```
jupyterlab 4.1.4
numpy 1.24.4
pandas 2.1.4
matplotlib 3.6.2
scipy 1.11.4
tqdm 4.66.1
```

## Installation

We recommend creating a virtual environment and installing dependencies in that environment, e.g.:

```bash
# create a new virtual environment
virtualenv venv

# enter virtual environment
source venv/bin/activate

# install dependencies
pip install -r requirements.txt
```

Installation should complete in a few minutes if installing from wheels, and 1-2 hours if recompiling numpy and pandas is needed.

## Running the Examples

```bash
# enter virtual environment
source venv/bin/activate

# launch a jupyter lab instance inside virtual environment
jupyter lab
```

Have a look at the included Jupyter Notebooks for the included fitting code and expected outputs. All fits should complete in a few minutes on a normal desktop computer.
