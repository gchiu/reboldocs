USAGE:
     FAIL reason /where location

DESCRIPTION:
     Interrupts execution by reporting an error (a TRAP can intercept it).
     FAIL is a function .

RETURNS:
    (undocumented)

ARGUMENTS:
    reason [error! string! block!]
        ERROR! value, message string, or failure spec

REFINEMENTS:
    /where
        Specify an originating location other than the FAIL itself
    location [frame! any-word!]
        Frame or parameter at which to indicate the error originated
