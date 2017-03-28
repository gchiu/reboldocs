USAGE:
     CASE* cases /all /only

DESCRIPTION:
     Same as CASE/OPT (return void, not blank, if branch evaluates to void)
     CASE* is a specialization of CASE .

ARGUMENTS:
    cases [block!]
        Block of cases (conditions followed by branches)

REFINEMENTS:
    /all
        Evaluate all cases (do not stop at first TRUE? case)
    /only
        Return block and function branches instead of evaluating them
