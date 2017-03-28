USAGE:
     CATCH? block /name names /quit /any /with handler

DESCRIPTION:
     Variation of CATCH which returns TRUE if a throw is caught, FALSE if not
     CATCH? is a specialization of CATCH .

ARGUMENTS:
    block [block!]
        Block to evaluate

REFINEMENTS:
    /name
        Catches a named throw
    names [block! word! function! object!]
        Names to catch (single name if not block)
    /quit
        Special catch for QUIT native
    /any
        Catch all throws except QUIT (can be used with /QUIT)
    /with
        Handle thrown case with code
    handler [block! function!]
        If FUNCTION!, spec matches [value name]
