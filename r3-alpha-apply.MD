USAGE:
     R3-ALPHA-APPLY action block /only

DESCRIPTION:
     Apply a function to a reduced block of arguments.
     R3-ALPHA-APPLY is a function .

RETURNS: [<opt> any-value!]

ARGUMENTS:
    action [function!]
        Function value to apply
    block [block!]
        Block of args, reduced first (unless /only)

REFINEMENTS:
    /only
        Use arg values as-is, do not reduce the block
