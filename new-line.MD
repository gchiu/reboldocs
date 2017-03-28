USAGE:
     NEW-LINE position mark /all /skip size

DESCRIPTION:
     Sets or clears the new-line marker within a block or group.
     NEW-LINE is a function .

RETURNS:
    (undocumented)

ARGUMENTS:
    position [block! group!]
        Position to change marker (modified)
    mark
        Set TRUE for newline

REFINEMENTS:
    /all
        Set/clear marker to end of series
    /skip
        Set/clear marker periodically to the end of the series
    size [integer!]
