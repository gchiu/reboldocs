USAGE:
     CHARSET chars /length len /local charset-length length-of

DESCRIPTION:
     Makes a bitset of chars for the parse function.
     CHARSET is a function .

RETURNS:
    (undocumented)

ARGUMENTS:
    chars [string! block! binary! char! integer!]

REFINEMENTS:
    /length
        Preallocate this many bits
    len [integer!]
        Must be > 0
    /local
    charset-length
    length-of
