# Unreachable Return Statement in Julia

This example demonstrates a common issue in Julia where an unreachable `return` statement doesn't cause an error. This can make it harder to debug logical flaws.

The `bug.jl` file contains a function with an unreachable return statement.  The `bugSolution.jl` provides a better way to handle the situation.

This is a useful example to illustrate how to avoid this issue and improve code robustness.