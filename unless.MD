USAGE:
     UNLESS condition branch /only /opt

DESCRIPTION:
     If FALSE? condition, return evaluation of branch value.
     UNLESS is a function .

RETURNS: [<opt> any-value!]
    Void on FALSE?, branch result if TRUE? condition (may be void)

ARGUMENTS:
    condition [any-value!]
    branch [<opt> any-value!]
        Evaluated if block or function and not /ONLY

REFINEMENTS:
    /only
        Return block and function branches instead of evaluating them
    /opt
        If branch runs and returns void, do not convert it to BLANK!
