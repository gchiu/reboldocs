USAGE:
     ENBASE value /base base-value

DESCRIPTION:
     Encodes data into a binary, hexadecimal, or base-64 ASCII string.
     ENBASE is a function .

RETURNS: [string!]

ARGUMENTS:
    value [binary! string!]
        If string, will be UTF8 encoded

REFINEMENTS:
    /base
        Binary base to use (BASE-64 default)
    base-value [integer!]
        The base to convert to: 64, 16, or 2
