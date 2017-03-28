USAGE:
     CASE? cases /all /only /opt

DESCRIPTION:
     Variation of CASE which returns TRUE if any cases run, FALSE if not
     CASE? is a chained function .

ARGUMENTS:
    cases [block!]
        Block of cases (conditions followed by branches)

REFINEMENTS:
    /all
        Evaluate all cases (do not stop at first TRUE? case)
    /only
        Return block and function branches instead of evaluating them
    /opt
        If branch runs and returns void, do not convert it to BLANK!
