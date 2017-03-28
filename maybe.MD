USAGE:
     MAYBE test value /?

DESCRIPTION:
     Check value using tests (match types, TRUE? or FALSE?, filter function)
     MAYBE is a function .

RETURNS: [<opt> any-value!]
    The input value or BLANK! if no match, void if FALSE? and matched

ARGUMENTS:
    test [function! datatype! typeset! block! logic!]
    value [<opt> any-value!]

REFINEMENTS:
    /?
        Return LOGIC! of match vs. pass-through of value or blank
