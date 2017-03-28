USAGE:
     ALL block 

DESCRIPTION:
     Short-circuiting variant of AND, using a block of expressions as input.
     ALL is a function .

RETURNS: [<opt> any-value!]
    Product of last evaluation if all TRUE?, else a BLANK! value.

ARGUMENTS:
    block [block!]
        Block of expressions.  Void evaluations are ignored.
