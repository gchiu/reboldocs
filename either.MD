USAGE:
     EITHER condition true-branch false-branch /only /opt

DESCRIPTION:
     If TRUE condition?, evaluate first branch, else evaluate second branch.
     EITHER is a function .

RETURNS: [<opt> any-value!]

ARGUMENTS:
    condition [any-value!]
    true-branch [<opt> any-value!]
    false-branch [<opt> any-value!]

REFINEMENTS:
    /only
        Return block and function branches instead of evaluating them
    /opt
        Do not convert void branch results to BLANK!
