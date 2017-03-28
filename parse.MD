USAGE:
     PARSE input rules /case

DESCRIPTION:
     Parses a series according to grammar rules and returns a result.
     PARSE is a function .

RETURNS:
    (undocumented)

ARGUMENTS:
    input [any-series!]
        Input series to parse (default result for successful match)
    rules [block! string! blank!]
        Rules to parse by (STRING! and BLANK!/none! are deprecated)

REFINEMENTS:
    /case
        Uses case-sensitive comparison
