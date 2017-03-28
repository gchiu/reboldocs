USAGE:
     FOREVER body 

DESCRIPTION:
     Evaluates a block endlessly, until an interrupting throw/error/break.
     FOREVER is a function .

RETURNS: [<opt> any-value!]
    Void if plain BREAK, or arbitrary value using BREAK/WITH

ARGUMENTS:
    body [block! function!]
        Block or function to evaluate each time
