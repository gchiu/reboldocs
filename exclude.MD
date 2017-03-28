USAGE:
     EXCLUDE series exclusions /case /skip size

DESCRIPTION:
     Returns the first data set less the second data set.
     EXCLUDE is a function .

RETURNS:
    (undocumented)

ARGUMENTS:
    series [any-array! any-string! binary! bitset! typeset!]
        original data
    exclusions [any-array! any-string! binary! bitset! typeset!]
        data to exclude from series

REFINEMENTS:
    /case
        Uses case-sensitive comparison
    /skip
        Treat the series as records of fixed size
    size [integer!]
