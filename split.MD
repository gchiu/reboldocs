USAGE:
     SPLIT series dlm /into

DESCRIPTION:
     Split series in pieces: fixed/variable size, fixed number, or delimited
     SPLIT is a function .

RETURNS:
    (undocumented)

ARGUMENTS:
    series [any-series!]
        The series to split
    dlm [block! integer! char! bitset! any-string!]
        Split size, delimiter(s), or rule(s).

REFINEMENTS:
    /into
        If dlm is integer, split in n pieces rather than pieces of length n.
