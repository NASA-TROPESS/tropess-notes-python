# tropess-notes-python

Jupyter Notebooks for TROPESS Notes (in Python)

## Setup

For initial setup see:

[https://github.com/NASA-TROPESS/tropess-notes/blob/main/dev/setup-macos.md](https://github.com/NASA-TROPESS/tropess-notes/blob/main/dev/setup-macos.md)

## How to run stuff

Clone this repository:

```bash
git clone https://github.com/NASA-TROPESS/tropess-notes-python.git
```

Configure the project to create a local Python virtual environment and install all required Python packages: 

```bash
# switch dir
cd tropess-notes-python

# configure the project
source configure.sh
```

Start Jupyter Lab:

```bash
jupyter lab
```

From here pick any of the notebooks (`*.ipynb`) and try to run it. Before running the code, make sure you have downloaded the TROPESS sample data  to `./data` as documented in the examples. 

 
