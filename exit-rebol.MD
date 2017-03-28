USAGE:
     EXIT-REBOL  /with value

DESCRIPTION:
     Stop the current Rebol interpreter, cannot be caught by CATCH/QUIT.
     EXIT-REBOL is a function .

RETURNS:
    (undocumented)

REFINEMENTS:
    /with
        Yield a result (mapped to an integer if given to shell)
    value [any-value!]
        See: http://en.wikipedia.org/wiki/Exit_status
