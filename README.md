# Introduction to Julia for optimization

## Practical session

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

## Useful tips for the class project and beyond

### Documentation

If you are looking for a command or function you don't know, start with https://juliadocs.github.io/Julia-Cheat-Sheet/.

If you want to know more about Julia syntax and functionalities, check out the official documentation at https://docs.julialang.org/en/v1/ or the course https://en.wikibooks.org/wiki/Introducing_Julia. A more in-depth coverage is given by https://benlauwens.github.io/ThinkJulia.jl/latest/book.html.

### Useful libraries

- Graphs: https://juliagraphs.org/
- Optimization: https://www.juliaopt.org/
- Statistics: https://juliastats.org/
- Plotting: https://github.com/JuliaPy/PyPlot.jl or https://github.com/JuliaPlots
- Utilities: https://github.com/timholy/ProgressMeter.jl
- Anything else: https://juliaobserver.com/packages or https://juliahub.com/ui/Packages

### Debugging

Here is a four-step debugging procedure that works 99\% of the time:
1. Try to understand the bug by tracking its origin.
2. If this doesn't work, copy-paste the bug message into Google and read the first three forum answers about it.
3. If that doesn't work, sleep on it and try again tomorrow.
4. If none of the previous methods work, email your teaching assistant.