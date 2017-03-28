USAGE:
     IF* condition branch /only

DESCRIPTION:
     Same as IF/OPT (return void, not blank, if branch evaluates to void)
     IF* is a specialization of IF .

ARGUMENTS:
    condition [any-value!]
    branch [<opt> any-value!]
        Evaluated if block or function and not /ONLY

REFINEMENTS:
    /only
        Return block and function branches instead of evaluating them
