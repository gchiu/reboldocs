USAGE:
     READ source /part limit /seek index /string /lines

DESCRIPTION:
     Read from a file, URL, or other port.
     READ is a function .

RETURNS:
    (undocumented)

ARGUMENTS:
    source [port! file! url! block!]

REFINEMENTS:
    /part
        Partial read a given number of units (source relative)
    limit [any-number!]
    /seek
        Read from a specific position (source relative)
    index [any-number!]
    /string
        Convert UTF and line terminators to standard text string
    /lines
        Convert to block of strings (implies /string)
