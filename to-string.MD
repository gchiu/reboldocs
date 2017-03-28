USAGE:
     TO-STRING value /astral handler

DESCRIPTION:
     Like TO STRING! but with additional options.
     TO-STRING is a function .

RETURNS:
    (undocumented)

ARGUMENTS:
    value [any-value!]
        Value to convert to a string.

REFINEMENTS:
    /astral
        Provide special handling for codepoints bigger than 0xFFFF
    handler [function! string! char! blank!]
        If function, receives integer argument of large codepoint value
