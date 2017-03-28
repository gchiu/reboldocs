USAGE:
     WHILE condition body 

DESCRIPTION:
     While a condition block is TRUE?, evaluates another block.
     WHILE is a function .

RETURNS: [<opt> any-value!]
    Last body result or BREAK value, will also be void if never run

ARGUMENTS:
    condition [block! function!]
    body [block! function!]
