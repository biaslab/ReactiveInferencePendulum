# Reactive inference with RxInfer.jl

This repository contains an example of reactive inference with [RxInfer.jl]() library for simple pendulum dynamics. 
The example implements an interactive environment where a user can change different parameters of the pendulum
dynamics on the fly and see the result of the actions made by `RxInfer` agent implemention. 

## Installation instructions

To (locally) reproduce this project, do the following:

0. Go to the [RxInfer.jl](https://github.com/biaslab/RxInfer.jl) and click the `Star` button, 
otherwise the demo will not work.
1. You need the Julia programming language preinstalled. The `RxInfer.jl` works with Julia 1.6-1.9, but the demo has 
been tested with the latest 1.8.5 release. We recommend using the [`juliaup`](https://github.com/JuliaLang/juliaup) 
Julia version manager to easliy install multiple versions of Julia.
2. The repository comes with the preconfigured environment written in the `Project.toml` and `Manifest.toml`.
The notebook instantiates and installs all required packages automatically. Note, however, that initial installation
and precompilation may take a significant amount of time.
3. Simply click `Cells` -> `Run all` and wait for the instantion of the example. Julia may take several minutes to 
precompile the code.
