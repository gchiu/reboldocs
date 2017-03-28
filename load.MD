USAGE:
     LOAD source /header /all /type ftype

DESCRIPTION:
     Loads code or data from a file, URL, string, or binary.
     LOAD is a function .

RETURNS:
    (undocumented)

ARGUMENTS:
    source [file! url! string! binary! block!]
        Source or block of sources

REFINEMENTS:
    /header
        Result includes REBOL header object (preempts /all)
    /all
        Load all values (does not evaluate REBOL header)
    /type
        Override default file-type; use NONE to always load as code
    ftype [word! blank!]
        E.g. text, markup, jpeg, unbound, etc.
