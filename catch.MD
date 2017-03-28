USAGE:
     CATCH block /name names /quit /any /with handler /?

DESCRIPTION:
     Catches a throw from a block and returns its value.
     CATCH is a function .

RETURNS: [<opt> any-value!]

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
    /?
        Instead of result or catch, return LOGIC! of if a catch occurred
