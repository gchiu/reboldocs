USAGE:
     DEBASE value /base base-value

DESCRIPTION:
     Decodes binary-coded string (BASE-64 default) to binary value.
     DEBASE is a function .

RETURNS: [binary!]

ARGUMENTS:
    value [binary! string!]
        The string to decode

REFINEMENTS:
    /base
        Binary base to use
    base-value [integer!]
        The base to convert from: 64, 16, or 2
