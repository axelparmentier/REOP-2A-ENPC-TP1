# REOP 2A - TP1

This practical session is an introduction to Julia for optimization.

## Before the session

Please try to prepare the session by yourself before coming to class. This means you have to:

### 1. Install Julia

Go to https://julialang.org/downloads/platform/ and follow the instructions relevant to your OS (Windows, Mac or Linux).

### 2. Clone the project repository

Go to https://github.com/axelparmentier/REOP-2A-ENPC-TP1, click on the green button `Code` and then `Download ZIP`. Extract the archive wherever you want.

### 3. Install Jupyter

Open a terminal and launch Julia using the command `julia`. Then, copy-paste the following commands into the REPL:
```julia
using Pkg
Pkg.add("IJulia")
using IJulia
notebook()
```

This should open an internet browser and display a window called Jupyter.

### 4. Open the notebook and run it once

Within Jupyter, navigate to the place where you extracted `REOP-2A-ENPC-TP1` and open the file named `Metaheuristics using Julia.ipynb`. Try to run every cell once in order. If no bug is triggered, you are ready for the practical session.

