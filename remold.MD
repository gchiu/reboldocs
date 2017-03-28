USAGE:
     REMOLD value /only /all /flat

DESCRIPTION:
     Reduces and converts a value to a REBOL-readable string.
     REMOLD is a function .

RETURNS:
    (undocumented)

ARGUMENTS:
    value
        The value to reduce and mold

REFINEMENTS:
    /only
        For a block value, mold only its contents, no outer []
    /all
        Mold in serialized format
    /flat
        No indentation
