USAGE:
     PROTECT value /deep /words /values /hide

DESCRIPTION:
     Protect a series or a variable from being modified.
     PROTECT is a function .

RETURNS:
    (undocumented)

ARGUMENTS:
    value [word! any-series! bitset! map! object! module!]

REFINEMENTS:
    /deep
        Protect all sub-series/objects as well
    /words
        Process list as words (and path words)
    /values
        Process list of values (implied GET)
    /hide
        Hide variables (avoid binding and lookup)
