USAGE:
     ANY block 

DESCRIPTION:
     Short-circuiting version of OR, using a block of expressions as input.
     ANY is a function .

RETURNS: [<opt> any-value!]
    The first TRUE? evaluative result, or BLANK! value if all FALSE?

ARGUMENTS:
    block [block!]
        Block of expressions.  Void evaluations are ignored.
