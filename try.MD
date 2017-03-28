USAGE:
     TRY block /except code

DESCRIPTION:
     Tries to DO a block and returns its value or an error.
     TRY is a function .

RETURNS: [<opt> any-value!]

ARGUMENTS:
    block [block!]

REFINEMENTS:
    /except
        On exception, evaluate code
    code [block! function!]
