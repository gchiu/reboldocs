USAGE:
     EITHER* condition true-branch false-branch /only

DESCRIPTION:
     Same as EITHER/OPT (return void, not blank, if branch evaluates to void)
     EITHER* is a specialization of EITHER .

ARGUMENTS:
    condition [any-value!]
    true-branch [<opt> any-value!]
    false-branch [<opt> any-value!]

REFINEMENTS:
    /only
        Return block and function branches instead of evaluating them
