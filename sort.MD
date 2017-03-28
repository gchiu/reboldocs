USAGE:
     SORT series /case /skip size /compare comparator /part limit /all /reverse

DESCRIPTION:
     Sorts a series; default sort order is ascending.
     SORT is a function .

RETURNS:
    (undocumented)

ARGUMENTS:
    series [any-series!]
        At position (modified)

REFINEMENTS:
    /case
        Case sensitive sort
    /skip
        Treat the series as records of fixed size
    size [integer!]
        Size of each record
    /compare
        Comparator offset, block or function
    comparator [integer! block! function!]
    /part
        Sort only part of a series
    limit [any-number! any-series!]
        Length of series to sort
    /all
        Compare all fields
    /reverse
        Reverse sort order
