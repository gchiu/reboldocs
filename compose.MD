USAGE:
     COMPOSE value /deep /only /into out

DESCRIPTION:
     Evaluates only the GROUP!s in a block of expressions, returning a block.
     COMPOSE is a function .

RETURNS:
    (undocumented)

ARGUMENTS:
    value
        Block to compose (or any other type evaluates to itself)

REFINEMENTS:
    /deep
        Compose nested blocks
    /only
        Insert a block as a single value (not the contents of the block)
    /into
        Output results into a series with no intermediate storage
    out [any-array! any-string! binary!]
