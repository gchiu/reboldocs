USAGE:
     COLLECT body /into output

DESCRIPTION:
     Evaluate body, and return block of values collected via keep function.
     COLLECT is a specialized function .

ARGUMENTS:
    body [block!]
        Block to evaluate

REFINEMENTS:
    /into
        Insert into a buffer instead (returns position after insert)
    output [any-series!]
        The buffer series (modified)
