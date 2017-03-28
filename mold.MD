USAGE:
     MOLD value /only /all /flat

DESCRIPTION:
     Converts a value to a REBOL-readable string.
     MOLD is a function .

RETURNS:
    (undocumented)

ARGUMENTS:
    value [any-value!]
        The value to mold

REFINEMENTS:
    /only
        For a block value, mold only its contents, no outer []
    /all
        Use construction syntax
    /flat
        No indentation
