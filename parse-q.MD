USAGE:
     PARSE? input rules /case

DESCRIPTION:
     Variant of PARSE that enforces a TRUE or FALSE result from the rules.
     PARSE? is a chained function .

ARGUMENTS:
    input [any-series!]
        Input series to parse (default result for successful match)
    rules [block! string! blank!]
        Rules to parse by (STRING! and BLANK!/none! are deprecated)

REFINEMENTS:
    /case
        Uses case-sensitive comparison
