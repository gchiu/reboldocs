USAGE:
     MOVE source offset /part limit /skip size /to

DESCRIPTION:
     Move a value or span of values in a series.
     MOVE is a function .

RETURNS:
    (undocumented)

ARGUMENTS:
    source [any-series!]
        Source series (modified)
    offset [integer!]
        Offset to move by, or index to move to

REFINEMENTS:
    /part
        Move part of a series
    limit [integer!]
        The length of the part to move
    /skip
        Treat the series as records of fixed size
    size [integer!]
        Size of each record
    /to
        Move to an index relative to the head of the series
