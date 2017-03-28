USAGE:
     TRAP? block /with handler

DESCRIPTION:
     Variation of TRAP which returns TRUE if an error traps, FALSE if not
     TRAP? is a specialization of TRAP .

ARGUMENTS:
    block [block!]

REFINEMENTS:
    /with
        Handle error case with code
    handler [block! function!]
        If FUNCTION!, spec allows [error [error!]]
