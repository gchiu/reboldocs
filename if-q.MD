USAGE:
     IF? condition branch /only /opt

DESCRIPTION:
     Variation of IF which returns TRUE if the branch runs, FALSE if not
     IF? is a chained function .

ARGUMENTS:
    condition [any-value!]
    branch [<opt> any-value!]
        Evaluated if block or function and not /ONLY

REFINEMENTS:
    /only
        Return block and function branches instead of evaluating them
    /opt
        If branch runs and returns void, do not convert it to BLANK!
