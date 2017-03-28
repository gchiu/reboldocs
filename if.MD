USAGE:
     IF condition branch /only /opt

DESCRIPTION:
     If TRUE? condition, return evaluation of branch value.
     IF is a function .

RETURNS: [<opt> any-value!]
    void on FALSE?, branch result if TRUE? or BLANK! if void

ARGUMENTS:
    condition [any-value!]
    branch [<opt> any-value!]
        Evaluated if block or function and not /ONLY

REFINEMENTS:
    /only
        Return block and function branches instead of evaluating them
    /opt
        If branch runs and returns void, do not convert it to BLANK!
