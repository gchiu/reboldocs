USAGE:
     UNLESS? condition branch /only /opt

DESCRIPTION:
     Variation of UNLESS which returns TRUE if the branch runs, FALSE if not
     UNLESS? is a chained function .

ARGUMENTS:
    condition [any-value!]
    branch [<opt> any-value!]
        Evaluated if block or function and not /ONLY

REFINEMENTS:
    /only
        Return block and function branches instead of evaluating them
    /opt
        If branch runs and returns void, do not convert it to BLANK!
