USAGE:
     SWITCH value cases /default default-case /all /strict /opt

DESCRIPTION:
     Selects a choice and evaluates the block that follows it.
     SWITCH is a function .

RETURNS: [<opt> any-value!]
    Last case evaluation, or void if no cases matched

ARGUMENTS:
    value [any-value!]
        Target value
    cases [block!]
        Block of cases (comparison lists followed by block branches)

REFINEMENTS:
    /default
        Default case if no others found
    default-case
        Block to execute (or value to return)
    /all
        Evaluate all matches (not just first one)
    /strict
        Use STRICT-EQUAL? when comparing cases instead of EQUAL?
    /opt
        If branch runs and returns void, do not convert it to BLANK!
