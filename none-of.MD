USAGE:
     NONE-OF block 

DESCRIPTION:
     Short circuiting version of NOR, using a block of expressions as input.
     NONE-OF is a function .

RETURNS: [<opt> bar! blank!]
    TRUE if all expressions are FALSE?, or BLANK if any are TRUE?

ARGUMENTS:
    block [block!]
        Block of expressions.  Void evaluations are ignored.
