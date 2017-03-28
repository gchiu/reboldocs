USAGE:
     WRITE destination data /part limit /seek index /append /allow access /lines

DESCRIPTION:
     Writes to a file, URL, or port - auto-converts text strings.
     WRITE is a function .

RETURNS:
    (undocumented)

ARGUMENTS:
    destination [port! file! url! block!]
    data [binary! string! block! object!]
        Data to write (non-binary converts to UTF-8)

REFINEMENTS:
    /part
        Partial write a given number of units
    limit [any-number!]
    /seek
        Write at a specific position
    index [any-number!]
    /append
        Write data at end of file
    /allow
        Specifies protection attributes
    access [block!]
    /lines
        Write each value in a block as a separate line
