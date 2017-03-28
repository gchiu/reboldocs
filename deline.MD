USAGE:
     DELINE string /lines

DESCRIPTION:
     Converts string terminators to standard format, e.g. CRLF to LF.
     DELINE is a function .

RETURNS:
    (undocumented)

ARGUMENTS:
    string [any-string!]
        Will be modified (unless /LINES used)

REFINEMENTS:
    /lines
        Return block of lines (works for LF, CR, CR-LF endings)
