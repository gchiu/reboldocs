USAGE:
     UNLESS* condition branch /only

DESCRIPTION:
     Same as UNLESS/OPT (return void, not blank, if branch evaluates to void)
     UNLESS* is a specialization of UNLESS .

ARGUMENTS:
    condition [any-value!]
    branch [<opt> any-value!]
        Evaluated if block or function and not /ONLY

REFINEMENTS:
    /only
        Return block and function branches instead of evaluating them
