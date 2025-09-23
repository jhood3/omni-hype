# Hypergraphs


# Dependencies

- [Julia](https://julialang.org/) ≥ 1.9  
- [Python](https://www.python.org/) ≥ 3.8
  
This software uses a Python interface with a Julia backend. Both may be installed using the links above. 
It requires the following Julia packages:

## Julia 

### Standard libraries (included with Julia)
- Statistics
- LinearAlgebra
- Random
- Base.Threads

### External packages
- [Distributions.jl](https://github.com/JuliaStats/Distributions.jl)
- [StatsFuns.jl](https://github.com/JuliaStats/StatsFuns.jl)
- [SpecialFunctions.jl](https://github.com/JuliaMath/SpecialFunctions.jl)
- [Combinatorics.jl](https://github.com/JuliaMath/Combinatorics.jl)
- [NPZ.jl](https://github.com/fhs/NPZ.jl)
- [Distances.jl](https://github.com/JuliaStats/Distances.jl)
- [Zygote.jl](https://github.com/FluxML/Zygote.jl)
- [ArgParse.jl](https://github.com/carlobaldassi/ArgParse.jl)
- [JSON.jl](https://github.com/JuliaIO/JSON.jl)

### Installation
You can install all dependencies by running in the Julia REPL:

```julia
using Pkg
Pkg.add([
    "Distributions",
    "StatsFuns",
    "SpecialFunctions",
    "Combinatorics",
    "NPZ",
    "Distances",
    "Zygote",
    "ArgParse",
    "JSON",
])

## Python

**External packages:**
- `numpy`
- `julia` (PyJulia bridge)

**Standard libraries (included with Python):**
- `subprocess`
- `json`

**Installation (in Python environment):**

```bash
# Upgrade pip and install required packages
python -m pip install --upgrade pip
python -m pip install numpy julia


