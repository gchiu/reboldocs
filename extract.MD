USAGE:
     EXTRACT series width /index pos /default value /into output /local len val

DESCRIPTION:
     Extracts a value from a series at regular intervals.
     EXTRACT is a function .

RETURNS:
    (undocumented)

ARGUMENTS:
    series [any-series!]
    width [integer!]
        Size of each entry (the skip)

REFINEMENTS:
    /index
        Extract from an offset position
    pos [any-number! logic! block!]
        The position(s)
    /default
        Use a default value instead of blank
    value
        The value to use (will be called each time if a function)
    /into
        Insert into a buffer instead (returns position after insert)
    output [any-series!]
        The buffer series (modified)
    /local
    len
    val
