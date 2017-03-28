USAGE:
     UNPROTECT value /deep /words /values /hide

DESCRIPTION:
     Unprotect a series or a variable (it can again be modified).
     UNPROTECT is a function .

RETURNS:
    (undocumented)

ARGUMENTS:
    value [word! any-series! bitset! map! object! module!]

REFINEMENTS:
    /deep
        Protect all sub-series as well
    /words
        Block is a list of words
    /values
        Process list of values (implied GET)
    /hide
        HACK to make PROTECT and UNPROTECT have the same signature
