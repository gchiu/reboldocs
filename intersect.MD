USAGE:
     INTERSECT series1 series2 /case /skip size

DESCRIPTION:
     Returns the intersection of two data series.
     INTERSECT is a function .

RETURNS:
    (undocumented)

ARGUMENTS:
    series1 [any-array! any-string! binary! bitset! typeset!]
    series2 [any-array! any-string! binary! bitset! typeset!]

REFINEMENTS:
    /case
        Uses case-sensitive comparison
    /skip
        Treat the series as records of fixed size
    size [integer!]
