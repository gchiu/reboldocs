USAGE:
     UNIQUE series /case /skip size

DESCRIPTION:
     Returns the data set with duplicates removed.
     UNIQUE is a function .

RETURNS:
    (undocumented)

ARGUMENTS:
    series [any-array! any-string! binary! bitset! typeset!]

REFINEMENTS:
    /case
        Use case-sensitive comparison (except bitsets)
    /skip
        Treat the series as records of fixed size
    size [integer!]
