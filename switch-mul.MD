USAGE:
     SWITCH* value cases /default default-case /all /strict

DESCRIPTION:
     Same as SWITCH/OPT (return void, not blank, if branch evaluates to void)
     SWITCH* is a specialization of SWITCH .

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
