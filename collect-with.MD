USAGE:
     COLLECT-WITH 'name body /into output

DESCRIPTION:
     Evaluate body, and return block of values collected via keep function.
     COLLECT-WITH is a function .

RETURNS: [block!]

ARGUMENTS:
    'name [word! lit-word!]
        Name to which keep function will be assigned (<local> if word!)
    body [block!]
        Block to evaluate

REFINEMENTS:
    /into
        Insert into a buffer instead (returns position after insert)
    output [any-series!]
        The buffer series (modified)
