USAGE:
     REDUCE value /into target

DESCRIPTION:
     Evaluates expressions and returns multiple results.
     REDUCE is a function .

RETURNS: [<opt> any-value!]

ARGUMENTS:
    value [<opt> any-value!]
        If BLOCK!, expressions are reduced, otherwise single value.

REFINEMENTS:
    /into
        Output results into a series with no intermediate storage
    target [any-array!]
