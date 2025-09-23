# OMNI-HYPE-SMT
Software for learning mesoscale structure in higher-order networks and hypergraphs corresponding to the model and inference algorithm presented in this [paper](https://arxiv.org/abs/2505.21748). The code has been tested on MacOS 15.0 and Linux. 

## Dependencies

- [Julia](https://julialang.org/) ≥ 1.9.1 
- [Python](https://www.python.org/) ≥ 3.11.1
  
This software uses a Python interface and a Julia backend. Both may be installed using the links above. 
It requires the following Julia packages:

### Julia 

#### Standard libraries (included with Julia)
- Statistics
- LinearAlgebra
- Random
- Base.Threads

#### External packages
- [Distributions.jl](https://github.com/JuliaStats/Distributions.jl) v0.25.117
- [StatsFuns.jl](https://github.com/JuliaStats/StatsFuns.jl) v0.9.18
- [SpecialFunctions.jl](https://github.com/JuliaMath/SpecialFunctions.jl) v1.8.8
- [Combinatorics.jl](https://github.com/JuliaMath/Combinatorics.jl) v1.0.2
- [NPZ.jl](https://github.com/fhs/NPZ.jl) v0.4.3
- [Distances.jl](https://github.com/JuliaStats/Distances.jl) v0.10.12
- [Zygote.jl](https://github.com/FluxML/Zygote.jl) v0.6.75
- [ArgParse.jl](https://github.com/carlobaldassi/ArgParse.jl) v1.2.0
- [JSON.jl](https://github.com/JuliaIO/JSON.jl) v0.21.4

#### Installation
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
```

### Python

**External packages**
- `numpy` v1.26.1
- `julia` (PyJulia bridge) v0.6.1

**Standard libraries (included with Python)**
- `subprocess`
- `json`

**Installation (in Python environment)**

```bash
# Upgrade pip and install required packages
python -m pip install --upgrade pip
python -m pip install numpy julia
```


