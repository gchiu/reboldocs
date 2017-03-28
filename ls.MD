USAGE:
     LS 'path /l /f /d /r /i indent

DESCRIPTION:
     Print contents of a directory (ls).
     LS is a function .

ARGUMENTS:
    'path [<end> file! word! path! string!]
        Accepts %file, :variables, and just words (as dirs)

REFINEMENTS:
    /l
        Line of info format
    /f
        Files only
    /d
        Dirs only
    /r
        Recursive
    /i
        Indent
    indent
