USAGE:
     CASE cases /all /only /opt

DESCRIPTION:
     Evaluates each condition, and when true, evaluates what follows it.
     CASE is a function .

RETURNS: [<opt> any-value!]
    Last matched case evaluation, or void if no cases matched

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
