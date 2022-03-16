# wordle-julia
Wordle solutions in Julia.

Started as an attempt to find the optimal Wordle solution as a kind of a tree, using a branch-and-bound approach. I was inspired by the 3blue1brown's video on this topic on YouTube.

Tried the greedy approach first. Couldn't use the `Graphs.jl` package, as I was running of out of memory with the longer word list.

Solving the optimal problem without the package would be more challenging; but I hope to try it, if time permits.
