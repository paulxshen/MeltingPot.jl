# MeltingPot.jl
Collection of function overloads to make Julia more convenient , concise , and AD (automatic differentiation ) friendly . Specifically :
* Defines arithmetic operations between numbers, tuples, arrays , named tuples and dicts via eager broadcast 
* Slightly modified `keys` `values` for Zygote.jl compatibility 
* `dict` constructor for Zygote.jl compatibility 

## Developers 
Paul Shen <pxshen@alumni.stanford.edu>