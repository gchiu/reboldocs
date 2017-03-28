USAGE:
     MATH expr /only

DESCRIPTION:
     Process expression taking "usual" operator precedence into account.
     MATH is a function .

RETURNS:
    (undocumented)

ARGUMENTS:
    expr [block!]
        Block to evaluate

REFINEMENTS:
    /only
        Translate operators to their prefix calls, but don't execute
