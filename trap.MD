USAGE:
     TRAP block /with handler /?

DESCRIPTION:
     Tries to DO a block, trapping error as return value (if one is raised).
     TRAP is a function .

RETURNS: [<opt> any-value!]

ARGUMENTS:
    block [block!]

REFINEMENTS:
    /with
        Handle error case with code
    handler [block! function!]
        If FUNCTION!, spec allows [error [error!]]
    /?
        Instead of result or error, return LOGIC! of if a trap occurred
