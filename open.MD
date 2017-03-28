USAGE:
     OPEN spec /new /read /write /seek /allow access

DESCRIPTION:
     Opens a port; makes a new port from a specification if necessary.
     OPEN is a function .

RETURNS:
    (undocumented)

ARGUMENTS:
    spec [port! file! url! block!]

REFINEMENTS:
    /new
        Create new file - if it exists, reset it (truncate)
    /read
        Open for read access
    /write
        Open for write access
    /seek
        Optimize for random access
    /allow
        Specifies protection attributes
    access [block!]
