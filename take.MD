USAGE:
     TAKE series /part limit /deep /last

DESCRIPTION:
     Removes and returns one or more elements.
     TAKE is a function .

RETURNS: [<opt> any-value!]

ARGUMENTS:
    series [any-series! port! gob! blank! varargs!]
        At position (modified)

REFINEMENTS:
    /part
        Specifies a length or end position
    limit [any-number! any-series! pair! bar!]
    /deep
        Also copies series values within the block
    /last
        Take it from the tail end
